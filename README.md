![year][0] ![status][1] ![progress][2]

# Управление требованиями и проектирование ИС
*ВШЭ ВШБ БИ, 1 модуль 2021/2022*

**Канал с объявлениями по курсу: https://t.me/utipis2021**

## Аннотация

Курс посвящен вопросам проектирования информационных систем. Рассматриваются вопросы сбора и управления требованиями, методики и подходы организации процессов проектирования, а также типовые паттерны реализации информационных систем и их взаимодействий. В рамках практических занятий ведется отработка навыков проектирования ПО с использованием UML.

## План лекций

### [Лекция 0](https://github.com/demist/is_design/blob/main/lecture0.pdf)

- :white_check_mark: Общая информация по курсу
    - Зачем вообще этот курс нужен
    - План лекций
    - План семинаров
    - Система оценивания

### [Лекция 1](https://github.com/demist/is_design/blob/main/lecture1.pdf)

- :white_check_mark: Базовые понятия 
- :white_check_mark: Сбор, выявление и анализ требований

### [Лекция 2](https://github.com/demist/is_design/blob/main/lecture2.pdf)

- :white_check_mark: Управление требованиями
    - Атрибуты требований
    - Приоритезация 
- :white_check_mark: Управление изменениями


### [Лекция 3](https://github.com/demist/is_design/blob/main/lecture3.pdf)

- :white_check_mark: Понятие об информационной системе
- :white_check_mark: Этапы жизненного цикла проектирования, реализации и внедрения ПО
    - Формирование требований
    - Разработка концепции
    - Техническое задание
    - Эскизный проект
        - Понятие о MVP и примеры MVP
    - Технический проект
    - Рабочая документация
    - Поставка / ввод в действие
        - Варианты поставки и развертывания
    - Сопровождение 
    - Сопровождение ИС

### [Лекция 4](https://github.com/demist/is_design/blob/main/lecture4.pdf)

- :white_check_mark: Роль анализа и управления требованиями в процессе разработки
- :white_check_mark: Интеграция работы с требованиями в методологии разработки ПО
- :white_check_mark: Обзор основных методологий разработки ПО
    - Каскадная модель
    - V-модель
    - Инкрементная модель
    - Итерационная модель
    - Спиральная модель
    - RAD-модель
    - Семейство гибких методологий
        - Scrum
        - Kanban 

> *Не предполагается глубокое погружение в сами методологии разработки ПО, предполагается, что слушатели уже знают про них и знают, как они устроены. Если же нет - придется хотя бы "по верхам" рассказывать.*

### [Лекция 5](https://github.com/demist/is_design/blob/main/lecture5.pdf)

- :white_check_mark: Варианты использования
- :white_check_mark: Понятие об акторах
- :white_check_mark: UML / базовые понятия
- :white_check_mark: Диаграмма вариантов использования
- :white_check_mark: Классы
- :white_check_mark: Диаграмма классов
- :white_check_mark: Выделение сущностей
    - Карточки CRC
    - Метод Аббота

### [Лекция 6](https://github.com/demist/is_design/blob/main/lecture6.pdf)

- :white_check_mark: Описание сложных процессов и взаимодействий
- :white_check_mark: Диграмма последовательности
- :white_check_mark: Диаграмма состояний
- :white_check_mark: Диаграмма деятельности


### :fire: [Лекция 7](https://github.com/demist/is_design/blob/main/lecture7.pdf)

Методологии функционального моделирования
- DFD (*Data Flow Diagrams*)
    - Определение и функциональное назначение
    - Основные компоненты
        - Ремарка про нотации
        - Внешняя сущность
        - Система и подсистема
        - Процесс
        - Накопитель данных
        - Поток данных
    - Нумерация объектов
    - Иерархия DFD
        - Уровень системы / подсистемы
        - Уровень процесса
- IDEF0
    - Общее понятие и основные термины
    - Базовые принципы
    - Основные компоненты
        - Функциональный блок
        - Интерфейсная дуга
        - Декомпозиция
        - Нумерация работ и диаграмм
        - Связи
        - Глоссарий


> **#bookmark**: [методология RAD](http://citforum.ru/database/case/glava1_3_2.shtml)

### :fire: [Лекция 8](https://github.com/demist/is_design/blob/main/lecture8.pdf)

- Понятие о проектировании и архитектуре
- Критерии оценки архитектуры системы
    - Критерии хорошей архитектуры
        - Эффективность системы
        - Гибкость системы
        - Расширяемость системы
        - Дополнительные критерии
            - Масштабируемость процесса разработки
            - Тестируемость
            - Возможность повторного использования
            - Сопровождаемость 
    - Критерии неудачной архитектуры
        - Жесткость
        - Хрупкость
        - Неподвижность
- Классификация архитектуры ПО
- Архитектура локальных приложений
    - MVC (*Model-View-Controller*)
- Клиент-серверная архитектура
    - Понятие о тонком и толстом клиентах
    - Трехзвенная архитектура

> **#bookmark**: [очень качественный ресурс про паттерны проектирования](https://refactoring.guru/ru/design-patterns/catalog)

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

