# [Система мониторинга температуры и влажности в помещении](http://iuriier.pythonanywhere.com/)
____
## Схема устройства
<img src="./NodeMCU_DHT11_Interfacing.png" width="500">
____
## Система позволяет
* видеть текущие температуру и влажность в помещении;
* изменять частоту снятия показаний;
* получить всю историю измерений (ограниченно: первая тысяча измерений);
*	получить средние значения температуры и влажности за введенный пользователем промежуток времени.
____
## Будущее системы
* Добавление автообновляемых средних показателей за день, неделю и месяц;
* Возможность более детальной настройки периодов, за которые выводятся показатели;
* Изменение внешнего вида;
* Добавление комментариев  и повышение usability;
* Рефакторинг кода;
* Поддержка SQLAlchemy;
* Вывод всей истории измерений и поиск по ней;
Возможно будет добавлено следующее:
* Визуализация собранной информации;
* Добавление новых функций для работы с данными (Например, добавление других статистических метрик, кроме среднего).
