## Какие бывают языки

Язык может быть высокого или низкого уровня, процедурный или объектно ориентированный, скриптовый или компилируемый.

#### Язык выского уровня ([Википедия](https://ru.wikipedia.org/wiki/%D0%92%D1%8B%D1%81%D0%BE%D0%BA%D0%BE%D1%83%D1%80%D0%BE%D0%B2%D0%BD%D0%B5%D0%B2%D1%8B%D0%B9_%D1%8F%D0%B7%D1%8B%D0%BA_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)):

Легче и быстрее писать код.
Легко обучиться азам, но на полное его изучение все равно уйдет не мало времени. Очень много абстракций.
Используется на очень большом количестве платформ.

Примеры языков: Java, Kotlin, Swift, C#, Python, NodeJs, ReactJs, PHP


#### Язык низкого уровня ([Википедия](https://ru.wikipedia.org/wiki/%D0%9D%D0%B8%D0%B7%D0%BA%D0%BE%D1%83%D1%80%D0%BE%D0%B2%D0%BD%D0%B5%D0%B2%D1%8B%D0%B9_%D1%8F%D0%B7%D1%8B%D0%BA_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)):

Писать код сложнее, часто медленее и труднее.
Программа на языке низкого уровня выполняется быстрее чем на языках высокого уровня, и требует значительно меньше ресурсов.
Довольно сложное обучение.

Примеры языков: С, С++

#### Процедурный язык ([Википедия](https://ru.wikipedia.org/wiki/%D0%9F%D1%80%D0%BE%D1%86%D0%B5%D0%B4%D1%83%D1%80%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)):

Код таких программ рассматривается как выполнение действий в определенной последовательности (процедура, алгоритм).
Чаще всего процедурно пишут, или простые программы, или утилиты, или части систем (например код для сервера)

Примеры языков: С, PHP, JavaScript, NodeJs


#### Объектно ориентированный язык ([Википедия](https://ru.wikipedia.org/wiki/%D0%9E%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BD%D0%BE-%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D1%8B%D0%B9_%D1%8F%D0%B7%D1%8B%D0%BA_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)):

Код таких программ рассматривается как описание взаимоотношений различных объектов и их реакций на изменение. Несколько более сложный подход (по сравнению с процедурным), но зато куда больше возможностей. Обильное использование абстракций для упрощения написания кода.

Примеры языков: Java, Kotlin, Swift, Python, C++, C#, ReactJS, PHP (с натяжкой)

#### Компилируемый язык ([Википедия](https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D0%BC%D0%BF%D0%B8%D0%BB%D0%B8%D1%80%D1%83%D0%B5%D0%BC%D1%8B%D0%B9_%D1%8F%D0%B7%D1%8B%D0%BA_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)):

Для запуска программы на таком языке, сперва нужно ее скомпилировать, т.е. превратить исходный код программы в запись понятную компьютеру. Особенность заключается в том что для компиляции нужен весь код программы и ее частей. Под разные процессоры (x64, x86) исходный код собирается по разному. Саму программу можно представить как один цельный и нераздельный файл.

Примеры языков: Java, Kotlin, Swift, C, C++, C#


#### Скриптовый язык ([Википедия](https://ru.wikipedia.org/wiki/%D0%A1%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%BD%D1%8B%D0%B9_%D1%8F%D0%B7%D1%8B%D0%BA)):

Для запуска такой программы нужен интерпретатор кода, обычно интерпретаторы уже встроены в среду в которой будет выполняться код. Код на таком языке не требует предварительной обработки, и его можно выполнять и передавать по кусочку. Как это например сделано в веб-сайтах, при переходе на новую страницу браузер интерпретирует код этой страницы и выполняет его.

Примеры языков: Python, PHP, JavaScript (все виды NodeJs, ReactJs и т.п.)

##### Комментарий
Я в своей работе использую Kotlin как основной язык, это компилируемый, объектно ориентированный язык высокого уровня.


------------------------------------------------------------

