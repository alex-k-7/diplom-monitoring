## Конфигурация системы мониторинга кластера Kubernetes.
Манифесты Kubernetes для деплоя системы мониторинга были сгенерированы с помощью библиотеки [kube-prometheus](https://github.com/prometheus-operator/kube-prometheus). Для доступа к интерфейсу Grafana через интернет был изменен тип сервиса на NоdePort ([example.jsonnet](example.jsonnet)) и создан дополнительный обработчик для балансировщика в Yandex Cloud.

[Интерфейс Grafana](http://51.250.27.127:8080/dashboards/f/QHOL0v6nz/default) (netology/1@3qweASD).