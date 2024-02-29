# Визуализация ДТП Иркутской области 
## Проект выполнила Фадеева Елизавета группа БГЕО221
Для анализа был взят датасет с ДТП в Иркутской области в формате .geojson с сайта https://dtp-stat.ru/opendata. В датасете имеются данные о координатах, районе, освещении, дорожном покрытии, категории аварии, тяжести ДТП: количестве погибших и раненых. 

На первом этапе данные по ДТП были визуализированы на интерактивной карте с помощью Plotly Express. Координаты были образаны по крайним точкам Иркутской области, для того, чтобы отсечь выбросы.

На следующем этапе аварии были классифицированы по тяжести ДТП: легкие, тяжелые, с погибшими. На интерактивной карте они отображаются разными цветами, также при наведении на точку отображаются другие данные об этом ДТП. 
