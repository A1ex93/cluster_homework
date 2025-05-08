# Домашнее задание к занятию "`Cluster_homework`" - `Gurylev A.V.`

# Задание 1



Запустите два simple python сервера на своей виртуальной машине на разных портах
![alt text](https://github.com/A1ex93/cluster_homework/blob/main/image/f1.png)

Настройте балансировку Round-robin на 4 уровне.

![alt text](https://github.com/A1ex93/cluster_homework/blob/main/image/f2.png)
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

Файл с конфингом HAProxy для первого задания:

[Конфиг первого задания](https://github.com/A1ex93/cluster_homework/blob/main/task1_haproxy.cfg)


# Задание 2

Запустите три simple python сервера на своей виртуальной машине на разных портах
![alt text](https://github.com/A1ex93/cluster_homework/blob/main/image/f2_1.png)

Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4

HAproxy должен балансировать только тот http-трафик, который адресован домену example.local

На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.
![alt text](https://github.com/A1ex93/cluster_homework/blob/main/image/f2_2.png)

Файл с конфингом HAProxy для первого задания:

[Конфиг второго задания](https://github.com/A1ex93/cluster_homework/blob/main/task2_haproxy.cfg)
