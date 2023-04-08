---
## Front matter
title: "Отчет по 3 этапу индивидуального проекта"
subtitle: "Добавление достижений, опыта и навыков"
author: "Лушин Артем Андреевич"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Добавить информацию о достижениях, навыках и опыте. 


# Выполнение лабораторной работы

1) Я добавил на сайт информацию о своих навыках. Изменил иконки и процент владения каждым навыком.

![Навыки](/home/aalushin/work/study/study_2022-2023_os-intro/project-personal/stage3/report/image/Снимок экрана от 2023-04-08 00-55-09.png){#fig:001 width=70%}

2) Я добавил на сайт информацию о своем опыте. Описал опыт своей работы в сфере репетиторства и создании приложения.

![Опыт](/home/aalushin/work/study/study_2022-2023_os-intro/project-personal/stage3/report/image/Снимок экрана от 2023-04-08 00-55-17.png){#fig:002 width=70%}

3) Я добавил на сайт информацию о своих достижениях. Добавил информацию о золотой медали и разрядах КМС.

![Достижения](/home/aalushin/work/study/study_2022-2023_os-intro/project-personal/stage3/report/image/Снимок экрана от 2023-04-08 00-55-23.png){#fig:003 width=70%}

4) Создал пост о прошедшей неделе и написал, что у меня было интересного за неделю.

![Прошедшая неделя](/home/aalushin/work/study/study_2022-2023_os-intro/project-personal/stage3/report/image/Снимок экрана от 2023-04-08 00-55-55.png){#fig:004 width=70%}

5) Создал пост о Языке разметки Markdown.

![Язык разметки Markdown](/home/aalushin/work/study/study_2022-2023_os-intro/project-personal/stage3/report/image/Снимок экрана от 2023-04-08 00-56-14.png){#fig:005 width=70%}

# Выводы

Добавил информацию о навыках, опыте и достижениях на сайт.

# Список литературы{.unnumbered}

::: {#refs}
:::
