Как добавить состояния

Для некоторых компонентов доступны различные состояния, вот несколько из них:

*   hover — состояние при наведении курсора
    
*   focus — состояние когда компонент в фокусе
    
*   active, for a <Button/> and an <Input/> — состояние когда элемент активен
    
*   disabled, for a <Button/> — состояние когда кнопка не активна
    
*   link, for a <Link/> — состояние для непосещенной ссылки
    
*   visited, for a <Link/> — состояние для посещенной ссылки
    
*   и другие.
    

Свойства и значения для таких состояний вы можете указывать и в коде, используя такой синтаксис: state-props="value". Например,

```
<Text hover-color="orange"> Оранжевый текст </Text>
```