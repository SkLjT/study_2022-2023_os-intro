---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №6
subtitle: Поиск файлов. Перенаправление ввода-вывода. Просмотр запущенных процессов
author:
  - Лушин А.А.
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Факультет Физико-математических и естественных наук
date: 18 февраля 2005

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

   * Лушин Артем Андреевич
  * бакалавр направления математика-механика
  * ученик математического института
  * Российский университет дружбы народов
  * [lusin5745@gmail.com](lusin5745@gmail.com)
  * <@temo4ek>

:::
::: {.column width="30%"}

![](./image/mee.jpeg)

:::
::::::::::::::

# Вводная часть

## Цели и задачи

- Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем

# Ход работы

## Запись в файлы

С помощью символов > и >> мы можем записать одной командой данные которые искали. Если мы хотим записать название всех файлов из домашнего каталога, то для начала мы выводим все файлы с помощью оманды ls, а потом уже с помощью символа > записываем их в файл. Команда выглядит следующим образом (см. рисунок)

![](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/labs/lab06/presentation/image/Снимок экрана от 2023-02-25 23-46-50.png)

## Поиск файлов по фрагментами названия

Мы можем найти файлы, зная его фрагмент. С помощью команды ls или find мы можем вывести в терминал все файлы которые начинаются или заканчиваются на любой символ, а так же по разрешению файлов. К примеру, если мы хотим найти все файлы в домашнем каталоге с разрешением txt, то мы вводим команду ls *.txt, и в терминале будут отображаться все файлы с таким разрешением.

![](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/labs/lab06/presentation/image/Снимок экрана от 2023-02-25 23-59-31.png)

## Запуск в фоновом режиме

Мы можем запустить любою команду в фоновом режиме. К примеру, если мы хотим запустить редактор gedit в фоновом режиме, в консоль мы должны будем записать "gedit &". Для того чтобы завершить этот процесс, понадобится воспользоваться командой kill. А чтобы управлять такими процессами, используем команду jobs.

![](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/labs/lab06/presentation/image/Снимок экрана от 2023-02-26 00-03-58.png)

## Df и du

Команда du отображает число килобайт, который занимает тот или иной файл. То есть, если мы хотим узнать, сколько килобайт занимает каждый файл из домашнего каталога, нам нужно ввести du -a ~. Команда DF отображает размер каждого смонтированного диска. 

![](/home/aalushin/work/study/2022-2023/Операционные системы/os-intro/labs/lab06/presentation/image/Снимок экрана от 2023-02-26 02-06-01.png)


# Результат

## Вывод 

Я ознакомился с инструментами поиска файлов и фильтрации текстовых данных. Приобрел практические навыки: по управлению процессами, по проверке диска и обслуживанию файловых систем.

## Контрольные вопросы

1. Какие потоки ввода вывода вы знаете?

2. Объясните разницу между операцией > и >>.

3. Что такое конвейер?

4. Что такое процесс? Чем это понятие отличается от программы?

5. Что такое PID и GID?

6. Что такое задачи и какая команда позволяет ими управлять?

7. Найдите информацию об утилитах top и htop. Каковы их функции?

8. Назовите и дайте характеристику команде поиска файлов. Приведите примеры использования этой команды.

9. Можно ли по контексту (содержанию) найти файл? Если да, то как?

10. Как определить объем свободной памяти на жёстком диске?

11. Как определить объем вашего домашнего каталога?

12. Как удалить зависший процесс?

## Цитатка

У каждого своя жизнь

но game over у всех один.







