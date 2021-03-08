# **Отчёт о тестировании приложения Credit Card Number Validator**

## **Краткое описание**
06 марта 2021 было проведено функциональное тестирование приложения Credit Card Number Validator при помощи положительного метода на основе TODO, закреплённом в коде Credit Card Number Validator.

## **На тестирование затрачено**: 01 час

## **В результате тестирования выявлены следующие дефекты**:

* [Валидный номер карты VISA длиной 19 знаков определяется как невалидный в приложении Credit Card Number Validator](https://github.com/maxim-valov/Credit-Card-Number-Validator/issues/1)
* [Валидные номера карт American Express (AMEX) длинной 15 символов определяются как невалидные в приложении Credit Card Number Validator](https://github.com/maxim-valov/Credit-Card-Number-Validator/issues/2)

## **Описание процесса тестирования**

**В процессе тестирования использовались следующие артефакты**:

Тестированииe проводилось на осове требований к [Задаче 2](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0-1) из Домашнего задания к занатию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»


**В качестве тестовых данных использовались данные**:

* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md) с ожидаемым результатом: Intellij IDEA устанавливается на ОС Windows 10 64x, и работает с java кодом
* [JAVA Код для Credit Card Number Validator](https://github.com/maxim-valov/Credit-Card-Number-Validator/blob/master/CodeValidator.md)  c ожидаемым результатом: Заявленный в TODO функционал, позволяет определять валидость или невалидность номеров банковских карт.
* [База тестовых валидных номеров карт](https://github.com/maxim-valov/Credit-Card-Number-Validator/blob/master/CreditCardNumbers.md) c ожидаемым результатом: валидныым номерам присваивается значение ОК, невалидным - значение FAIL.


**Тестирование производилось в следующем окружении**:

* Windows 10x
* OpenJDK 11.0.10+9
* IntelliJ IDEA