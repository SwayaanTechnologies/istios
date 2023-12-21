# Custom Resource Definition CRDs

In Kubernetes, Custom Resource Definitions (CRDs) allow you to extend the Kubernetes API and define your own custom resources.

Let's create a simple custom resoucre called `Person` with fields like `name` and `age` and `address`

**Step 1**: Create the Custom Resource Definition (CRD)

Create a YAML file named `person-crd.yaml ` with the following content:

``` yaml
apiVersion: apiextensions.k8s.io/v1
kind: CustomResourceDefinition
metadata:
  name: persons.example.com
spec:
  group: example.com
  versions:
    - name: v1
      served: true
      storage: true
      schema:
        openAPIV3Schema:
          type: object
          properties:
            spec:
              type: object
              properties:
                name:
                  type: string
                age:
                  type: integer
                  minimum: 0
                address:
                  type: string
  names:
    kind: Person
    plural: persons
    singular: person
    shortNames:
      - per
  scope: Namespaced
```
OpenAPI v3 schema definition is added to validate the structure of the Person resource. It defines the name as a string, age as an integer with a minimum value of 0, and address as a string.

**Apply the CRD to your cluster**

```bash +@Output
$ k8s apply -f person-crd.yaml
```

**Step 2:** Create a Custom Resource (CR)

Create a YAML file named `person-instance.yaml` to create an instance of the Person resource:

```yaml
apiVersion: example.com/v1
kind: Person
metadata:
  name: john-doe
spec:
  name: John Doe
  age: 30
  address: "123 Main St, City"

```

**Apply the custom resource to your cluster**

```bash +@Output
$ k8s apply -f person-instance.yaml
```

**Step 3:** Verify and Use the Custom Resource

Verify that the custom resource has been created:

```bash +@Output
$ k8s get persons
```

![](images/crd_output.png)

You can also describe the custom resource to get more details

```bash +@Output
$ k8s describe person john-doe
```

## Delete a CustomResourceDefinition

When you delete a CustomResourceDefinition, the server will uninstall the RESTful API endpoint and delete all custom objects stored in it.

```
$ k8s delete -f person-crd.yaml
$ k8s get persons 
# Error from server (NotFound): Unable to list "example.com/v1, Resource=persons": the server could not find the requested resource (get persons.example.com)

```