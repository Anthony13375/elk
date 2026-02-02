# Домашнее задание к занятию "`ELK`" - `Герасимов Антон`

### Задание 1. Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.*

#### Ответ к заданию 1


![elastic](https://github.com/Anthony13375/elk/blob/main/img/1.jpg)


---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.*

#### Ответ к заданию 2

![kibana](https://github.com/Anthony13375/elk/blob/main/img/2.jpg)

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

#### Ответ к заданию 3

![logstash](https://github.com/Anthony13375/elk/blob/main/img/3.jpg)

---

### Задание 4. Filebeat

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

#### Ответ к заданию 4

![filebeat](https://github.com/Anthony13375/elk/blob/main/img/4.jpg)