*При работах на семинаре предлагается использовать любой доступный и простой сервис для построения диаграмм. Например, [draw.io](https://app.diagrams.net/). Либо любой другой на усмотрение семинариста. Лучше отдавать предпочтение простым инструментам, чтобы сконцентрировать внимание студентов на том, **что именно** они рисуют, а не **как именно** они это рисуют*.

*Учитывая, что у студентов есть отдельные дисциплины, где учат нотациям (UML, BPMN, IDEF), лучше ставить акценты в рамках данного курса на вопросы проектирования, а не следования нотациям.*

### Семинар 1

**Проектная игра**: выделение требований к простой ИС (например, для парковки).

*Сначала берем какую-то простую ИС и описываем для нее основные требования - чтобы показать пример. Далее делим студентов на команды по 5-6 человек. Описываем словами простую и понятную для них жизненную ситуацию: платная парковка, столовая в университете, покупка и оформление сим-карты, получение стипендии и т.п., и просим студентов текстом написать функциональные и нефункциональные требования к ИС, с помощью которой можно было бы этот процесс автоматизировать. Даем на это 20-30 минут, попутно отвечая на вопросы студентов, потом просим 2-3 команды презентовать свои решения. Обсуждаем с другими студентами правильные решения и ошибки.*

### Семинар 2

Практика выделения акторов и вариантов использования. Отработка навыков формирования use-case диаграмм.

*Для начала берем некоторый простой пример (можно взять ту же ИС, на примере которой в Семинаре №1 Вы описывали требования). Выделяем акторов, подчеркиваем, что акторы - это **роли**, а не конкретные пользователи, показываем, что один человек в разные моменты может играть разных акторов; показываем, что актором может выступать и внешняя ИС. Выделяем ВИ, рисуем use-case диаграмму из UML. Разбираем еще один пример, посложнее, чтобы показать **include** и **extend** для ВИ. Далее предлагаем студентам попробовать самостоятельно построить диаграмму ВИ для той системы, для которой они выделяли требования на Семинаре №1 (даем на это 5-10 минут), потом просим 1-2 студентов показать свои решения, обсуждаем, объясняем ошибки.*

### Семинар 3

Практика описания сложных процессов. Диаграммы деятельности и последовательности.

*Для начала снова берем некоторый простой пример (например, "процесс покупки сим-карты", "процесс получения автомобильных прав") и показываем диаграмму деятельности. Добавляем передачу данных между этапами: показываем соответствующий пример (например, "процесс обработки изображения от помех/лишних деталей/красных глаз/фильтр и т.п."). Показываем пример взаимодействия нескольких объектов, иллюстрируя это диаграммой последовательности (например, "процесс покупки автомобиля в кредит и оформления страховки на него"). Далее предлагаем ребятам описать ключевые процессы для ИС с Семинара №1 с помощью диаграммы деятельности / последовательности. Просим 1-2 студентов показать свои решения, обсуждаем, объясняем ошибки.*

### Семинар 4

Проектирование ПО. Отработка навыка проектирования.

*Показываем диаграмму классов / подсистем. Показываем на примере (можно на примере с Семинара №1) проектирование системы. Дальше на нескольких примерах (можно взять примеры с Семинара №2 или №3) отрабатываем навыки, вызывая студентов "к доске" с задачей спроектировать ту или иную систему. Призываем аудиторию к активности, чтобы к процессу проектирования подключилось как можно больше слушателей. Обсуждаем и объясняем недостатки и ошибки при проектировании.*

### Семинар 5

Практика формирование ТЗ. Защита заданий.

*На лекции студенты получат задание разбиться на команды и подготовить ТЗ в группах по 5-6 человек для любой ИС на их выбор. На семинаре каждая группа студентов коротко (5-10 минут) презентует свою работу, другие студенты задают вопросы. При необходимости, объясняем недостатки и пути их исправления.*


## Контрольные мероприятия

### :fire: Лекционная контрольная работа (ЛКР)

- **Пройдет 25 сентября на лекции в 18:10**
- Ориентировочная продолжительность - 60 минут (*подробности будут позже, когда задание будет полностью составлено*). 
- Формат - дистанционный тест на базе *Google Forms*, свои результаты вы узнаете сразу по итогам выполнения
- Вопросы будут только по материалам лекций *№1 - №8*

### :fire: Задание на диаграмму вариантов использования (ЗВИ)

Давайте представим, что данный репозиторий на github'е по нашему курсу и канал по курсу в telegram - не репозиторий и канал вовсе, а некоторая информационная система.
И для этой системы вам необходимо: 
- Выделить акторов
- Выделить варианты использования
- Составить диаграмму вариантов использования

*Составлять диаграммы можно в любом удобном для вас ПО или с помощью любого веб-сервиса. Мы предлагаем два варианта: [draw.io](https://app.diagrams.net/), [Miro](https://miro.com/)*

Для сдачи задания отправьте файл с диаграммой в любом из форматов *pdf/jpeg/png* на электронную почту вашего семинариста.

**Обязательно** укажите тему письма в формате "УТиПИС_ЗВИ_ФАМИЛИЯ_ГРУППА" (например, *УТиПИС_ЗВИ_ИВАНОВ_112*)

**:fire: Дедлайн (если у вашей группы семинар по диаграммам вариантов использования уже прошел: 26/09/2021 23:59**

**:fire: Дедлайн (если у вашей группы семинар по диаграммам вариантов использования еще не прошел: 03/10/2021 23:59**

### Задание на диаграмму деятельности / последовательности (ЗДД)
### Командный (3-5 человек) проект на написание ТЗ (ПрТЗ)
### Письменный экзамен (ЭКЗ)

## Правила оценивания 

*Оценка* = Округление (0,2\**ЛКР* + 0,3\**ЭКЗ* + 0,1\**ЗВИ* + 0,1\**ЗДД* + 0,3\**ПрТЗ*)

[0]:https://img.shields.io/badge/year-2021%2F2022-blue
[1]:https://img.shields.io/badge/status-running-brightgreen
[2]:https://progress-bar.dev/40/