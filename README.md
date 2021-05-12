# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

12/05/2021 - 12/05/2021 было проведено смоук-тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час 

В результате тестирования выявлены следующие дефекты:

* [В Credit Card Number Validator отклоняются 15-значные номера карт Voyager](https://github.com/ElenaVedernikova/Project_J_1_1/issues/1)
* [В Credit Card Number Validator отклоняются 14-значные номера карт Diners Club](https://github.com/ElenaVedernikova/Project_J_1_1/issues/2)
* [В Credit Card Number Validator отклоняются 13-значные номера карт Visa 13 digit ](https://github.com/ElenaVedernikova/Project_J_1_1/issues/3)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Генератор номеров кредитных карт](https://www.getcreditcardnumbers.com/)

В качестве тестовых данных использовались данные:
* 16-значные номера карт Visa, MasterCard, Discover
* 15-значные номера карт Voyager
* 14-значные номера карт Diners Club
* 13-значные номера карт Visa 13 digit


Тестирование производилось в следующем окружении:
* Win 10 Pro 10.0.19042 Сборка 19042 64-bit, 
* Java 11.0.10
* IntelliJ IDEA 2021.1.1