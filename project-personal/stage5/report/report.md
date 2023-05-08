---
## Front matter
title: "Отчет по 5 этапу индивидуального проекта"
subtitle: "Добавление к сайту данных о себе"
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

Добавить к сайту данные о своим проектах и сделать 2 поста.


# Выполнение лабораторной работы

1) Я создал новый проект с названием "site" и затем переименовал его в "создание своего личного сайта". Добавил в эту публикацию фотографии, краткое описание процесса создания и ссылки на мой ютуб-канал, где я показываю, как создавать сайт и ссылку на гитхаб, где располагается сам репозиторий, а так же установил тег "программирование".

![Первый проект](/home/aalushin/work/study/study_2022-2023_os-intro/project-personal/stage5/report/image/Снимок экрана от 2023-05-09 02-12-35.png){#fig:001 width=70%}

2) Я создал еще один проект с названием "Teach" и затем переименовал его в "репетиторство". В этот проект я добавил описание своей работы в роли репетитора и немного порассуждал о репетиторстве. Так же добавил тег "работа".

![Второй проект](/home/aalushin/work/study/study_2022-2023_os-intro/project-personal/stage5/report/image/Снимок экрана от 2023-05-09 02-12-14.png){#fig:002 width=70%}

3) Сделал пост о прошедшей неделе. Описал свою работу за эту неделю, мое посещение др и ужасную погоду, которая мне не нравится.

![Пост о прошедшей неделе](/home/aalushin/work/study/study_2022-2023_os-intro/project-personal/stage5/report/image/Снимок экрана от 2023-05-09 02-12-51.png){#fig:003 width=70%}

4) Сделал пост о научном языке программирования. Этот пост получился довольно маленьким, так как я не нашел информацию в интернете. В этом посте описывается один и тот же пример, но в разных математических смыслах.

![Пост о научном языке программирования](/home/aalushin/work/study/study_2022-2023_os-intro/project-personal/stage5/report/image/Снимок экрана от 2023-05-09 02-13-09.png){#fig:004 width=70%}
 
# Выводы

Я добавил к сайту информацию о своих проектах и сделал 2 поста.

# Список литературы{.unnumbered}

::: {#refs}
:::
