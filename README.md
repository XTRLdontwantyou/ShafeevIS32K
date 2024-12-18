
pizzeria AKA TROLLPIZZA
суть нашей пиццерии в том что все пиццы сделаны в виде тролльфейса и начинка всегда неизвестна покупателю
через приложение незарегистрированный человек может только сделать вещи такие как посмотреть меню и зарегестрироваться
зарегестрированный может ваще че хочет ну то есть заказать пиццу с рандомным вкусом сделать заказ оставить чаевые ну и все что клиент только захочет

```mermaid
    RANDOMUSER-->CHECKMENU;
    RANDOMUSER-->REGISTRATION;
    REGISTREDUSER-->CALL
    REGISTREDUSER-->CHECKMENU
    REGISTREDUSER-->ORDERPIZZA
    REGISTREDUSER-->PAYTIPS

   ```


на данной диаграмме я показал выручку в течении года ну это по нашим ожидаемым результатам

```mermaid
xychart-beta
    title "выручка pizzeria AKA TROLLPIZZA"
    x-axis [jan, feb, mar, apr, may, jun, jul, aug, sep, oct, nov, dec]
    y-axis "Revenue (in $)" 0 --> 11000
    bar [5000, 6000, 7500, 8200, 9500, 10500, 11000, 10220, 12000, 11500, 0, 6000]
    line [5000, 6000, 7500, 8200, 9500, 10500, 11000, 10220,12000, 11500, 0, 6000]
```
в нашей пиццерии есть пиццы
*   пицца без одного кусочка
*   кусочек без пиццы
*   пицца без начинки
*   с ананасами
конечно же все пиццы в виде головы тролля,так же за отдельную плату вы можете попросить затроллить любого чела в инете

```mermaid
    user-->orderpizza;
    user-->checkmenu;
    user-->trollingpeople;
    troll-->troll;
```


вот диаграмма компонентов из чего наши повара делают пиццы

```mermaid
mindmap
  root((trollpizza))
    Origins
      bacon
      human meat
       papaya
        pineapples
          
    cobblestone
      fish
```
