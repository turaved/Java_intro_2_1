# Отчёт о тестировании приложения **Money Transfer**

## Краткое описание

Было создано базовое приложение, в котором суммируются переменные типа int "Балланс текущего счета" (CurrentBalance) и "Новое поступление"(NewTransfer) с сохранением результата в переменную типа int "Итоговый балланс"(TotalBalance).


## Описание тестов

13.11.2020 было проведено функциональное тестирование приложения. 

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты: 
* [Превышение значения переменной типа int "TotalBalance"](https://github.com/turaved/Java_intro_2_1/issues/1)

### Этапы тестирования
* создать программу **Money Transfer** в среде разработки **IntelliJ IDEA** согласно [Задания №1](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)
* провести компиляцию и запустить программу

**Ожидаемый результат**
TotalBalance = 2500 000 000  - значение итогового балланса.

**Фактический результат**
TotalBalance =-1794967296


**Тестирование производилось в следующем окружении:**
* Windows 10, 64-разрядная операционная система
* версия JDK "11.0.9" 2020-10-20
* Google Chrom Версия 86.0.4240.193 (Официальная сборка), (64 бит)
