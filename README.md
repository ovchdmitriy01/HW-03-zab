# Домашнее задание к занятию «Система мониторинга Zabbix. Часть 2»


### Задание 1
Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон
3. Создайте Item который будет собирать информацию об загрузке CPU в процентах
4. Создайте Item который будет собирать информацию об загрузке RAM в процентах

![alt text](https://github.com/ovchdmitriy01/HW-03-zab/blob/main/zab_2_2.png)
![alt text](https://github.com/ovchdmitriy01/HW-03-zab/blob/main/zab_2_3.png)



 ---

### Задание 2-3
Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.

![alt text](https://github.com/ovchdmitriy01/HW-03-zab/blob/main/zab_2_4.png)
![alt text](https://github.com/ovchdmitriy01/HW-03-zab/blob/main/zab_2_5.png)
![alt text](https://github.com/ovchdmitriy01/HW-03-zab/blob/main/zab_2_6.png)
![alt text](https://github.com/ovchdmitriy01/HW-03-zab/blob/main/zab_2_7.png)

Zabbix не дает установить шаблон Linux by Zabbix Agent одновременно с новыми заданными шаблонами, т.к. в нем также присутствует item на CPU и RAM

![alt text](https://github.com/ovchdmitriy01/HW-03-zab/blob/main/zab_2_8.png)


 ---

### Задание 4
Создайте свой кастомный дашборд.

![alt text](https://github.com/ovchdmitriy01/HW-03-zab/blob/main/zab_2_9.png)

 ---
