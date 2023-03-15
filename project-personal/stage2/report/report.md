---
## Front matter
title: "Отчет по 2 этапу индивидуального проекта"
subtitle: "Добавление данных о себе"
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

Добавить на сайт свою фотографию, данные о себе и выложить несколько постов.


# Выполнение лабораторной работы

1) Я добавил в папку /home/aalushin/work/blog/content/authors/admin данные о себе, свои интересы и образование.

![Данные о себе](/home/aalushin/work/study/2022-2023/Операционные системы/study_2022-2023_os-intro/project-personal/stage2/report/image/Снимок экрана от 2023-03-14 21-23-21.png){#fig:001 width=70%}

2) Добавил свою фотографию на обложку сайта.

![Добавление фотографии](/home/aalushin/work/study/2022-2023/Операционные системы/study_2022-2023_os-intro/project-personal/stage2/report/image/Снимок экрана от 2023-03-15 20-49-40.png){#fig:002 width=70%}

3) Я создал пост о прошедшей неделе. Затем заполнил файл и написал как прошла неделя.

![Создание поста](/home/aalushin/work/study/2022-2023/Операционные системы/study_2022-2023_os-intro/project-personal/stage2/report/image/Снимок экрана от 2023-03-15 20-52-53.png){#fig:003 width=70%}

![Добавление текста](/home/aalushin/work/study/2022-2023/Операционные системы/study_2022-2023_os-intro/project-personal/stage2/report/image/Снимок экрана от 2023-03-15 20-54-37.png){#fig:004 width=70%}

4) Я выбрал "Управление версиями. Git." и создал пост по этой тема. Нашел в интернете информацию и заполнил файл.

![Создание поста](/home/aalushin/work/study/2022-2023/Операционные системы/study_2022-2023_os-intro/project-personal/stage2/report/image/Снимок экрана от 2023-03-15 20-56-20.png){#fig:005 width=70%}

![Добавление информации](/home/aalushin/work/study/2022-2023/Операционные системы/study_2022-2023_os-intro/project-personal/stage2/report/image/Снимок экрана от 2023-03-15 20-56-59.png){#fig:006 width=70%}

5) Затем я создал локальный сервер, чтобы проверить правильность заполнения данных.

![Проверка на локальном сервере](/home/aalushin/work/study/2022-2023/Операционные системы/study_2022-2023_os-intro/project-personal/stage2/report/image/Снимок экрана от 2023-02-23 14-10-43.png){#fig:007 width=70%}

6) Когда я убедился в правильности заполнения данных, я отправил все данные на систему git и уже проверил сам сайт. По ссылке  SkLjT.github.io oткрывается мой сайт.

![Готовый онлайн сайт](/home/aalushin/work/study/2022-2023/Операционные системы/study_2022-2023_os-intro/project-personal/stage2/report/image/Снимок экрана от 2023-03-15 21-02-41.png){#fig:008 width=70%}

# Выводы

Я добавил на сайт данные о себе и научился писать посты.

# Список литературы{.unnumbered}

::: {#refs}
:::
