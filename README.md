# Домашнее задание к занятию "`Cluster_homework`" - `Gurylev A.V.`

# Задание 1



Запустите два simple python сервера на своей виртуальной машине на разных портах
![alt text](https://github.com/A1ex93/cluster_homework/blob/main/image/1.png)

Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
![alt text](https://github.com/A1ex93/cluster_homework/blob/main/image/2.png)

Настройте балансировку Round-robin на 4 уровне.

![alt text](https://github.com/A1ex93/cluster_homework/blob/main/image/3.png)
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.


# Задание 2



Запустите три simple python сервера на своей виртуальной машине на разных портах
![alt text](https://github.com/A1ex93/cluster_homework/blob/main/image/2.1.png)

Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4

![alt text](https://github.com/A1ex93/cluster_homework/blob/main/image/2.2.png)
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local

![alt text](https://github.com/A1ex93/cluster_homework/blob/main/image/2.3.png)
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.
