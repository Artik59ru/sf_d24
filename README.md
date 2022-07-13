# sf_d24
```sh
minikube start --nodes 5 > minikube.log && minikube status >> minikube.log
```
Почему Kind говорит, что это изменение его не затронет?
 - Формат контейнеров не поменялся, поэтому проблем не будет. Изменения затрагивают только способ запуска контейнеров внутри кластера k8s.
ссылка на источник: https://mcs.mail.ru/blog/kubernetes-otkazyvaetsya-ot-docker

