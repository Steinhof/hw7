Подготовка:
1. minikube start
2. minikube addons enable ingress
3. kubectl apply -f ./namespaces.yaml
4. kubectl apply -f ./deploy

Запустить тесты postman.json

Для реализации идемпотентности использовался паттерн idempotency key