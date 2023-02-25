---
## Front matter
title: "Отчет по индивидуальному проекту. 1 этап."
subtitle: "Размещение на github"
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

Размещение заготовки сайта на github.

# Выполнение работы

1)Я установил go hugo для начала работы.

![Установка go hugo](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 13-40-48.png){#fig:001 width=70%}

2) В терминале клонируем репозиторий с сайта (предварительно добавив новый репозиторий)

![Клонирование репозитория](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 13-53-17.png){#fig:002 width=70%}

3) Проверка команды hugo в новом репозитории.

![Содержимое каталога до команды hugo](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 13-54-21.png){#fig:003 width=70%}

![Содержимое каталога после команды hugo](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 13-56-26.png){#fig:004 width=70%}

4) У нас создалось несколько новый папок, после проверки работоспособности, удаляем каталог "public".

![Удаление каталога public](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 13-56-42.png){#fig:005 width=70%}

5) Cоздаем локальную ссылку на сайт, с помощью команды hugo server.

![Создание локального сайта](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 14-10-43.png){#fig:006 width=70%}

6) Копируем ссылку и открываем в браузере. Нас перекинет на сайт, который мы создали.

![Локальный сайт](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 14-23-44.png){#fig:007 width=70%}

7) Удаление предупреждения на сайте через папку _index.md. В этой папке удаляем первый блок.

![Удаление предупреждения](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-24 21-52-09.png){#fig:008 width=70%}

8) После проверки локального сайта, создаем новый пустой репозиторий на сайте github, и клонируем его на компьютер. Обязательно надо назвать репозиторий таким же именем как и в github.

![Клонирование нового репозитория](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 14-45-13.png){#fig:009 width=70%}

9) Проверяем чтобы новый репозиторий был пустой.

![Проверка нового репозитория](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 14-45-54.png){#fig:010 width=70%}

10) Далее в новом репозитории создаем основную ветку "main" и в ней создаем еще один текстовый файл "README.md".

![Создание основной ветки и файла](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 14-46-40.png){#fig:011 width=70%}

11) Отправляем созданную ветку обратно на сайт github, вместо команды "git push", я использовал команду "git push origin main", чтобы отправить именно основную ветку.

![Отправка изменений на github](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 14-47-33.png){#fig:012 width=70%}

12) Объединяем репозиторий blog и SkLjT.github.io. Но из-за созданного файла public, мы не может объединить репозитори.

![Попытка объединения репозиториев](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 15-11-42.png){#fig:013 width=70%}

13) Для того, чтобы объединить оба репозитория, нужно в папке gitignore, перед словом public поставить "#", чтобы слово отображалось как комментарий.
![Комментирование слова public](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 15-12-08.png){#fig:014 width=70%}

14)Объединение двух репозиториев.

![Объединение репозиториев](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 15-13-07.png){#fig:015 width=70%}

15) Создание сайта с помощью команды hugo.

![Создание сайта](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 15-13-36.png){#fig:016 width=70%}

16)Проверка подключения каталога к нужному репозиторию.

![Подключение каталога](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2023-02-23 15-14-02.png){#fig:017 width=70%}

17) С помощью команды "git push" отправляем все изменения на сайт github.

![Изменения в репозитории](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/image.png){#fig:018 width=70%}

18) В качестве ссылки для сайта мы используем ссылку с github, после /, в моем случаи SkLjT.github.io

![Ссылка на сайт](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/image(1).png){#fig:019 width=70%}

19) Проверка сайта. По ссылке можно зайти с любого устройства и аккаунта.

![Сайт](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/image(2).png){#fig:020 width=70%}


# Выводы

Я разместил заготовки для сайта на платформе github.

# Список литературы{.unnumbered}

::: {#refs}
:::
