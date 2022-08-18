# wazuh-agent-k8s

## Build Docker image, if modified

$ docker build -t nidp/wazuh-agent .

## push 
$ docker push nidp/wazuh-agent


## create k8s resources
kubectl create -f wazuh-agent-dep.yaml
