## Конфигурация системы мониторинга кластера Kubernetes.
Деплой системы мониторинга был осуществлен с помощью пакета [kube-prometheus](https://github.com/prometheus-operator/kube-prometheus). Для доступа к интерфейсу Grafana через интернет был изменен тип сервиса на NоdePort и создан дополнительный обработчик для балансировщика в Yandex Cloud.

Интерфейс Grafana - [http://51.250.27.127:8080](http://51.250.27.127:8080) (netology/1@3qweASD).