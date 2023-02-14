# hse23_hw1

| | SRA accession  | Stage    |
|---:|:-------------|:-----------|
| 1 | SRR5836473  | 8 cell       |
| 2 | SRR3824222 | Epiblast    |
| 3 | SRR5836475  | ICM       |

## Отчёт FastQC

для образца SRR5836473_1 (8 cell read 1)

![fastqc_hw2_1](https://user-images.githubusercontent.com/103137801/218765992-a88498e6-8994-4d66-8338-b6f75e00523e.png)

**Соотношение оснований ACTG отличается по сравнению с секвенированием ДНК и РНК. Для примера первая картинка соотношение для нашего образца (T>25%, C<25%, A и G примерно 25%) , вторая для SRR3414629 из дз 4 (все примерно 25%).**

![метилир](https://user-images.githubusercontent.com/103137801/218776498-365f47c2-bf85-4723-945f-b41b155c2aba.png)

![другой](https://user-images.githubusercontent.com/103137801/218776441-81ea8def-bfe6-4cc9-ad8d-3f4bbde9ae0f.png)


## Число ридов

участок | 8cell | epiblast | ICM |
--- | --- | --- | --- | 
11347700-11367700 | 1090 | 2328 | 1456 |
40185800-40195800 | 464 | 1062 | 630 |

## Процент дупликации

-- | 8cell | epiblast | ICM |
--- | --- | --- | --- | 
процент дупликации| 18.3% | 2.92% | 9.08% |

SRR5836473 - 8cell

![newplot (1)](https://user-images.githubusercontent.com/103137801/218763864-7a712797-2ec3-48fa-92bc-31febc2528cd.png)

SRR3824222 - epiblast

![newplot (2)](https://user-images.githubusercontent.com/103137801/218764055-afdca031-832b-4ee9-b511-dd6dcefa1359.png)

SRR5836475 - ICM

![newplot](https://user-images.githubusercontent.com/103137801/218762814-fc8c5188-a0fa-4462-821b-b62ae7c857ff.png)


## M-bias plot

SRR5836473_1 - 8cell read 1

![Bismark M-bias Read 1](https://user-images.githubusercontent.com/103137801/218764759-002055ee-585d-4fd0-adb9-125257daa679.png)

SRR5836473_2 - 8cell read 2

![Bismark M-bias Read 2](https://user-images.githubusercontent.com/103137801/218764895-b07d37dd-0ee4-4389-a78d-94fdcd4f1221.png)

SRR3824222_1 - epiblast read 1

![Bismark M-bias Read 1 (1)](https://user-images.githubusercontent.com/103137801/218765057-d65ab9f7-c1fc-41fa-bb76-9dbd4c98c2a3.png)

SRR3824222_2 - epiblast read 2

![Bismark M-bias Read 2 (1)](https://user-images.githubusercontent.com/103137801/218765183-c1435516-23a6-4089-b723-0d828aaec151.png)

SRR5836475_1 - ICM read 1

![Bismark M-bias Read 1 (2)](https://user-images.githubusercontent.com/103137801/218765636-87e2eb57-367c-4a5d-92c6-6982884ad30c.png)

SRR5836475_2 - ICM read 2

![Bismark M-bias Read 2 (2)](https://user-images.githubusercontent.com/103137801/218765763-4dd8c009-97b9-4ce8-ae7f-4136b8d81876.png)


**В образцах преобладает CpG метилирование. Больше всего процентов цитозина заметилировано в образцах epiblast, меньше в 8cell и наименьший уровень метилирования в ICM.**


## Гистограммы метилирования

![8cell](https://user-images.githubusercontent.com/103137801/218759207-ee81611c-c4c7-4fda-8cec-083f29793641.png)

![epiblast](https://user-images.githubusercontent.com/103137801/218759263-ca74bb13-50a6-4a3d-beed-3730e95558b4.png)

![ICM](https://user-images.githubusercontent.com/103137801/218759027-3f6e7126-b7c7-4a9c-a198-31373e0edae4.png)

**Видно что в 8cell присутствуют совершенно разные уровни метилирования, в epiblast большинство цитозинов - сильно метилированны, в ICM большинство - слабо метилированны. По порядку развития организма идет 8cell --> ICM --> epiblast, т.е. цитозины сначала разметилируются, а потом сильно метилируются.**


## Бонус 

по участку chr11:3100030-3500030

![coverage methylation](https://user-images.githubusercontent.com/103137801/218758954-b50a8bd6-057c-4a48-95c7-efbd18c4828b.png)




