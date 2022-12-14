# Принятие решений в бизнессе
## Данные
Проект состоит из двух частей.
### Данные для первой части:
- краткое описание гипотезы
- охват пользователей по 10-балльной шкале
- влияние на пользователей по 10-балльной шкале
- уверенность в гипотезе по 10-балльной шкале
- затраты ресурсов на проверку гипотезы по 10-балльной шкале
### Данные для второй части:
- идентификатор заказа
- идентификатор пользователя, совершившего заказ
- дата, когда был совершён заказ
- выручка заказа
- группа A/B-теста, в которую попал заказ
- количество пользователей в указанную дату в указанной группе A/B-теста
## Задача
Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами
## Описание
Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста.
## Используемые навыки и инструменты
*Python*, *Pandas*, *Matplotlib*, *SciPy*, *A/B-тестирование*, *проверка статистических гипотез*
