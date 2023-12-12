  1  microk8s status --wait-ready
    2  microk8s kubectl get nodes
    3  microk8s add-node
    4  microk8s kubectl get no
    5  clear
    6  microk8s status --wait-ready
    7  microk8s kubectl get nodes
    8  sudo snap install kubectl --classic
    9  ls
   10  cd ~
   11  ls
   12  ls -
   13  ls -a
   14  clear
   15  ls -a
   16  cd .kube/
   17  ls
   18  ls -a
   19  cd cache/
   20  ls
   21  clear
   22  cd ..
   23  cd ~
   24  ls
   25  ls -a
   26  clear
   27  cd .kube
   28  ls
   29  ls -a
   30  microk8s status
   31  microk8s kubectl get ns
   32  microk8s kubectl get kubeconfig
   33  ls
   34  ls -a
   35  ls /var/snap/microk8s/current/credentials/client.config
   36  cat /var/snap/microk8s/current/credentials/client.config
   37  cp /var/snap/microk8s/current/credentials/client.config .
   38  ls
   39  mv client.config kube.config
   40  ls
   41  kubectl get ns
   42  microk8s kubectl get ns
   43* ls     client-certificate-data: LS0tLS1CRUdJTiBDRVJUSUZJQ0FURS0tLS0tCk1JSUN6RENDQWJTZ0F3SUJBZ0lVY2tiSkttSFl0ZkxpcGpIYnZSL01CY2ZFcXBjd0RRWUpLb1pJaHZjTkFRRUwKQlFBd0Z6RVZNQk1HQTFVRUF3d01NVEF1TVRVeUxqRTRNeTR4TUI0WERUSXpNVEl3TmpFeE1UazFPRm9YRFRNegpNVEl3TXpFeE1UazFPRm93S1RFT01Bd0dBMVVFQXd3RllXUnRhVzR4RnpBVkJnTlZCQW9NRG5ONWMzUmxiVHB0CllYTjBaWEp6TUlJQklqQU5CZ2txaGtpRzl3MEJBUUVGQUFPQ0FROEFNSUlCQ2dLQ0FRRUF3ckNBNldPbmJVdC8KSE1LcmNycGtIVW5nL0NIalNaNGJ2TVFXM2ZHVmhYN0hZS2h2dUdGaldnUE90K1IxQlF6aXIvVC9yZEsrSFY1bAptbkpacDVoYjQ2eHFzTDI2MUlwZ3dVRE1rMCtxa05abitKYW5ITURybGFGRGhtc1VCU3kxd2svZ0RZQk0xbW9CCjd0NXVGcVpZNlFqblkyU0Ztc3BJVjY1YlZRZWpkTGVyMWtDTUdHckVRYU9HbXpiajIzTkllSFBtTVMwSEJ1ZXgKV1E4TnVIYXk3TC9GUDVqMnFja21WbFRmTVFqaWVhMEdZMHRobkJCNG56MW9LUnYyUUZrd3VNZWRTZ0xjKzNXcwovZVprZGdPKzlzeHJ4b1pEaTE1cnBUSEhtdTNyemZoY1QxWUJseWluMUFtSHB6RkI5RjNUelF1YW9ST3BkeFRoCjkrVlpPWmVoWlFJREFRQUJNQTBHQ1NxR1NJYjNEUUVCQ3dVQUE0SUJBUUFubHE3cFVqTkRVeFpPN3RJTDh0VzQKbE1RTUlNL3lWSWtNNUJBS2o0eXF2MGEzLzhjNUJjREFCdTZxdEdXdDBTazhmZjdNazZtVjRKTTRiSU1KRHBOMwpteDZ3WXQxVC9PejI4Z1F5YVNxYUtkTEhWN2xlbkwweDdKdnlZdDV1OENrUklQaGVVYzZaaE5oVGZyVjVTTkNWCnNuZDhsUWRLQk9PTkF4OG5sVGF4VkJVcjlpNktrMkN1ZGdrWWFZNnVQZERXb2p6L2RDSFZrV3RmVGhwb1NUNjgKbkZKaFgyb0tCQzRhY28vWjFsL3ozZGFHVFQxSEF4bjVQY2hFTklqbklUTGtRZFczNElUZlE2QmFubkNieEFzTwo1NmNrMjJVbmtmSHgxeXcyclc0c0ZyTFRZRVZFS0tGZDN1eSsrd292Wk1haXJvYW05T04yT2VidGk1dGN3aC9CCi0tLS0tRU5EIENFUlRJRklDQVRFLS0tLS0K
   44  ls /var/snap/microk8s/current/credentials/
   45  clear
   46  cd ~
   47  nano ~/.bash_aliases
   48  cat ~/.bash_aliases
   49  k8s
   50  k8s get ns
   51  nano ~/.bashrc
   52  cat ~/.bashrc
   53  source ~/.bashrc
   54  k8s get ns
   55  clear
   56  history



