# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

14.02.2026 было проведено функциональное тестирование приложения Credit Card Number Validator. 
На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* [#1](https://github.com/Rromario/HomeworkJava1/issues/1)
* [#2](https://github.com/Rromario/HomeworkJava1/issues/2)
* [#3](https://github.com/Rromario/HomeworkJava1/issues/3)
* [#4](https://github.com/Rromario/HomeworkJava1/issues/4)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Тест-план](https://github.com/Rromario/HomeworkJava1/tree/master/src) 

В качестве тестовых данных использовались данные [сайт freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* Валидные номера банковских карт:
  * 16 цифр: 2200020241578697
  * 17 цифр: 45323103082451542
  * 18 цифр: 453231030824515424
  * 19 цифр: 4532310308245154245

* Невалидные номера банковских карт:
  * 0
  * abcdefg
  * )&*%$#
  * 12
  * 123
  * 1234
  * 12345
  * 123456
  * 1234567
  * 12345678
  * 123456789
  * abcdefgetreytr16
  * 16abcdefgetrey16
  * SELECT * FROM users WHERE username = 'admin' --'
Тестирование производилось в следующем окружении:
* Windows 11 Pro, 64-разрядная
* Java 11
