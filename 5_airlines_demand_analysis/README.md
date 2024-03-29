# Анализ деятельности авиакомпании

Используемые библиотеки Python - pandas, matplotlib.pyplot, seaborn.

`Задача`:  на основе данных о моделях самолётов и городах, в которых совершаются рейсы авиакомпании, провести анализ её деятельности.

Визуализированы распределения рейсов по моделям самолётов (гистограмма, пай-чарт), визуализировано распределение рейсов в день (бокс-плот, виолин-плот). Подсчитан список самых популярных городов, откуда совершаются рейсы, созданы соответствующие графики (гистограмма, пай-чарт).

`Выводы`: 
- большая часть рейсов приходится на Sukhoi SuperJet-100, Bombardier CRJ-200 и Cessna 208 Caravan;
- в большей части городов происходит от 2 до 6 рейсов в день. Медиана - 3. Москва и Санкт-Петербург - 2 выброса (130 и 31 рейс в день соответственно);
- топ-10 городов по количеству рейсов: Москва, Санкт-Петербург, Новосибирск, Красноярск, Екатеринбург, Ростов-на-Дону, Пермь, Брянск, Сочи, Ульяновск;
- среди 10 самых загруженных городов больше половины рейсов приходится на Москву (51,8 %), также значительная доля у Санкт-Петербурга (12,4 %).
