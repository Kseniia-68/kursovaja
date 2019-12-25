# Определение требований к модели
## Лабораторная работа №4

#### Тема ВКР: Разработка средств информационной поддержки подбора поставщиков и закупка изделий для предприятий горнодобывающей промышленности

#### Объект исследования: процессы выбора поставщиков

#### Предмет исследования: процессы выбора поставщиков оборудования и изделий для горнодобывающей промышленности

Процессы верхнего уровня: 
А0 Закупка оборудования для горнодобывающей промышленности
А1 Подбор оборудования
А2 Процесс выбора поставщика по определенным критериям 
А3 Процесс закупки изделий
А4 Оценка поставщика

Точка зрения: Руководитель отдела закупок 

Цель моделирования: отследить последовательность операций от подачи заявки на приобретение определенного оборудования до его получения



![none](https://github.com/Kseniia-68/kursovaja/blob/master/3.1.PNG)


![none](https://github.com/Kseniia-68/kursovaja/blob/master/3.2.PNG)


![none](https://github.com/Kseniia-68/kursovaja/blob/master/3.3.PNG)


![none](https://github.com/Kseniia-68/kursovaja/blob/master/3.4.PNG)
![none](https://github.com/Kseniia-68/kursovaja/blob/master/%D0%BB%D1%83%D1%87%20%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D1%89%D0%B8%D0%BA.PNG)
![none](https://github.com/Kseniia-68/kursovaja/blob/master/%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%20%D0%B7%D0%B0%D0%BA%D1%83%D0%BF%D0%BA%D0%B8.PNG)
![none](https://github.com/Kseniia-68/kursovaja/blob/master/7.PNG)

## Построение ERD-диаграммы для всех потоков
![none](https://github.com/Kseniia-68/kursovaja/blob/master/%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B8.PNG)
## Построение ERD-диаграммы для всех ролей
![none](https://github.com/Kseniia-68/kursovaja/blob/master/%D1%80%D0%BE%D0%BB%D1%8C%D0%BA.PNG)
## Построение ERD-диаграммы для всех модулей
![none](https://github.com/Kseniia-68/kursovaja/blob/master/%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8C3.PNG)

Эффект проекта:
•	Период рассмотрения = 30 дней.
•	Т (оформление закупки без системы) =  8 ч.
•	t (оформление закупки с системой) = 3 ч.
•	Сотрудник может оформить 7 закупок.
•	В системе: 7*3 =21 ч/день; 21*30 = 630 ч (за рассмотренный период)
•	Без системы: 7* 8 = 56 ч/день; 56*30 = 1680 ч (за рассмотренный период)
•	Пусть 3 сотрудников в день пользуются системой: 3*630 = 1890 ч.
•	Если сотрудники не пользуются системой: 3*420 = 5040 ч.
•	5040 – 1890 = 3150 ч/мес. выгода.


## Расчет невыровненных функциональных точек:
![none](https://github.com/Kseniia-68/kursovaja/blob/master/%D1%80%D0%B0%D1%81%D1%87%D0%B5%D1%82.PNG)

Определение числовых показателей для трудозатрат на разработку программных средств:

Методом FPA/IFPUG
![none](https://github.com/Kseniia-68/kursovaja/blob/master/%D1%84%D0%BF%D0%B0.PNG)

Расчеты, выполненные первым методом FPA IFPUG, позволяют оценить сложность требуемых для создания информационной системы программных средств в 80 выровненных функциональных точек, а объем программного кода на языках программирования высокого уровня – 3400 строк кода.

Методом COCOMO II
![none](https://github.com/Kseniia-68/kursovaja/blob/master/cocomo.PNG)

Расчеты, выполненные вторым методом COCOMO II, позволяют оценить общие трудозатраты проекта разработки программных средств в 5 человеко-месяцев, а ожидаемую продолжительность проекта – в 6 месяцев.

Вывод

Данная система позволит значительно сократить время закупки оборудования и выбора поставщика для горнодобывающего предприятия.

Сформированные модели будут использованы в выпускной квалификационной работе для наглядного представления проблем интероперабельности при построении данной системы. 


