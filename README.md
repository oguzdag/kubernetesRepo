# kubernetesRepo

This is a repo for several kubernetes deployments

## Ignite

This is a ignite deployment on kubernetes using configmap to store example-kube.xml

### To deploy

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Ignite/ignite-service.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Ignite/ignite-configmap.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Ignite/ignite-rbac.yaml

kubectl create -f https://raw.githubusercontent.com/oguzdag/kubernetesRepo/master/Ignite/ignite-deployment.yaml