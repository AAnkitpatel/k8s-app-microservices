# deploy you application as multiple microservice on kubernetes
## please update your docker image registory username password in k8s-pre-setup.yaml
### using this "kubectl create secret docker-registry regcred --docker-server=<your-registry-server> --docker-username=<your-name> --docker-password=<your-pword> --docker-email=<your-email> --output=yaml"
## update your ssl certs in k8s-pre-setup.yaml and upload dns in all ingress
### using this cmd "kubectl create secret tls my-tls-secret --key < private key filename> --cert < certificate filename> --output=yaml"
### update your latest images accordingly # k8s-app-microservices