## Кто чем занимается, по платформам

#### Мобайл (Mobile)
Мобильные телефоны, устройства на операционной системе Android и iOS. 

* Под Android пишут на Kotlin (раньше писали на Java). 
* Под iOS пишут на Swift (раньше писали на ObjectiveC).
* Под обе платформы можно писать на Xamarin (производная от C#) или ReactNative. Но храни тебя господь если решишься этим заниматься.

#### Десктоп (Desktop) 
Стационарные компьютеры и ноутбуки, устройства на операционной системе Windows, Linux, MacOS.

На всех декстопных операционках можно писать на Java\Kotlin. Но сейчас их используют довольно редко. Чаще используют C++, C#, Python.

* Для Windows так же используется фреймворк .Net
* Для Linux надо знать особенности Unix
* Для MacOS хз что, но что-то есть точно. Не разбираюсь в них особо.

#### Эмбеддед (Embedded) 
Микроконтроллеры и различные самостоятельные устройства (чаще на Linux, но могут бы и на других или вообще без операционной системы)

Используют чаще всего C и C++. А так же специализированные фреймворки и средства предоставляемые производителями плат и операционных систем, они бывают очень разные.

#### Бекенд (Backend) 
Часть системы работающая без графического интерфейса. Очень часто под бекендом понимают создание серверной части веб-сайтов и базы данных.

Касательно работы серверных приложений (программ которые выполняются на удаленном компьютере и выполняющему задачи по запросам), то чаще всего используются такие языки как: PHP, NodeJs. Бывают и сервера на Java и Kotlin, но значительно реже.

Касательно баз данных используют реляционные (см. википедию) такие как MySQL, PostgeSQL; И нереляционные такие как MongoDB. Каждая имеет свои особенности, но в целом они выполняют одни и те же функции.

#### Форнтенд (Frontend) 
Часть системы работающая в основном отвечающая за графический интерфейс. Очень часто под фронтендом понимают создание 
части веб-сайтов выполняемой в браузере. Основная работа идет с отображением данных в браузере.

Относительно веб-сайтов выделяют две категории фронтендеров:
1. Верстальщик - занимается только отображением контента в окне браузера и переходами между страницами. Для верстки страниц используются HTML, JS (JavaScript, NodeJs, ReactJs и т.п.), CSS (SASS, LESS). Код пишет, но довольно мало. Больше занимается настройкой и выставлением параметров.
2. Полноценный фронт - Делает то же что и верстальщик, но так же и занимается написанием исполняемых функций. Тут уже есть настоящее программирование, реализация алгоритмов, выполнение обработок и операций. Используются скриптовые языки JS (JavaScript, NodeJs, ReactJs и т.п.), но уже более профессионально.

##### Комментарий 1
При этом каждая платформа имеет свои [фреймворки](https://ru.wikipedia.org/wiki/%D0%A4%D1%80%D0%B5%D0%B9%D0%BC%D0%B2%D0%BE%D1%80%D0%BA), часто даже несколько, каждая для своей задачи. Фреймворк это по сути другая программа которая включается в ту программу которую ты пишешь, она уже содержит код посредством которого идет работа с определенными данными или объектами.

Например я на Android использую фреймфорк Android Framework (да-да, так и называется) для обращения к операционной системе. Фреймворк Retrofit для отправки http-запросов. Фреймворк Room для работы с внутренней базой данных. Фреймворк Glide для загрузки и отображения изображений. И много других.

##### Комментарий 2
Иногда разработчик может совмещать некоторые виды работ. Например разработчик который создает веб-сайт и браузерную его часть и серверную называется фулстек (Fullstack). Или например я создавая приложение под Android участвую сразу в трех категориях: Mobile, так как приложение на телефон. Backend так как приложение очень часто использует внутренюю реляционную базу данных SQLite. И как Frontend, так как верстки страниц приложения используется тот же подход что для верстки сайтов, хотя и с другими инструментами (Android Framework).

------------------------------------------------------------

