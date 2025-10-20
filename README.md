# Домашнее задание к занятию "ELK" - `Волкивский Андрей`

### Задание 1  Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

### Решение 1

<img width="1605" height="945" alt="image" src="https://github.com/user-attachments/assets/3ce06f7f-d47a-4925-a30c-0a90ff83b46f" />

<img width="1031" height="594" alt="image" src="https://github.com/user-attachments/assets/57c8289f-37fc-4c64-8dde-ec272c17ac22" />

### Задание 2 Kibana

Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

### Решение 2

<img width="1900" height="1042" alt="image" src="https://github.com/user-attachments/assets/d42105e6-251e-4518-a47b-efa00097e01f" />

### Задание 3

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

### Решение 3

<img width="1756" height="844" alt="image" src="https://github.com/user-attachments/assets/e2ce950f-6106-4486-a258-f3b21ac1fcbf" />

<img width="1571" height="592" alt="image" src="https://github.com/user-attachments/assets/f567e725-9680-49b0-9479-56d2c7ce855b" />

<img width="1718" height="1010" alt="image" src="https://github.com/user-attachments/assets/5634c114-5b7b-4add-ac95-bc59c25a73f6" />

### Задание 4

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

### Решение 4



