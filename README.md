# trade-cube

## Install

MySQL by HELM
`helm install trade-mysql7 bitnami/mysql -f mysql.yaml`

Trade App
`helm install trade-app ./trade-chart`


## Checkout
(http://arch.homework/health)

## Postman Test Auth collection

`newman run trade-core-auth-test.postman_collection)`

trade.postman_collection.json
(https://github.com/orensimple/trade-cube/blob/main/trade-core-auth-test.postman_collection)

## Postman collection
trade.postman_collection.json
(https://github.com/orensimple/trade-cube/blob/main/trade.postman_collection.json)

## Load test
`wrk -t2 -c100 -d600s -s random_search.lua http://arch.homework`

random_search.lua
(https://github.com/orensimple/trade-cube/blob/main/random_search.lua)

result screnshot
(https://github.com/orensimple/trade-cube/blob/main/load-test-screen)

## Grafana dashboard
dashboard_app.json
(https://github.com/orensimple/trade-cube/blob/main/dashboard_app.json)


## About
Docker образ приложения
(https://hub.docker.com/repository/docker/orensimple/trade-core-app)

Исходный код приложения
(https://github.com/orensimple/trade-core-app)

Описание приложения и схемы данных
(https://github.com/orensimple/trade-db)
