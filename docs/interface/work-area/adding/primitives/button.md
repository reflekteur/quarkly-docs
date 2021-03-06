Button

![](https://uploads.quarkly.io/landing/docs-interface-context-menu.png)

Стилизованный компонент для кнопки.

Доступные свойства:

type

HTML-элемент, который будет использован в документе: input или button

disabled

Флаг, если кнопка отключена по умолчанию

Hr

Обычная линия, использует элемент hr.

Icon

Иконка из доступного в конструкторе набора.

Доступные свойства:

size

Размер иконки, соответствует размеру шрифта

category

Имя набора:

*   fa – Font Awesome
    
*   bs – Bootstrap Icons
    
*   io – Ionicons
    
*   md – Material Design
    
*   ti – Typicons
    
*   go – GutHub Octicons
    
*   fi – Feather
    
*   gi – Game Icons
    
*   wi – Weather Icons
    
*   di – Devicons
    
*   ai – Ant Design
    

icon

Имя иконки в конкретном наборе, вы можете посмотреть полный список названий на оф. сайте нужного набора или узнать имя нужной иконки выбрав её в конструкторе

color

Цвет иконки, соответствует стилевому свойству color

Image

Обычное изображение.

Доступные свойства:

object fit

Определяет, как содержимое должно заполнять контейнер относительно его высоты и ширины

object position

Используется в сочетании с object fit и задаёт положение содержимого внутри контейнера

src

Ссылка на изображение

srcset

Список из одной или нескольких строк, разделенных запятыми, определяющий набор возможных изображений для отображения в браузере. Каждая строка списка должна содержать дескриптор ширины или плотности пикселей

sizes

Список размеров изображений для разных размеров страниц. Он состоит из разделенных запятыми медиа-запросов со значениями ширины изображения

alt

Альтернативное текстовое описание изображения, будет показано в браузере если изображение не получилось загрузить

title

Заголовок изображения, будет показан в виде всплывающей подсказки при наведении курсора

loading

Отложить загрузку изображения за пределами экрана

Input

Одно или многострочное поле ввода текста.

Доступные свойства:

name

уникальное для формы имя поля

type

тип элемента формы: text, email, tel, date, number, file, search

placeholder

подсказывающий текст

defaultValue

значение поля по умолчанию

required

флаг, если поле обязательное для заполнения

disabled

флаг, если поле отключено по умолчанию

as

html-элемент, который будет использован в документе: input или textarea

Link

Компонент для создания ссылки.

Доступные свойства:

href

задает адрес, на который следует перейти

target

имя окна, в котором следует выполнить переход: \_self, \_blank, \_parent или \_top

List

Компонент для создания списка

Доступные свойства:

as

тип списка: ol (нумерованный) или ul (маркированный)

list-style-type

вид маркера для каждого элемента списка

Text

Компонент для вывода текста, позволяет редактировать текст на холсте.

Доступные свойства:

as

html-элемент, который будет использован в документе:  
h1, h2, h3, h4, h5, h6, p, div