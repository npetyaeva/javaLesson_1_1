# Отчёт о тестировании функциональности Money Transfer

## Краткое описание

29.09.2021 - 29.09.2021 было проведено тестирование белого ящика функциональности Money Transfer.

На тестирование затрачено: 0.4

В результате тестирования выявлены следующие дефекты:
* [Issue](https://github.com/npetyaeva/javaLesson_1_1/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Тестовые данные
* Тестовый скрипт

В качестве тестовых данных использовались данные, [источник](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---money-transfer):
* текущий баланс счёта клиента - 2 000 000 000, int currentBalance = 2_000_000_000 
* сумма перевода - 500 000 000, int transferAmount = 500_000_000
* итоговое значение currentBalance + transferAmount, int finalValue = 2_500_000_000

Тестовый скрипт
```java
public class Main {
    public static void main(String[] args) {
        int currentBalance = 2_000_000_000;
        int transferAmount = 500_000_000;
        int finalValue = currentBalance + transferAmount;
        System.out.println(finalValue);
    }
}
```

Тестирование производилось в следующем окружении:
* Windows 7 Professional
* Java 11
* IntelliJ IDEA Community
