![year][0] ![status][1] ![progress][2]

# Управление требованиями и проектирование ИС
*ВШЭ ВШБ БИ, 1 модуль 2021/2022*

**Канал с объявлениями по курсу: https://t.me/utipis2021**

**[Таблица с баллами](https://docs.google.com/spreadsheets/d/1b8eMGlg6PsapQc-Gp74CGsBrqPbVUEcrjGI2qcJR0RE/edit?usp=sharing)**

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

> [UML Cheat Sheet](https://www.guru99.com/uml-cheatsheet-reference-guide.html)

### [Лекция 6](https://github.com/demist/is_design/blob/main/lecture6.pdf)

- :white_check_mark: Описание сложных процессов и взаимодействий
- :white_check_mark: Диграмма последовательности
- :white_check_mark: Диаграмма состояний
- :white_check_mark: Диаграмма деятельности


### [Лекция 7](https://github.com/demist/is_design/blob/main/lecture7.pdf)

Методологии функционального моделирования
- :white_check_mark: DFD (*Data Flow Diagrams*)
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
- :white_check_mark: IDEF0
    - Общее понятие и основные термины
    - Базовые принципы
    - Основные компоненты
        - Функциональный блок
        - Интерфейсная дуга
        - Декомпозиция
        - Нумерация работ и диаграмм
        - Связи
        - Глоссарий


> [Методология RAD](http://citforum.ru/database/case/glava1_3_2.shtml)

### [Лекция 8](https://github.com/demist/is_design/blob/main/lecture8.pdf)

- :white_check_mark: Понятие о проектировании и архитектуре
- :white_check_mark: Критерии оценки архитектуры системы
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
- :white_check_mark: Классификация архитектуры ПО
- :white_check_mark: Архитектура локальных приложений
    - MVC (*Model-View-Controller*)
- :white_check_mark: Клиент-серверная архитектура
    - Понятие о тонком и толстом клиентах
    - Трехзвенная архитектура

> [Очень качественный ресурс про паттерны проектирования](https://refactoring.guru/ru/design-patterns/catalog)

### Лекция 9 

:white_check_mark: *Лекция №9 уйдет на написание лекционной контрольной работы*


### [Лекция 10](https://github.com/demist/is_design/blob/main/lecture10.pdf)

:white_check_mark: *Разбор контрольной*
- Общие итоги
- Самые сложные вопросы
    - Объяснение самых "тяжелых вопросов"

*Собственно, лекция*

- :white_check_mark: Как считать нагрузку?
- :white_check_mark: Тип проекта и влияние на нагрузку
- :white_check_mark: Ресурсы для обеспечения производительности
- :white_check_mark: Масштабирование
    - Горизонтальное
    - Вертикальное
    - Функциональное разбиение
    - Шардинг
- :white_check_mark: Типичная архитектура веб-сервиса
- :white_check_mark: Типичная архитектура нагруженной ИС

### [Лекция 11](https://github.com/demist/is_design/blob/main/lecture11.pdf)

- :white_check_mark: Общий план технического задания
- :white_check_mark: Общие сведения
- :white_check_mark: Назначение и цели создания (развития) системы
- :white_check_mark: Характеристики объектов автоматизации
- :white_check_mark: Требования к системе
    - Требования к системе в целом
        - Требования к структуре и функционированию системы
        - Требования к численности и квалификации персонала системы и режима его работы
        - Показатели назначения
        - Требования к надежности
        - Требования безопасности
        - Требования к эргономике и технической эстетике
        - Требования к транспортабельности для АС
        - Требования к эксплуатации, техническому обслуживанию, ремонту и хранению компонентов системы
        - Требования к защите информации от несанкционированного доступа
        - Требования по сохранности информации при авариях
        - Требования к защите от влияния внешних воздействий
        - Требования к патентной чистоте
        - Требования по стандартизации и унификации
        - Дополнительные требования
    - Требования к функциям (задачам), выполняемым системой
    - Требования к видам обеспечения
        - Математическое обеспечение
        - Информационное обеспечение
        - Лингвистическое обеспечение
        - Программное обеспечение
        - Техническое обеспечение
        - Метрологическое обеспечение
        - Организационное обеспечение
        - Методическое обеспечение
- :white_check_mark: Состав и содержание работ по созданию системы
- :white_check_mark: Порядок контроля и приемки системы
- :white_check_mark: Требования к составу и содержанию работ по подготовке объекта автоматизации к вводу системы в действие
- :white_check_mark: Требования к документированию
- :white_check_mark: Источники разработки

> [ГОСТ 19.201-78](https://www.prj-exp.ru/gost/gost_19-201-78.php)

> [ГОСТ 34.602-89](http://www.rugost.com/index.php?catid=22&id=96:gost-34602-89&Itemid=53&option=com_content&view=article)

### :fire: [Лекция 12](https://github.com/demist/is_design/blob/main/lecture12.pdf)

- Способы организации работы с данными
    - OLTP
    - OLAP
- Понятие о транзакции
- ACID
    - Atomicity
    - Consistency
    - Isolation
    - Durability
- CAP-теорема\*
- Реляционные базы данных
    - Реляционная модель данных
    - Примеры реляционных СУБД
    - ORM
- NoSQL БД
    - Общая идея
    - BASE
        - Basic Availability
        - Soft State
        - Eventual Consistency
    - Типы NoSQL-систем

*\* - дополнительная тема, не войдет в программу экзамена*

### :fire: [Лекция 13](https://github.com/demist/is_design/blob/main/lecture13.pdf)

- Принципы SOLID
    - **S**ingle responsibility principle
    - **O**pen-closed principle
    - **L**iskov substitutional principle
    - **I**nterface segregation principle
    - **D**ependency inversion principle
- Закон Деметры
- YAGNI
- DRY / DIE
- KISS

> [Лекция Роберта *Uncle Bob* Мартина  про SOLID](https://www.youtube.com/watch?v=zHiWqnTWsn4)

### Лекция 14

- Понятие о тестировании
- Роль описания тестирования в подготовке задания на разработку
- Различные типы тестирования
- Приемо-сдаточное тестирование
- Понятие об управлении качеством ПО
- Понятие внутреннего и внешнего качества
- Связь качества и процессов проектирования и разработки
- 7 инструментов качества

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

### :white_check_mark: Лекционная контрольная работа (ЛКР)

- **Пройдет 25 сентября на лекции в 18:10**
- Продолжительность - 50 минут
- Максимальный балл за работу - 40 первичных. **Оценка ЛКР = (Первичные баллы) / 4** (без округления)
- Формат - дистанционный тест на базе *Google Forms*, свои результаты вы узнаете сразу по итогам выполнения
- Вопросы будут только по материалам лекций *№1 - №8*

### :white_check_mark: Задание на диаграмму вариантов использования (ЗВИ)

Давайте представим, что данный репозиторий на github'е по нашему курсу и канал по курсу в telegram - не репозиторий и канал вовсе, а некоторая информационная система.
И для этой системы вам необходимо: 
- Выделить акторов
- Выделить варианты использования
- Составить диаграмму вариантов использования

*Составлять диаграммы можно в любом удобном для вас ПО или с помощью любого веб-сервиса. Мы предлагаем два варианта: [draw.io](https://app.diagrams.net/), [Miro](https://miro.com/)*

Для сдачи задания отправьте файл с диаграммой в любом из форматов *pdf/jpeg/png* на электронную почту вашего семинариста.

**Обязательно** укажите тему письма в формате "УТиПИС_ЗВИ_ФАМИЛИЯ_ГРУППА" (например, *УТиПИС_ЗВИ_ИВАНОВ_112*)

**:end: Дедлайн** *(если у вашей группы семинар по диаграммам вариантов использования уже прошел)*: **26/09/2021 23:59**

**:fire: Дедлайн** *(если у вашей группы семинар по диаграммам вариантов использования еще не прошел)*: **03/10/2021 23:59**

### :fire: Задание на диаграмму деятельности / последовательности (ЗДД)

Давайте снова представим, что данный репозиторий на github'е по нашему курсу и канал по курсу в telegram - не репозиторий и канал вовсе, а некоторая програмная система.
И для этой системы вам необходимо: 
- Для сценария "Объявить студентам о новом техническом задании" составить диаграмму последовательности. *Диаграмма должна быть адекватна и позволять восстановить сценарий без дополнительных уточнений в стиле "ну тут понятно" / "голосом объясню". Минимум у вас должно получиться 5 отдельных действий. Учитывайте, что текст задания готовит лектор, публикует его и делает об этом объявление, отправляет задание для ознакомления семинаристам, далее на лекции опционально может ответить на вопросы студентов*

**Обязательно** укажите тему письма в формате "УТиПИС_ЗДД_ФАМИЛИЯ_ГРУППА" (например, *УТиПИС_ЗДД_ИВАНОВ_112*)

**:fire: Дедлайн** *(если у вашей группы семинар по диаграммам деятельности / последовательности уже прошел)*: **03/10/2021 23:59**

**:fire: Дедлайн** *(если у вашей группы семинар по диаграммам деятельности / последовательности еще не прошел)*: **10/10/2021 23:59**

### :fire: Командный (3-5 человек) проект на написание ТЗ (ПрТЗ)

*Задание выполняется командами по 3-5 человек. Делитесь на команды по своему желанию, однако все участники должны быть из одной группы (т.к. защищать вам проект вместе)*

Вам необходимо разработать **техническое задание (ТЗ)** на разработку ИС для автоматизации учебной деятельности по нашему курсу. 
**ТЗ** оформляется в текстовом виде, в формате *doc/docx/pdf*, строгое соблюдение правил оформления согласно ГОСТу не требуется. 
Ваше **ТЗ** в обязательном порядке должно включать в себя следующие пункты (*обратите внимание, не все пункты из ГОСТа нужны*):
- Общие сведения
- Назначение и цели создания системы
- Требования к системе
    - Требования к системе в целом
        - Требования к структуре и функционированию системы
    - Требования к функциям (задачам), выполняемым системой
    - Требования к видам обеспечения
        - Информационное обеспечение
        - Программное обеспечение
- Состав и содержание работ по созданию системы

*Всего у вас должно получиться порядка 7-10 страниц*

Также вам будет необходимо защитить свою работу - подготовив **презентацию**. 
Презентовать вы будете перед своими одногруппниками на семинара. Подготовьте презентацию на 7-10 минут.
Будьте готовы отвечать на вопросы преподавателя и своих одногруппниках. 
В презентации в **обязательном порядке** отразите следующие элементы:
- Состав команды (Фамилия-Имя всех участников) (*1 слайд*)
- Назначение и цели создания системы (*1 слайд*)
- Основные функциональные блоки (*2-3 слайда*)
    - Отразите ключевые функциональные возможности из **ТЗ**
- Требования к информационному обеспечению (*1 слайд*)
- Требования к программному обеспечению (*1 слайд*)
- План работ по созданию системы (*1 слайд*)
*Всего 7-8 слайдов* 

**Обязательно** укажите тему письма в формате "УТиПИС_ПрТЗ_ФАМИЛИЯ_ГРУППА" (например, *УТиПИС_ПрТЗ_ИВАНОВ_112*)

**:fire: Дедлайн**: *заранее присылаете ваше **ТЗ** семинаристу (каждый семинарист сам устанавливает срок в зависимости от вашего графика), далее на последнем семинаре курса защищаете свою работу (рассказываете презентацию)*

### Письменный экзамен (ЭКЗ)

:fire: **Пройдет онлайн 19 октября в 11:10 - 12:30**, *подробности позже*

## Правила оценивания 

*Оценка* = Округление (0,2\**ЛКР* + 0,3\**ЭКЗ* + 0,1\**ЗВИ* + 0,1\**ЗДД* + 0,3\**ПрТЗ*)

[0]:https://img.shields.io/badge/year-2021%2F2022-blue
[1]:https://img.shields.io/badge/status-running-brightgreen
[2]:https://progress-bar.dev/73/