# kubernetesRepo

This is a repo for several kubernetes deployments

## Ignite

This is a ignite deployment on kubernetes using configmap to store example-kube.xml

### To deploy

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Ignite/ignite-service.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Ignite/ignite-configmap.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Ignite/ignite-rbac.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Ignite/ignite-deployment.yaml

## Kafka

This is kafka deployment and it is derived from https://github.com/Yolean/kubernetes-kafka. It will be customized, though...

### To deploy

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Kafka/kafka-storage.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Kafka/kafka-namespace.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Kafka/kafka-rbac.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Kafka/zookeeper-configmap.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Kafka/zookeeper-service.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Kafka/zookeeper-deployment.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Kafka/kafka-configmap.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Kafka/kafka-service.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Kafka/kafka-deployment.yaml

