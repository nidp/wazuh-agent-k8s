# wazuh-agent-k8s

docker build -t nidp/wazuh-agent

docker push nidp/wazuh-agent

kubectl create -f wazuh-agent-dep.yaml
