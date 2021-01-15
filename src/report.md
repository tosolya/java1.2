#Отчёт о тестировании Credit Card Number Validator

##Краткое описание

14.01.2021 - 14.01.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
 * https://github.com/tosolya/java1.2/issues/1
 * https://github.com/tosolya/java1.2/issues/2

##Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

 * Баг-репорт
 * Отчет о тестировании

В качестве тестовых данных использовались данные с сайта: https://www.freeformatter.com/credit-card-number-generator-validator.html:

 * 5351719427810741 Result is OK
 * 2720995574521684 Result is OK
 * 4916447409129713 Result is OK
 * 4945219561866315898 Result is FAIL
 * 30046047626012 Result is FAIL
 * 5893820104764055 Result is OK
 
 * ничего не вводили Result is FAIL
 * -1 Result is FAIL
 * 2 пробела Result is FAIL
 * hhh Result is FAIL
 * 000000000000000 Result is FAIL
 * 589382010476405558938201047640555893820104764055 Result is FAIL
 * !!!!!!! Result is FAIL

Тестирование производилось в следующем окружении:
 * macOS Catalina v 10.15.7,
 * Java11