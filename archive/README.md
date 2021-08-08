# trade-cube

## Install

MySQL by HELM
`helm install trade-mysql7 bitnami/mysql -f mysql.yaml`

ConfigMap
`kubectl apply -f configmap.yaml`

Secret
`kubectl apply -f secret.yaml`

Job initDB
`kubectl apply -f initdb.yaml`

App
`kubectl apply -f deployment.yaml`

Service NodePort for app
`kubectl apply -f service.yaml`

Ingress
`kubectl apply -f ingress.yaml`

## Checkout
(http://arch.homework/health)

## Postman collection
trade.postman_collection.json
(https://github.com/orensimple/trade-cube/blob/main/trade.postman_collection.json)


## About
Docker образ приложения
(https://hub.docker.com/repository/docker/orensimple/trade-core-app)

Исходный код приложения
(https://github.com/orensimple/trade-core-app)

Описание приложения и схемы данных
(https://github.com/orensimple/trade-db)
