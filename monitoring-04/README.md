# Система сбора логов Elastic Stack

## Задание 1

Вам необходимо поднять в докере и связать между собой:

- elasticsearch (hot и warm ноды);
- logstash;
- kibana;
- filebeat.

Logstash следует сконфигурировать для приёма по tcp json-сообщений.
Filebeat следует сконфигурировать для отправки логов docker вашей системы в logstash.

### Ответ

![docker ps](https://github.com/loginochka/monitoring-systems/blob/main/monitoring-04/media/docker_ps.png)

![gui_kibana](https://github.com/loginochka/monitoring-systems/blob/main/monitoring-04/media/gui_kibana.png)

[docker-compose](https://github.com/loginochka/monitoring-systems/blob/main/monitoring-04/media/docker-compose.yml)

[logstash.conf](https://github.com/loginochka/monitoring-systems/blob/main/monitoring-04/media/logstash.conf)

[filebeat.yml](https://github.com/loginochka/monitoring-systems/blob/main/monitoring-04/media/filebeat.yml)
---

## Задание 2

Перейдите в меню создания index-patterns  в kibana и создайте несколько index-patterns из имеющихся.

Перейдите в меню просмотра логов в kibana (Discover) и самостоятельно изучите, как отображаются логи и как производить поиск по логам.

## Ответ

![logstash_index.png](https://github.com/loginochka/monitoring-systems/blob/main/monitoring-04/media/logstash_index.png)
