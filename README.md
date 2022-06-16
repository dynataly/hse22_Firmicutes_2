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
Хохлов Владислав  | Thermoanaerobacter |  github




Презентация

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


print(pd.concat([streptococcus, staphylococcus, aerococcus, anoxybacillus, enterococcus, paenibacillus], join='outer')['func'].value_counts().to_markdown())

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


Heatmap:

![heat](https://user-images.githubusercontent.com/72361668/174020653-341dbc54-94e8-43de-b473-6bb0aa998d93.jpg)

