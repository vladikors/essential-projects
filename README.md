# essential-projects
Projects from traineeships and from data analysis study course

Исследовал инвестиционную программу Северсталь (публично доступная редакция, ноябрь 2022 г.) 
Получил в pdf и преобразовал данные (361 поз., Excel, сводная таблица). Для каждого мероприятия экспертно определил направленность. 
Предприятие планирует реализовать наибольшее количество мероприятий, направленных на улучшение условий труда (96 шт.) и установку / модернизацию систем контроля и управления технологическим процессом (55 шт.). Мероприятия по модернизация основного технологического оборудования и ввод новых агрегатов будут выполняться точечно (24 шт.). Следует отметить, что мероприятия по улучшению условий и охране труда запланированы практически во всех подразделениях (установка кондиционеров, системы пожаротушения, оборудование пешеходных маршрутов). Мероприятия по системам контроля и управления технологическим процессом максимально сконцентрированы в холодном, горячем прокате и сталеплавильном производстве (39 шт., 11% от суммарного количества мероприятий программы).
Подобная конфигурация программы, вероятно, позволяет добиться максимального эффекта при минимуме капитальных затрат в условиях санкций, фактическом запрете экспорта, падении прибыльности в условиях исторически сложившегося дисбаланса производства и потребления в России в объеме 70+ и 40+ млн. тонн в год соответственно. 
В качестве эффектов программы возможно прогнозировать улучшение условий труда и удовлетворенности сотрудников, а также повышение качества продукции в основных прокатных цехах. Подготовлен дашборд в Power BI, представлен скрин дашборда.

Исследовал некоторые метрики пользователей e-commerce площадки. 
Использовал Python, Pandas, Seaborn, Jupiter, Git. Выполнил разведочный анализ данных (100 тыс. позиций). Предложил считать фактом покупки отгрузку или доставку товара (статусы shipped, delivered). Определил пользователей, которые совершили покупку только один раз. Определил количество заказов в месяц, не доставленных по разным причинам. Определил для каждого товара день недели, в который товар чаще всего покупается. Наконец, выполнил RFM сегментацию пользователей. Определил границы для метрик Recency, Frequency, Monetary для отнесения пользователей к сегменту. Построил частотные диаграммы распределения метрик. Предложил стратегии работы с сегментами. Дал наименования, кратко характеризующие стратегии. Определил принадлежность каждого покупателя к своему сегменту.

Разработал с нуля метрики качества планирования объемов продаж по портфелям новых продуктов за 2021 г.
Данные по составу инициатив выгружал из SAP Innovation Management, по отгрузке - из Power BI дашборда, по причинам отклонений - из Excel файла. Объединял данные по id инициативы, далее обрабатывал в Excel (138 проекта). Выбрал окончательно 62 проекта исходя из наличия данных по ним. Строил частотные диаграммы распределения отклонений фактических данных от плановых в тоннах и в процентах по выборке в целом и крупным категориям. Строил сводную таблицу по портфелям инициатив и причинам отклонений. Предложил метрику для определения статистически максимально допустимого отклонения исходя из правила 3 сигма. Сформулировал выводы по качеству планирования. Предложил сформировать дашборд в Power BI для выгрузки данных и отслеживания метрик. Передал выводы и предложения руководителю.

Исследовал каталог фирмы Dillinger для определения продукции, не производимой на Северсталь. 
Использовал pdf файл с сайта компании Dillinger в качестве исходных данных. Выполнил преобразование файла в Excel формат 513 поз. отдельных марок и групп марок (лист data). Выделил отдельные марки с получением 884 уникальных позиций, производимых по своим режимам обработки. По имеющимся данным отгрузки двух компаний (884 и 3370 поз.) определил с использованием ВПР расхождение в сортаменте выпускаемой продукции. Нашел 400+ видов продукции, не производимой непосредственно либо в виде аналогов (лист Dillinger). Также обратил внимание и сформировал из каталога Dillinger перечень брендов 20 поз. с указанием краткого описания (лист branded steels). Передал результаты руководителю для изучения перспектив спроса на продукцию 

Разрабатывал регрессионную модель прогнозирования качества металлопроката в Excel, Minitab, Python.
Получал в Excel исходные данные. Выполнял в Python заполнение пустых ячеек средними значениями с формированием xls файла. Рассчитывал в Minitab уравнения регрессии для обучающей выборки. Использовал контрольную выборку для определения качества прогнозирования. Передал результаты руководителю.
Файл не может быть представлен.

Решал задачу на статистическую значимость расхождения двух средних по учебным данным. 
Исследовал выборки по количеству брака в партиях равного веса (Excel), полученному при работе по старой (131 поз.) и новой технологиям (98 поз.). Выделил, согласно заданию, количество случаев получения брака более 3 кг на партию по старой и новой технологиям. Рассчитал частоту получения более 3 кг брака. Определил нулевую и альтернативную гипотезы. Установил уровень значимости 0,05. Выбрал в качестве случайной величины разницу частот получения брака по старой и новой технологиям. Рассчитал вероятность того, что случайная величина примет значение больше, чем полученное по результатам наблюдений на основании выборок. Получил вероятность 0,1 для нулевой гипотезы. Данное значение не позволяет нам отклонить нулевую гипотезу при приянятом уровне значимости 0,05. Сформулировал вывод, что применяемая технология не влияет на уровень брака. Представил решение задачи руководителю конкурса.
