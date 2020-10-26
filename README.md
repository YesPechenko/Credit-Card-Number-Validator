# Отчёт о тестировании <Credit Card Number Validator>

## Проверить работу программы Credit Card Number Validator, которая помогает осуществлять приём платежей с банковских карт различным организациям

24.10.2020г. - 24.10.2020г. было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

* [программа Credit Card Number Validator не осуществляет приём платежей](https://github.com/YesPechenko/Credit-Card-Number-Validator/issues/1#issue-728789540)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

[Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)


В качестве тестовых данных использовались данные 
[Fake credit card numbers for all major brands](https://www.freeformatter.com/credit-card-number-generator-validator.html)

VISA:

* 4532716681438826
	
* 4024007146149611

* 4485188817166844738 

Discover:

* 6011448974271996

* 6011472115765294

* 6011806486227209648 

MasterCard:

* 2221002816999192

* 2720998600580369

* 5456363851210054

Тестирование производилось в следующем окружении:
* Windows 10, 64-битная версия
* Java version "11.0.9"