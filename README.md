# OTUS
ДЗ №1 по курсу "Observability: мониторинг, логирование, трейсинг"

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
5. Оповещения для отправки в Telegram алертов настроены с помощью специального бота Telepush:
![image](https://user-images.githubusercontent.com/71332690/215460167-450d4794-f022-452d-9a75-54aeec4eb865.png)


ДЗ №2 по курсу "Grafana - продвинутое использование"

Ход работ:
1. Установлена Grafana версии 9.3.6.
2. Внутри Grafana созданы папки App и Infra.
3. В папку Infra импортирован Dashboard "Node Exporter Full".
4. В папке App создан дашборд "Zabbix" для мониторинга параметров Zabbix.
5. Скриншоты дашбордов находятся в папке GAP2

