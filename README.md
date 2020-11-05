# Отчёт о тестировании программы Credit Card Number Validator.

04.11.2020 было проведено исследовательское тестирование программы Credit Card Number Validator.

На тестирование затрачено: 2 часа.

В результате тестирования выявлены следующие дефекты:
* [Ошибка при валидации карт Dinners club](https://github.com/urop9xa/credit-card-validator/issues/3)
* [Ошибка при валидации карт American express и Voyager.](https://github.com/urop9xa/credit-card-validator/issues/2)
* [Ошибка при валидации карт Visa](https://github.com/urop9xa/credit-card-validator/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* сайт генерации номеров кредитных карт [https://www.prepostseo.com](https://www.prepostseo.com/tool/ru/credit-card-generator)
* сайт генерации номеров кредитных карт [https://www.getcreditcardnumbers.com](https://www.getcreditcardnumbers.com/generated-credit-card-numbers)
В качестве тестовых данных использовались данные c сайта генерации [https://www.prepostseo.com](https://www.prepostseo.com/tool/ru/credit-card-generator):
[https://www.getcreditcardnumbers.com](https://www.getcreditcardnumbers.com/generated-credit-card-numbers)

Валидные данные карт :
5487530668884668
5164906885093251
Невалидные данные карт :
4916945479106
4929444620054
4916378388527
348372627887601
344000700575322
869966682271970
869935753669826
30340656280330
38365484551224
38510957519162
30214542721312
Тестирование производилось в окружении:
* Windows 10 Home 64 bit
* Java version 11
