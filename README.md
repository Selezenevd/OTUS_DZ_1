# OTUS_DZ_1
Репозиторий для ДЗ №1 по курсу "Observability: мониторинг, логирование, трейсинг"

Ход работ:
1. Развернуты 2 хоста: ubuntu-srv (192.168.100.164), ubuntu-srv-2 (192.168.100.161).
2. На хосте ubuntu-srv (192.168.100.164) установлены zabbix, nginx, php7.4-fpm, postgresql:
![image](https://user-images.githubusercontent.com/71332690/215459055-c9c70310-438e-4615-b263-0d1a9d974ec5.png)
3. Также на хосте ubuntu-srv (192.168.100.164) установлены экспортеры: 
 - nginx-exporter
 - node-exporter
 - php-fpm-exporter
 - postgres_exporter
 - blackbox-exporter
4. На ubuntu-srv-2 (192.168.100.161) установлены Prometheus и Alertmanager, отредактированы конфигурационные файлы:
![image](https://user-images.githubusercontent.com/71332690/215459612-a60f8206-9474-41c3-b64b-63bb4d53f484.png)

