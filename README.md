# My-projects
Описание выполненных проектов


| Название проекта | Задачи проекта | Описание | Используемые библиотек, навыки и инструменты | 
| :---------------------- | :---------------------- | :---------------------- | :---------------------- |
| [Исследование надежности заемщиков](https://github.com/JulNika/My-projects/tree/main/Research%20of%20borrowers%20reliability) | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок | На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три. | Pyton, Pandas, предобработка данных |
|[Продажа квартир в Санкт-Петербурге](https://github.com/JulNika/My-projects/blob/main/Determining%20the%20prices%20of%20apartments%20in%20St.%20Petersburg/%D0%9F%D1%80%D0%BE%D0%B4%D0%B0%D0%B6%D0%B0%20%D0%BA%D0%B2%D0%B0%D1%80%D1%82%D0%B8%D1%80%20%D0%B2%20%D0%A1%D0%B0%D0%BD%D0%BA%D1%82-%D0%9F%D0%B5%D1%82%D0%B5%D1%80%D0%B1%D1%83%D1%80%D0%B3%D0%B5%20-%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D1%80%D1%8B%D0%BD%D0%BA%D0%B0%20%D0%BD%D0%B5%D0%B4%D0%B2%D0%B8%D0%B6%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8.ipynb) | Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир |На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания. | Pytom, Pandas, Matplotlib, исследовательский анализ, предобработка данных, визуализация данных |
|[Анализ успешных компьтерных игр для планирования рекламной компании](https://github.com/JulNika/My-projects/blob/main/Analisys%20of%20computer%20games/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D1%83%D1%81%D0%BF%D0%B5%D1%88%D0%BD%D1%8B%D1%85%20%D0%BA%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D1%8B%D1%85%20%D0%B8%D0%B3%D1%80%20%D0%B4%D0%BB%D1%8F%20%D0%BF%D0%BB%D0%B0%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20%D1%80%D0%B5%D0%BA%D0%BB%D0%B0%D0%BC%D0%BD%D0%BE%D0%B9%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D0%B8.ipynb)| Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. |Проведен предварительный анализ и предобработка данных. Выделены Топ-5 самых популярных и непопулярных игровых жанров и платформ. Проверены гипотезы об одинаковости рейтингов двух платфом и разности рейтингов 2 жанров.| bpxplot. histogram, статистический тест |
|[Классификация клиентов телеком компании ](https://github.com/JulNika/My-projects/tree/main/Classification%20of%20telecom%20company's%20clients)|На основе данных предложить клиенту тариф.|Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям один из новых тариф.|Pytom, Pandas, Matplotlib, Scikit-learn |||||||
|[Прогнозирование оттока клиентов банка](https://github.com/JulNika/My-projects/tree/main/Forecasting%20outflow%20of%20customers%20in%20the%20bank)|На основе данных из банка определить клиент, который может уйти|Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.| Pandas, Matplotlib, Scikit-learn|
|[Выбор локации для скважины](https://github.com/JulNika/My-projects/tree/main/Choosing%20the%20location%20for%20the%20well)| На основе данных геологи разведки выбрать район добычи нефти | Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль.  | Pandas, Scikit-learn, бутстреп |
|[Прогнозирование концентрации золота при проведении процесса очистки золота](https://github.com/JulNika/My-projects/tree/main/Predict%20the%20concentration%20of%20gold%20during%20the%20gold%20purification%20process)| Спрогнозировать концентрацию золота при проведении процесса очистки золота | Строитстся модель машинного обучения для промышленной компании, разрабатывающая решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. | Pytom, Pandas, Matplotlib, Scikit-learn, Numpy, исследовательский анализ данных|
|[Прогнозирование стоимости жилья в жилом массиве](https://github.com/JulNika/My-projects/tree/main/Forecasting%20the%20cost%20of%20housing)| Определить медианную стоимость квартиры | Сервис по продаже квартир закала разработку модели по прогнозированию стоимости квартиры  |Pyton, Pandas, Spark|
|[Защита персональных данных клиентов](https://github.com/JulNika/My-projects/tree/main/Model%20of%20protection%20of%20personal%20data%20of%20clients)| Разработка модели анонимизации персональных данных| Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется. | Pyton, NumPy, Scikit-learn|
|[Построение модели определения стоимости автомобиля](https://github.com/JulNika/My-projects/tree/main/Determining%20the%20price%20of%20a%20car)| Разработка системы рекомендации стоимости автомобиля на основе его описания | Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля. | Pyton, Pandas, lightgbm|
|[Решение задач по SQL](https://github.com/JulNika/My-DS-projects-Practicum-/blob/main/%D0%9F%D1%80%D0%BE%D0%B4%D0%B2%D0%B8%D0%BD%D1%83%D1%82%D1%8B%D0%B9%20SQL.ipynb)| Подключение к БД, задачи по SQL| функция усечения даты, сортировка данных, рамки в оконных функциях, подсчет сумм с накоплением, расчет среднего значения за период и проч.| SQL, pandas, matplotlib, plotly, seaborn|||
|[Прогнозироввание температуры](https://github.com/JulNika/My-DS-projects-Practicum-/blob/main/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%82%D0%B5%D0%BC%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D1%83%D1%80%D1%8B%20%D0%B7%D0%B2%D0%B5%D0%B7%D0%B4%D1%8B.ipynb)| Определить температуру на поверхности звезды | На основе косвенных данных построить модель оценки температуры на поверхности звезды| Pandas, Pyton, PyTorch|
|[Разработка системы предупреждения аварий на каршеринге](https://github.com/JulNika/My-DS-projects-Practicum-/blob/main/%D0%A0%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0%20%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%8B%20%D0%BF%D1%80%D0%B5%D0%B4%D1%83%D0%BF%D1%80%D0%B5%D0%B6%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B0%D0%B2%D0%B0%D1%80%D0%B8%D0%B9%20%D0%BD%D0%B0%20%D0%BA%D0%B0%D1%80%D1%88%D0%B5%D1%80%D0%B8%D0%BD%D0%B3%D0%B5.ipynb)| Построить систему предупреждения об аварии клиентам каршеринга | На основе исторических данных из базы данных выявить причины возникновения аварий и создать алерт о безопасном вождении. | SQL, Pandas, Scikit-learn, PostgreSQL, SQLAlchemy
|[Прогнозирование заказов такси на следующий час](https://github.com/JulNika/My-DS-projects-Practicum-/blob/main/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%BA%D0%B0%D0%B7%D0%BE%D0%B2%20%D1%82%D0%B0%D0%BA%D1%81%D0%B8%20%D0%BD%D0%B0%20%D1%81%D0%BB%D0%B5%D0%B4%D1%83%D1%8E%D1%89%D0%B8%D0%B9%20%D1%87%D0%B0%D1%81.ipynb)| Разработка системы предсказания объема заказа. |Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания. | Pyton, Pandas, Scikit-learn, statsmodels|
|[Обучение модели классификации текстов](https://github.com/JulNika/My-DS-projects-Practicum-/blob/main/%D0%9E%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%20%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D0%B8%20%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BE%D0%B2.ipynb)|Определение токсичности комментарии. | Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. |  Pyton, Pandas, BERT, nltk, tf-idf|
|[Определение возраста покупателей по фотографии](https://github.com/JulNika/My-DS-projects-Practicum-/blob/main/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%D0%BE%D0%B7%D1%80%D0%B0%D1%81%D1%82%D0%B0%20%D0%BF%D0%BE%D0%BA%D1%83%D0%BF%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%20%D0%BF%D0%BE%20%D1%84%D0%BE%D1%82%D0%BE%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D0%B8.ipynb)| Определение возраста по фотографии| Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Строится модель, которая по фотографии определит приблизительный возраст человека. В вашем распоряжении набор фотографий людей с указанием возраста.| Pyton, Keras|
|[Построение модели для телекома, предсказывающей разорвет ли абонент контракт](https://github.com/JulNika/My-DS-projects-Practicum-/blob/main/%D0%9C%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C%20%D0%B4%D0%BB%D1%8F%20%D0%BF%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D1%8F%20%D1%80%D0%B0%D0%B7%D0%BE%D1%80%D0%B2%D0%B5%D1%82%20%D0%BB%D0%B8%20%D0%B0%D0%B1%D0%BE%D0%BD%D0%B5%D0%BD%D1%82%20%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%B0%D0%BA%D1%82.ipynb)| Построить модедь, котоорпая будет предсказывать уход абонента |Оператор связи хочет бороться с оттоком клиентов. Для этого его сотрудники начнут предлагать промокоды и специальные условия всем, кто планирует отказаться от услуг связи. Чтобы заранее находить таких пользователей, заказчику нужна модель, которая будет предсказывать, разорвёт ли абонент договор. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и услугах. Ваша задача — обучить на этих данных модель для прогноза оттока клиентов| Pyton, matplotlib, Torch, phik, NumPy, Catboost, Seaborn |
|[Поиск по изображению](https://github.com/JulNika/My-DS-projects-Practicum-/blob/main/%D0%9F%D0%BE%D0%B8%D1%81%D0%BA%20%D0%BF%D0%BE%20%D0%B8%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8E.ipynb)| Разработать простой поиск картинок по запросу | Разработать модель соединяющую текстовые данные и изображения.  |Scikit-learn, Bert, PyTorch, Keras|
