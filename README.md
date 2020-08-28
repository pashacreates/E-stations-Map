# E-stations-Map

Ссылка на хостинг
https://epoint-e19c5.firebaseapp.com/

Задание на практикум
Приложение-карта точек зарядки электромобилей с графиками статистики по точкам и с возможностью поиска ближайшей точки зарядки
Технологии: карты, загрузка данных из стороннего API, https://openchargemap.org/site/develop/api?ref=public-apis, highcharts, haversine, geolocation API

1 Загрузить на страницу 2 000 точек зарядки электромобилей в Великобритании. Выгрузить эти точки на карту.

2 Настроить на карте агрегатор точек - если очень много близко лежащих точек, они складываются в одну большую с указанием количества.

3 При клике на карте на точку открыть информационное окно с данными о точке. Это полный адрес, телефон, стоимость использования и кол-во зарядных пунктов.

4 При перемещении карты и масштабировании справа от карты выводить список тех точек, которые видны на карте. Выводить название, стоимость зарядки и кол-во зарядных пунктов.
При клике на точку в этом списке отматывать карту на максимальный масштаб, и чтобы эта точка оказалась в центре, а также открыть информационное окно с данными точки.

5 При перемещении карты также строить (с задержкой, без моргания) круговую диаграмму, которая показывает кол-во зарядных
точек с группировкой по количеству зарядных пунктов в точке.

6 В списке в верхушке есть кнопка “Найти ближайшую”. При нажатии на неё отыскивается ближайшая точка (отправить данные  в веб-поток!) и карта отматывается с центрированием к ней. 
