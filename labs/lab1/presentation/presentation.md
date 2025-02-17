---
## Front matter
lang: ru-RU
title: Лабораторная работа №1
subtitle: Установка и конфигурация операционной системы на виртуальную машину
author:
  - Карпова Е.А.
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Объединённый институт ядерных исследований, Дубна, Россия
date: 15.02.2025

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

---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Карпова Есения Алексеевна
  * Студентка НКАбд-02-23
  * ФФМиЕН
  * Российский университет дружбы народов
  * [1132236008@pfur.ru](mailto:1132236008@pfur.ru)
  * <https://github.com/eakarpova>

:::
::: {.column width="30%"}

![](image/me.jpeg)

:::
::::::::::::::


# Вводная часть

## Цели и задачи

- Приобрести практические навыки установки операционной системы на ВМ
- Настройки минимально необходимых сервисов
- Выполнение домашней работы


# Установка и настройка виртуальной машины

## Создание виртуальной машины

![](image/1.png)

## Задание настроек ВМ

![](image/2.png)

## Окно с созданной ВМ

![](image/3.png)

## Добавление образа ОС

![](image/4.png)

## Окно настроек ОС

![](image/6.png)

## Место установки ОС]

![](image/7.png)

## Выбор программ

![](image/8.png)

## Образ диска дополнений

![](image/10.png)

## Загрузка дополнений

![](image/11.png)

# Домашнее задание

## Версия ядра Linux

![dsmeg](image/12.png)


## Частота процессора

![dmesg | grep -i "mhz processor"](image/13.png)


## Модель процессора

![dmesg | grep -i "cpu"](image/14.png)

## Объем ОП

![dmesg | grep -i "memory"](image/15.png)

## Тип файловой системы и гипервизора

![](image/16.png)


## Результаты

В ходе лабораторной работы я приобрела практические навыки установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов
