# Домашнее задание к занятию "15.Система сбора логов Elastic Stack" - `Чернышов Андрей`

### Задание 1.  

Docker ps  .  
![1](https://github.com/ANDREYTOLOGY/terraform-hw/blob/main/img/kibana-1.png)     

Cкриншот веб-интерфейса kibana  
![2](https://github.com/ANDREYTOLOGY/terraform-hw/blob/main/img/kibana-2.png)  


### Задание 2.  
В Kibana были созданы несколько Data View (index-patterns):  
- logstash-* — для всех логов  
- logstash-2026.04.29 — для конкретного индекса  
![3](https://github.com/ANDREYTOLOGY/terraform-hw/blob/main/img/kibana-3.png)  

В разделе Discover были проанализированы поступающие логи c ошибками.  
![4](https://github.com/ANDREYTOLOGY/terraform-hw/blob/main/img/kibana-4.png)  
Логи поступают от Filebeat через Logstash в Elasticsearch и отображаются в Kibana.  

Были выполнены:
- фильтрация по полям 
- поиск по ключевым словам
- изменение временного диапазона  

Также подтверждено наличие индекса logstash-*, который формируется Logstash на основе поступающих данных.  


