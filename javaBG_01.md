# Отчёт о тестировании Money Transfer

## Краткое описание

29.09.2021 - 29.09.2021 было проведено Функциональное тестирование приложения интернет-банкинга.

На тестирование затрачено: 0.4

В результате тестирования выявлены следующие дефекты:
* [https://github.com/npetyaeva/javaLesson_1_1/issues/1](https://github.com/npetyaeva/javaLesson_1_1/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Тестовые данные
* Тестовый скрипт

В качестве тестовых данных использовались данные, [источник](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---money-transfer):
* текущий баланс счёта клиента - 2 000 000 000, int currentBalance = 2000000000 
* сумма перевода - 500 000 000, int transferAmount = 500000000
* итоговое значение currentBalance + transferAmount, int finalValue = 2500000000

Тестирование производилось в следующем окружении:
* Windows 7 Professional
* Java 11
