# Управление требованиями и проектирование ИС
ВШЭ ВШБ БИ, 1 модуль 2021/2022

## Аннотация

Курс посвящен вопросам проектирования информационных систем. Рассматриваются вопросы сбора и управления требованиями, методики и подходы организации процессов проектирования, а также типовые паттерны реализации информационных систем и их взаимодействий. В рамках практических занятий ведется отработка навыков проектирования ПО с использованием UML.

## План лекций

### Лекция 0

- Общая информация по курсу
    - План лекций
    - План семинаров
    - Зачем вообще этот курс нужен
- Система оценивания
- Введение

### Лекция 1

- Базовые понятия 
- Сбор, выявление и анализ требований

### Лекция 2

- Управление требованиями
    - Атрибуты требований
    - Приоритезация 
- Управление изменениями


### Лекция 3

- Этапы жизненного цикла проектирования, реализации и внедрения ПО
- Варианты поставки и развертывания

### Лекция 4

- Роль анализа и управления требованиями в процессе разработки
- Интеграция работы с требованиями в методологии разработки ПО

### Лекция 5

- Варианты использования
- Понятие об акторах
- Выделение вариантов использования
    - Карточки CRC
    - Метод Аббота

### Лекция 6

- Описание сложных процессов и взаимодействий
- Диаграммы деятельности, последовательности

### Лекция 7

- Методологии проектирования ПО
    - SADT
    - RAD
    - SUP

### Лекция 8

- Классификация архитектуры ИС
- Базовые типы архитектур
- Архитектура десктопных приложений
- Понятие о тонком и толстом клиентах

### Лекция 9 

- Архитектура бекэнда клиент-серверных приложений
- Управление нагрузкой и распределенные системы
- Понятие о масштабировании
- Базовые архитектурные паттерны

### Лекция 10

- Подходы к хранению данных
- Хранилища данных
- Реляционные и нереляционные базы данных
- Распределенные хранилища, репликации

### Лекция 11

- Интеграция ИС в ИТ-ландшафт предприятия
- Интеграции с внешними системами
- Системы класса ESB

### Лекция 12

- Подготовка *Технического задания* на разработку ИС
- Основные разделы *Технического задания*

### Лекция 13

- Понятие о тестировании
- Роль описания тестирования в подготовке задания на разработку
- Различные типы тестирования
- Приемо-сдаточное тестирование

### Лекция 14

- Понятие об управлении качеством ПО
- Понятие внутреннего и внешнего качества
- Связь качества и процессов проектирования и разработки

### Лекция 15

- Обеспечение безопасности ИС
- Различные подходы организации контроля доступа
- Роли и права доступа
- Уровни доступа
- Блокировка доступа на уровне таблиц
- Блокировка доступа на уровне записей

## План семинаров

*При работах на семинаре предлагается использовать любой доступный и простой сервис для построения диаграмм. Например, draw.io (https://app.diagrams.net/). Либо любой другой на усмотрение семинариста. Лучше отдавать предпочтение простым инструментам, чтобы сконцентрировать внимание студентов на том, **что именно** они рисуют, а не **как именно** они это рисуют*.

*Учитывая, что у студентов есть отдельные дисциплины, где учат нотациям (UML, BPMN, IDEF), лучше ставить акценты в рамках данного курса на вопросы проектирования, а не следования нотациям.*

### Семинар 1

**Проектная игра**: выделение требований к простой ИС (например, для парковки).

*Сначала берем какую-то простую ИС и описываем для нее основные требования - чтобы показать пример. Далее делим студентов на команды по 5-6 человек. Описываем словами простую и понятную для них жизненную ситуацию: платная парковка, столовая в университете, покупка и оформление сим-карты, получение стипендии и т.п., и просим студентов текстом написать функциональные и нефункциональные требования к ИС, с помощью которой можно было бы этот процесс автоматизировать. Даем на это 20-30 минут, попутно отвечая на вопросы студентов, потом просим 2-3 команды презентовать свои решения. Обсуждаем с другими студентами правильные решения и ошибки*

### Семинар 2

Практика выделения акторов и вариантов использования. Отработка навыков формирования use-case диаграмм.

*Для начала берем некоторый простой пример (можно взять ту же ИС, на примере которой в Семинаре №1 Вы описывали требования). Выделяем акторов, подчеркиваем, что акторы - это **роли**, а не конкретные пользователи, показываем, что один человек в разные моменты может играть разных акторов; показываем, что актором может выступать и внешняя ИС. Выделяем ВИ, рисуем use-case диаграмму из UML. Разбираем еще один пример, посложнее, чтобы показать **include** и **extend** для ВИ. Далее предлагаем студентам попробовать самостоятельно построить диаграмму ВИ для той системы, для которой они выделяли требования на Семинаре №1 (даем на это 5-10 минут), потом просим 1-2 студентов показать свои решения, обсуждаем, объясняем ошибки*

### Семинар 3

Практика описания сложных процессов. Диаграммы деятельности и последовательности.

*Для начала снова берем некоторый простой пример (например, "процесс покупки сим-карты", "процесс получения автомобильных прав") и показываем диаграмму деятельности. Добавляем передачу данных между этапами: показываем соответствующий пример (например, "процесс обработки изображения от помех/лишних деталей/красных глаз/фильтр и т.п."). Показываем пример взаимодействия нескольких объектов, иллюстрируя это диаграммой последовательности (например, "процесс покупки автомобиля в кредит и оформления страховки на него"). Далее предлагаем ребятам описать ключевые процессы для ИС с Семинара №1 с помощью диаграммы деятельности / последовательности. Просим 1-2 студентов показать свои решения, обсуждаем, объясняем ошибки*

### Семинар 4

Проектирование ПО. Отработка навыка проектирования.

**Проектная игра**: проектируем простую ИС (например, для парковки).

### Семинар 5

Практика формирование ТЗ. Защита заданий.


## Контрольные мероприятия

- **Лекционная контрольная работа (ЛКР)**
- **Задание на диаграмму вариантов использования (ЗВИ)**
- **Задание на диаграмму деятельности / последовательности (ЗДД)**
- **Командный (3-5 человек) проект на написание ТЗ (ПрТЗ)**
- **Пиьсменный экзамен (ЭКЗ)**

## Правила оценивания 

*Оценка* = Округление (0,2\**ЛКР* + 0,3\**ЭКЗ* + 0,1\**ЗВИ* + 0,1\**ЗДД* + 0,3\**ПрТЗ*)