# hse22_Firmicutes_2

ФИО           | Род                            | репозиторий
---------------------|------------------------------------------|-
Арчибасова Анна | Caldicellulosiruptor | github 
Бурцев Артем| Staphylococcus | [github](https://github.com/prometneus/hse22_project)   
Геворков Иван  | Aerococcus | [github](https://github.com/IvanTurHi/hse22_project)    
Дьячкова Наталия  | Enterococcus| [github](https://github.com/dynataly/hse22_project)   
Еринова Варя | virgibacillus | github
Зинов Александр  | Paenibacillus   |  [github](https://github.com/sashkent3/biominor_hse22_project)
Соколов Антон  | Streptococcus  |   [github](https://github.com/antonsokol57/hse22_project)
Хан Андрей   | Anoxybacillus  |     [github](https://github.com/midzukami/hse22_project)
Хохлов Владислав  | Thermoanaerobacter |  [github](https://github.com/entergro/hse22_project)


Статистика по всем родам:

Род |	Длина генома | GC |	кол-во генов | кол-во ZДНК участков |	Кол-во генов с ZДНК в промотере
------|----|---|---|---|-
Caldicellulosiruptor |	2709221 |	35.4 |	2508.4. |	853.6	|
Staphylococcus |	2391536 |	37.8 |	2209.4 |	3554	|
Aerococcus |	1938957 |	40.7 |	1819 |	1192 |	206
Enterococcus	| 3367528	| 39.1	| 3263 |	796 |	193
virgibacillus		| | | | |			
Paenibacillus |	7054719 |	55.5 |	6045 |	31796 |	1277
Streptococcus |	2 008 585.6 |	42.7 |	1883.6 |	1246.2 |	66.6
Anoxybacillus	| | | | |				
Thermoanaerobacter	| | | | |				


[Презентация](https://docs.google.com/presentation/d/1Svm-As2WG6i6F2u52PYbz7J38om2SyB_J_lKUWkPtmQ/edit#slide=id.p)

[Статистика по всем кластерам](https://github.com/dynataly/hse22_Firmicutes_2/blob/main/cluster_stats.csv):

.. | ..
---|----
Общее число кластеров | 15280
Число кластеров, сключающих не меньше половины генов | 1050
Максимальное количество родов | 6
Максимальное количество генов | 21



Распределение количества генов в кластерах:



![genes](https://user-images.githubusercontent.com/72361668/173962626-fd5f0210-486e-4704-a225-ea4f69726ba3.png)




# Функции генов

## Для cluster_6

[Колабчик](https://colab.research.google.com/drive/1Q5G9vosjOBqkwfDbzEas0M8iSipoAlf4?usp=sharing)

### Aerococcus

|               function   | count  |
|:-------------------------|-------:|
| 30S ribosomal protein S9 |      4 |
| glutamate--tRNA ligase   |      4 |

### Anoxybacillus

|              function    | count |
|:-------------------------|-------:|
| 30S ribosomal protein S9 |      5 |
| glutamate--tRNA ligase   |      5 |

### Enterococcus

|               function   | count  |
|:-------------------------|-------:|
| 30S ribosomal protein S9 |      4 |
| glutamate--tRNA ligase   |      4 |

### Paenibacillus

|              function    |  count |
|:-------------------------|-------:|
| 30S ribosomal protein S9 |      4 |
| glutamate--tRNA ligase   |      4 |

### Staphylococcus

|              function    |  count |
|:-------------------------|-------:|
| 30S ribosomal protein S9 |      3 |
| glutamate--tRNA ligase   |      3 |

### Streptococcus

|                function  | count  |
|:-------------------------|-------:|
| 30S ribosomal protein S9 |      5 |
| glutamate--tRNA ligase   |      5 |


## Для cluster_5


|                function  | count  |
|:------------------------------------------------|-------:|
| 50S ribosomal protein L18                       |     25 |
| translation initiation factor IF-2              |     25 |
| phosphopyruvate hydratase                       |     25 |
| excinuclease ABC subunit UvrA                   |     25 |
| tRNA guanosine(34) transglycosylase Tgt         |     25 |
| 30S ribosomal protein S3                        |     25 |
| polyribonucleotide nucleotidyltransferase       |     25 |
| chaperonin GroEL                                |     24 |
| translational GTPase TypA                       |     24 |
| Mini-ribonuclease 3                             |     21 |
| ATP-dependent Clp protease ATP-binding subunit  |     18 |
| phosphocarrier protein HPr                      |     16 |
| ATP-dependent protease ATP-binding subunit ClpC |      7 |
| ribonuclease III                                |      4 |
| HPr family phosphocarrier protein               |      2 |


## Heatmap:


![heat_no_t_horiz](https://user-images.githubusercontent.com/72361668/174398971-f7e8df98-5ce3-464b-8b35-3c1c726e1748.jpg)


## Визуализация для двух кластеров, в которые входят представители 6 родов, имеющие Z-ДНК в промотерах:

Кластер 1: 30S ribosomal protein S9

![cluster1](https://user-images.githubusercontent.com/72361668/174435829-6ea01488-0b91-4559-bd78-9f974acf55da.jpeg)


Кластер 2: glutamate--tRNA ligase


![cluster2](https://user-images.githubusercontent.com/72361668/174435833-19f870f8-5116-4cf1-83f7-c2d05bf81dcc.jpeg)


## Аминокислотное выравнивание:

Видно, что белки из одного кластера действительно похожи друг на друга:

Кластер 1:

![cluster1](https://user-images.githubusercontent.com/72361668/174436214-0b2fd049-0b01-422e-bb28-1a5d752e506b.jpg)


Кластер 2:

![cluster2](https://user-images.githubusercontent.com/72361668/174436218-46fd5fba-7c33-47f3-9a9d-f55399f21635.jpg)



## Нуклеотидное выравнивание:

Кластер 1:

![cluster1_zdna](https://user-images.githubusercontent.com/72361668/174437563-d48badf0-84ca-42e4-8faa-af22e2d7bb97.jpg)


Кластер 2:

![cluster1_zdna](https://user-images.githubusercontent.com/72361668/174437194-ff355f54-4f9e-473c-acb2-8295551cfa9b.jpg)

