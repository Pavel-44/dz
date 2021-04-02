# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

02.04.21 - 02.04.21 было проведено модульное позитивное и негативное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 30 минут

В результате тестирования выявлены следующие дефекты:
* [Не работает валидация банковских карт из 19 цифр](https://github.com/Pavel-44/dz/issues/1#issue-849496444)
* [Не работает валидация банковских карт из 14 цифр](https://github.com/Pavel-44/dz/issues/2#issue-849498830)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Сервис по генерированию валидных номеров карт - [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)
* [Тест-план](Test.md)

В качестве тестовых данных использовались данные cервиса по генерированию валидных номеров карт [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html).

Тестирование производилось в следующем окружении:
* macOS 10.13.6 High Siera
* Java version "11.0.10" 2021-01-19
