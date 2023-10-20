---
## Front matter
lang: ru-RU
title: Лабораторная работа №5
subtitle: Дискреционное разграничение прав в Linux. Исследование влияния дополнительных атрибутов
author:
  - Аникин Константин Сергеевич
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 7 октября 2023

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
::: 

  * Аникин Константин Сергеевич
  * студент
  * просто студент
  * Российский университет дружбы народов
  * [1032201736@rudn.ru](mailto:1032201736@rudn.ru)
  * <https://rituliot.github.io/ru/>

# Вводная часть

## Цель работы

Изучение механизмов изменения идентификаторов, применения SetUID- и Sticky-битов. Получение практических навыков работы в консоли с дополнительными атрибутами. Рассмотрение работы механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов

## Задание

- Разобраться с Sticky и SetUID битами

# Выполнение работы

## Работа с simpleid

Создал программу simpleid (рис. \ref{fig1}).

![simpleid\label{fig1}](image/1.png)

## Работа с simpleid

Скомпилировал и запустил её (рис. \ref{fig2}).

![simpleid\label{fig2}](image/2.png)

## Работа с simpleid2

Создал программу simpleid2 (рис. \ref{fig3}).

![simpleid2\label{fig3}](image/3.png)

## Работа с simpleid2

Скомпилировал и запустил её (рис. \ref{fig4}).

![simpleid2\label{fig4}](image/4.png)

## Работа с readfile

Создал программу readfile (рис. \ref{fig5}).

![readfile\label{fig5}](image/5.png)

## Работа с readfile

Скомпилировал и запустил её (рис. \ref{fig6}).

![readfile\label{fig6}](image/6.png)

## Работа с file01

Создал file01.txt, заполнил его через guest, прочитал через guest2 и изменил содержимое (рис. \ref{fig7}).

![file01\label{fig7}](image/7.png)

## Работа с file01

Изменил Sticky-бит и попытался повторить операции (рис. \ref{fig8}).

![file01\label{fig8}](image/8.png)

# Вывод

Работа выполнена полностью