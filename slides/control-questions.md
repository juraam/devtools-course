# Список контрольных вопросов

---------------------

  1. [Инструменты разработки](#intro)
  1. [Системы контроля версий](#vcs)
  1. [Коллективная разработка](#teamwork)
  1. [Дополнительные вопросы](#extra-questions)
  1. [Текстовые форматы](#text)
  1. [Обработка текста](#text-processing)
  1. [Автоматизация](#automation)
  1. [Создание проектов](#projects)
  1. [Тестирование](#testing)
  1. [Непрерывная интеграция](#continuous-integration)
  1. [Анализ бинарных модулей](#binary-module-analysis)
  1. [Отладка с помощью GDB](#debug)

---------------------

<a name="intro"/>
## 1. Инструменты разработки

  1. Общее назначение инструментов, примеры.
  1. Признаки "хороших" инструментов, с пояснениями.
  1. Примеры практик Программной инженерии, их суть.
  1. Приведите примеры инструментов, помогающих применять практики.
  1. Диаграмма каскадной модели жизненного цикла.
  1. Диаграмма работы программиста над задачей.

<a name="vcs"/>
## 2. Системы контроля версий

  1. Определение СКВ
  1. Основные функции/возможности современных СКВ
  1. Преимущества DVCS

<a name="teamwork"/>
## 3. Коллективная разработка

  1. Centralized Workflow (диаграмма, достоинства и недостатки)
  1. Integration Manager Workflow (диаграмма, достоинства и недостатки)
  1. Dictator and Lieutenants Workflow (диаграмма, достоинства и недостатки)
  1. Модель ветвления GitFlow
  1. Рабочий процесс (модель ветвления), используемый в компании GitHub
  1. Базовые принципы корректной работы с СКВ
  1. Простые истины планирования
  1. Практические рекомендации при учете задач (issue tracking)

<a name="extra-questions"/>
## 11. Дополнительные вопросы

  1. Написать регулярные выражения для
     1. Времени в американском формате (9:00 AM, но не 19:77 AM)
     1. Номеров мобильных телефонов в России
     1. Веб-адресов
  1. Сравнительный анализ интерфейсов командной строки и графического
  1. Какие будут негативные последствия при:
     1. Нарушении базовых принципов работы с VCS
     1. Недостаточном использовании автоматизации в проекте
     1. Тестировании без использования соответствующих фреймворков
     1. Отсутствии практики непрерывной интеграции
  1. Какие полезные следствия имеет то, что Travis (CMake, GTest) является
     популярным инструментом
  1. Почему важно поддерживать бинарную (на уровне исходников) совместимость
     API, в каких случаях допустимо ее нарушать? (см. <http://semver.org/lang/ru/>)
<a name="text"/>
## 92. Текстовые форматы

  1. Преимущества простого текста
  1. Преимущества бинарного формата
  1. Примеры ситуаций, когда удобно использовать TXT, XML, YAML, JSON
  1. Синтаксис Markdown (заголовки, стили, списки, ссылки)
  1. Примеры использования Markdown, в том числе нестандартные. В чем конкретно
     преимущество использования Markdown.

<a name="text-processing"/>
## 93. Обработка текста

  1. Как будет выглядет команда в Vim для:
     - Создания 10 копий текущей строки
     - Перевода всей строки в верхний регистр (капитализация)
  1. Предложите регулярное выражение для поиска:
     - Имен всех классов в вашем С++ проекте
     - Поиска дат в формате `2013-09-18` или `14-01-01`
     - IP-адресов, номеров банковских карт, HEX-представления чисел типа `int`
  1. Предложите командную строку для:
     - Поиска всех вызовов виртуального метода в директории с исходниками
     - Печати всех заголовков первого и второго уровня в файле Markdown (#-нотация)

<a name="automation"/>
## 95. Автоматизация

  1. Какие преимущества дает автоматизация
  2. Типичные классы задач на автоматизацию (в работе программиста)
  3. Философия UNIX
  4. Преимущества UNIX при автоматизации
  5. Суть деятельности профессионального программиста

<a name="projects"/>
## 96. Создание проектов

  1. Определение ИСР
  1. Отличия ИСР от редакторов исходного кода
  1. Основные функции/возможности современных ИСР
  1. Определение метапрограммирования и его примеры
  1. Иcтория развития билд-систем
  1. Плюсы и минусы Makefile
  1. Плюсы и минусы CMake

<a name="testing"/>
## 97. Тестирование

  1. Классификация тестов по назначению.
  1. Современная стратегия тестирования (основные 5 утверждений).
  1. Основные возможности фреймворков модульного тестирования.
  1. Критерии хорошего теста.
  1. Возможности Google Test.
  1. Порядок использования Google Test.

<a name="continuous-integration"/>
## 98. Непрерывная интеграция

  1. Определение непрерывной интеграции
  1. Задачи выделенного сервера
  1. Эволюция взглядов на непрерывную интеграцию
  1. Travis CI, преимущества и недостатки
  1. BuildBot, преимущества и недостатки

<a name="binary-module-analysis"/>
## 99. Анализ бинарных модулей

  1. Определение: Исполняемый модуль
  1. Определение: API
  1. Зачем нужно разделение на сегменты и секции в исполняемых модулях?
  1. Что такое статическое и динамическое связывание, в чём их отличия?
  1. Что такое бинарная совместимость и совместимость на уровне исходного кода?

<a name="debug"/>
## 100. Отладка с помощью GDB

  1. Что такое отладка и отладчик?
  1. Назовите 3 метода отладки и опишите их.
  1. Опишите алгоритм отладки "Волчья ограда" (wolf fence).
  1. Расшифруйте и объясните следующие термины: breakpoint, watchpoint,
     checkpoint, catchpoint и call stack.
  1. Перечислите 3 распространенных приема против отладки.
  1. Объясните назначение отладочной информации и как нужно скомпилировать
     программу, чтобы она была.
  1. Напишите 5 команд отладчика GDB (запуск, поставить точку останова с
     условием, продолжить, распечатать локальные переменные, завершить работу
     отладчика).