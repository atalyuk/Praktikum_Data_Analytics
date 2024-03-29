# Проверка гипотез по увеличению выручки в интернет-магазине — оценка результаты A/B теста

Используемые библиотеки Python - pandas, datetime, matplotlib.pyplot, numpy, scipy.

`Задача`: на основе данных о покупках пользователей в интернет-магазине провести анализ результатов A/B теста и сделать выводы об эффективности внедрённых изменений в сайте интернет-магазина.

В ходе анализа с помощью фреймворков IСE и RICE определена самая приоритетная гипотеза ("добавить форму подписки на все основные страницы"). 

Подсчитана кумулятивная выручка и средний чек каждой из групп в течение контрольного периода времени, построены соответствующие визуализации. Аналогичным образом исследовано изменение кумулятивной конверсии по группам.

При помощи анализа распределения количества и стоимости заказов определены границы "нормального" поведения пользователей, аномалии исключены. 

Проведен статистический анализ разницы поведения групп по признакам конверсии и  среднего чека

`Выводы`: 
- различия в конверсии групп статистически значима. Разница составляет в среднем 13,8 % на сырых данных и 17.3 % на очищенных данных в пользу группы B
- средний чек группы B превосходит аналогичный показатель группы A, однако это было достигнуто в связи с малым количеством аномально дорогих заказов. Применение критерия Манна-Уитни показывает, что статистически значимой разницы в среднем чеке нет ни на сырых, ни на очищенных данных.
- по итогам A/B теста группу B можно признать победителем по показателю "конверсия" (он устойчиво выше конверсии группы А). Показатель отношения средних чеков ведёт себя нестабильно в связи с наличием выбросов в виде дорогих заказов, однако исходя из анализа графика на последнем этапе и исследования статистической значимости различий мы можем предположить, что средние чеки групп будут стремиться к равенству.

`Рекомендации`:
1) добавить форму подписки на все основные страницы, чтобы собрать базу клиентов для email-рассылок
2) добавить блоки рекомендаций товаров на сайт интернет магазина, чтобы повысить конверсию и средний чек заказа 
3) добавить два новых канала привлечения трафика, что позволит привлекать на 30% больше пользователей
