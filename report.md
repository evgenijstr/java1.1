# Отчет о тестировании приложения Credit card number validator

## Краткое описание

11.08.2021 было проведено функциональное тестирование методом белого ящика приложения Credit card number validator

На тестирование затрачено: 30 минут

В результате тестирования выявлены следующие дефекты:
* [Не подтверждается номер карты Diners Club - Carte Blanche при исполнении кода](https://github.com/evgenijstr/java1.1/issues/1)
* [Не подтверждается номер карты Diners Club - International при исполнении кода](https://github.com/evgenijstr/java1.1/issues/2)
* [Не подтверждается номер карты American Express - International при исполнении кода](https://github.com/evgenijstr/java1.1/issues/3)
## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* [тест-кейсы](https://docs.google.com/spreadsheets/d/1yH0gnMRXJ8pJkwGYZE4G_CqH1vSEcHig4TByoynG8qE/edit?usp=sharing)
* [баг-репорт](https://docs.google.com/spreadsheets/d/1j5LxrG4NAKZJiOExP3OG6t4sA34wafAXC9w82VY3o4Q/edit?usp=sharing)

В качестве тестовых данных использовались [данные](https://www.freeformatter.com/credit-card-number-generator-validator.html)

* VISA: 4485404173260688
* Discover: 6011000143519134
* Visa Electron: 4913646505126050
* MasterCard: 5373022351701141
* JCB: 3535446268209361
* Diners Club - North America: 5538427454685848
* Maestro: 5893779946479613
* Diners Club - Carte Blanche: 30089796236385
* Diners Club - International: 36591308396304
* American Express: 342912837761215

Тестирование проводилось в следующем окружении
* Ubuntu 20.04.2 LTS, 64 bit
* Java 11.0.11
* IntelliJ IDEA 2021.2 (Community Edition) Build #IC-212.4746.92