-----------------------------



 microk8s enable dns storage
    2  exit
    3  microk8s enable dns storage
    4  microk8s enable ingress dashboard
    5  microk8s kubectl apply -f https://raw.githubusercontent.com/metallb/metallb/v0.10.2/manifests/namespace.yaml
    6  clear
    7  sudo usermod -a -G microk8s $USER
    8  sudo chown -f -R $USER ~/.kube
    9  newgrp microk8s
   10  exit
   11  microk8s status --wait-ready
   12  microk8s kubectl get nodes
   13  microk8s add-node
   14  microk8s kubectl get no
   15  clear
   16  microk8s status --wait-ready
   17  microk8s kubectl get nodes
   18  sudo snap install kubectl --classic
   19  ls
   20  cd ~
   21  ls
   22  ls -
   23  ls -a
   24  clear
   25  ls -a
   26  cd .kube/
   27  ls
   28  ls -a
   29  cd cache/
   30  ls
   31  clear
   32  cd ..
   33  cd ~
   34  ls
   35  ls -a
   36  clear
   37  cd .kube
   38  ls
   39  ls -a
   40  microk8s status
   41  microk8s kubectl get ns
   42  microk8s kubectl get kubeconfig
   43  ls
   44  ls -a
   45  ls /var/snap/microk8s/current/credentials/client.config
   46  cat /var/snap/microk8s/current/credentials/client.config
   47  cp /var/snap/microk8s/current/credentials/client.config .
   48  ls
   49  mv client.config kube.config
   50  ls
   51  kubectl get ns
   52  microk8s kubectl get ns
   53  ls     client-certificate-data: LS0tLS1CRUdJTiBDRVJUSUZJQ0FURS0tLS0tCk1JSUN6RENDQWJTZ0F3SUJBZ0lVY2tiSkttSFl0ZkxpcGpIYnZSL01CY2ZFcXBjd0RRWUpLb1pJaHZjTkFRRUwKQlFBd0Z6RVZNQk1HQTFVRUF3d01NVEF1TVRVeUxqRTRNeTR4TUI0WERUSXpNVEl3TmpFeE1UazFPRm9YRFRNegpNVEl3TXpFeE1UazFPRm93S1RFT01Bd0dBMVVFQXd3RllXUnRhVzR4RnpBVkJnTlZCQW9NRG5ONWMzUmxiVHB0CllYTjBaWEp6TUlJQklqQU5CZ2txaGtpRzl3MEJBUUVGQUFPQ0FROEFNSUlCQ2dLQ0FRRUF3ckNBNldPbmJVdC8KSE1LcmNycGtIVW5nL0NIalNaNGJ2TVFXM2ZHVmhYN0hZS2h2dUdGaldnUE90K1IxQlF6aXIvVC9yZEsrSFY1bAptbkpacDVoYjQ2eHFzTDI2MUlwZ3dVRE1rMCtxa05abitKYW5ITURybGFGRGhtc1VCU3kxd2svZ0RZQk0xbW9CCjd0NXVGcVpZNlFqblkyU0Ztc3BJVjY1YlZRZWpkTGVyMWtDTUdHckVRYU9HbXpiajIzTkllSFBtTVMwSEJ1ZXgKV1E4TnVIYXk3TC9GUDVqMnFja21WbFRmTVFqaWVhMEdZMHRobkJCNG56MW9LUnYyUUZrd3VNZWRTZ0xjKzNXcwovZVprZGdPKzlzeHJ4b1pEaTE1cnBUSEhtdTNyemZoY1QxWUJseWluMUFtSHB6RkI5RjNUelF1YW9ST3BkeFRoCjkrVlpPWmVoWlFJREFRQUJNQTBHQ1NxR1NJYjNEUUVCQ3dVQUE0SUJBUUFubHE3cFVqTkRVeFpPN3RJTDh0VzQKbE1RTUlNL3lWSWtNNUJBS2o0eXF2MGEzLzhjNUJjREFCdTZxdEdXdDBTazhmZjdNazZtVjRKTTRiSU1KRHBOMwpteDZ3WXQxVC9PejI4Z1F5YVNxYUtkTEhWN2xlbkwweDdKdnlZdDV1OENrUklQaGVVYzZaaE5oVGZyVjVTTkNWCnNuZDhsUWRLQk9PTkF4OG5sVGF4VkJVcjlpNktrMkN1ZGdrWWFZNnVQZERXb2p6L2RDSFZrV3RmVGhwb1NUNjgKbkZKaFgyb0tCQzRhY28vWjFsL3ozZGFHVFQxSEF4bjVQY2hFTklqbklUTGtRZFczNElUZlE2QmFubkNieEFzTwo1NmNrMjJVbmtmSHgxeXcyclc0c0ZyTFRZRVZFS0tGZDN1eSsrd292Wk1haXJvYW05T04yT2VidGk1dGN3aC9CCi0tLS0tRU5EIENFUlRJRklDQVRFLS0tLS0K
   54  ls /var/snap/microk8s/current/credentials/
   55  clear
   56  cd ~
   57  nano ~/.bash_aliases
   58  cat ~/.bash_aliases
   59  k8s
   60  k8s get ns
   61  nano ~/.bashrc
   62  cat ~/.bashrc
   63  source ~/.bashrc
   64  k8s get ns
   65  clear
   66  history
   67  sudo usermod -a -G microk8s $USER
   68  sudo chown -f -R $USER ~/.kube
   69  newgrp microk8s
   70  exit
   71  sudo apt update
   72  sudo apt install git
   73  git --version
   74  git init
   75  git clone
   76  git clone https://github.com/vijaynvb/todoapi.git
   77  sudo apt install docker.io
   78  docker --version
   79  docker login
   80  docker ingo
   81  docker info
   82  docker ps
   83  ls
   84  cd todoapi/
   85  ls
   86  cat Dockerfile
   87  docker build -t todoapi:1.0 .
   88  docker images
   89  docker tag todoapi:1.0 swayaanthanu/todoapi:1.0
   90  docker images
   91  docker push swayaanthanu/todoapi:1.0
   92  clear
   93  cd ~
   94  ls
   95  clear
   96  sudo snap install microk8s --classic --channel=latest/stable
   97  sudo usermod -a -G microk8s $USER
   98  sudo chown -f -R $USER ~/.kube
   99  ls
  100  su - $USER
  101  exit
  102  clear
  103  microk8s status
  104  microk8s enable ingress dashboard
  105  microk8s kubectl apply -f https://raw.githubusercontent.com/metallb/metallb/v0.10.2/manifests/namespace.yaml
  106  microk8s kubectl apply -f https://raw.githubusercontent.com/metallb/metallb/v0.10.2/manifests/metallb.yaml
  107  nano metallb-config.yaml
  108  kubectl apply -f metallb-config.yaml
  109  k8s apply -f metallb-config.yaml
  110  nano metallb-config.yaml
  111  k8s apply -f metallb-config.yaml
  112  microk8s enable community
  113  microk8s enable istio
  114  microk8s istioctl version
  115  k8s ns
  116  k8s ge ns
  117  k8s get ns
  118  k8s get pods -n istio-system
  119  k8s get svc -n istio-system
  120  git clone https://github.com/istio/istio.git
  121  microk8s kubectl get ns default --show-labels
  122  microk8s kubectl label namespace default istio-injection=enabled
  123  microk8s kubectl get ns default --show-labels
  124  cd istio
  125  microk8s kubectl apply -f <(microk8s istioctl kube-inject -f ./samples/bookinfo/platform/kube/bookinfo.yaml)
  126  microk8s kubectl get all
  127  clear
  128  microk8s kubectl get all
  129  k8s describe pod/productpage-v1-5858859db8-q4gln
  130  microk8s kubectl exec "$(microk8s kubectl get pod -l app=ratings -o jsonpath='{.items[0].metadata.name}')" -c ratings -- curl -sS productpage:9080/productpage | grep -o "<title>.*</title>"
  131  microk8s kubectl apply -f ./samples/bookinfo/networking/bookinfo-gateway.yaml
  132  microk8s kubectl get gateway
  133  export INGRESS_NAME=istio-ingressgateway
  134  export INGRESS_NS=istio-system
  135  export INGRESS_HOST=$(microk8s kubectl -n "$INGRESS_NS" get service "$INGRESS_NAME" -o jsonpath='{.status.loadBalancer.ingress[0].ip}')
  136  export INGRESS_PORT=$(microk8s kubectl -n "$INGRESS_NS" get service "$INGRESS_NAME" -o jsonpath='{.spec.ports[?(@.name=="http2")].port}')
  137  export SECURE_INGRESS_PORT=$(microk8s kubectl -n "$INGRESS_NS" get service "$INGRESS_NAME" -o jsonpath='{.spec.ports[?(@.name=="https")].port}')
  138  export TCP_INGRESS_PORT=$(microk8s kubectl -n "$INGRESS_NS" get service "$INGRESS_NAME" -o jsonpath='{.spec.ports[?(@.name=="tcp")].port}')
  139  export GATEWAY_URL=$INGRESS_HOST:$INGRESS_PORT
  140  curl -s "http://${GATEWAY_URL}/productpage" | grep -o "<title>.*</title>"
  141  echo $GATEWAY_URL
  142  microk8s kubectl get svc -n istio-system
  143  curl http://172.18.255.200/productpage
  144  microk8s enable host-access
  145  microk8s kubectl get svc -n istio-system
  146  ping 10.152.183.90
  147  curl http://10.152.183.90/productpage
  148  microk8s kubectl get svc -n istio-system
  149  cd samples/addons/
  150  ls
  151  k8s apply -f kiali.yaml
  152  cd ../..
  153  microk8s kubectl get svc -n istio-system
  154  k8s port-forward -n istio-system svc/kiali 20001:20001
  155  cd samples/addons/
  156  ls
  157*
  158  clear
  159  microk8s kubectl get svc -n istio-system
  160  k8s edit svc kiali -n istio-system
  161  microk8s kubectl get svc -n istio-system
  162  ls
  163  microk8s kubectl apply -f prometheus.yaml
  164  microk8s kubectl get svc -n istio-system
  165  k8s edit svc prometheus.yaml -n istio-system
  166  k8s edit svc prometheus -n istio-system
  167  microk8s kubectl get svc -n istio-system
  168  history
