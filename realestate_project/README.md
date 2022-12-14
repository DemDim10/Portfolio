# Проект - Анализ объявлений о продаже недвижимости в Санкт-Петербурге и ЛО

## Описание и цели
Чтобы научиться определять рыночную стоимость объектов недвижимости, нужно установить параметры этой стоимости, что позволит в дальнейшем построить автоматизированную систему, которая будет отслеживать аномалии и мошенническую деятельность.

## Данные
Архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет, предоставленные сервисом Яндекс.Недвижимость. 

## Задачи
- Изучить данные
- Провести предобработку данных
- Добавить в таблицу новые параметры:
    - цену квадратного метра; этаж
    - день недели, месяц и год публикации
    - соотношение жилой, общей и площади кухни
- Изучить параметры и построить по ним графики
- Удалить аномалии
- Изучить, какие факторы больше всего влияют на стоимость квартиры
- Выделить сегмент квартир в цене
- Написать общий вывод

## Полученные выводы
Ислледование показало, что на на повышение стоимости квартиры влияют: площадь квартиры, цена за квадратный метр, доля жилой площади и кухни, удалённость от центра (чем ближе - тем дороже). Самые дорогие квартиры находятся не на первом и не не последнем этаже. На первом всегда дешевле, чем на последнем. Дорогие объявления выкладывались в 2017 году.

## Используемые инструменты
*python*, *pandas*, *markdown*, *matplotlib*

## Ключевые слова
обработка данных, histogram, boxplot, scattermatrix,
категоризация, scatterplot,  фрод-мониторинг
