<h1>Описание</h1>
Постарался реализовать поддержку иконок с 1 по 6 в одну строку без внесения правок в css. Для этих целей отлично подошел `grid`.  
В современных браузерах все работает отлично. А вот IE11 поддержкой `grid` разочаровал (как обычно).  
В ходе работы выяснилось, что IE11:
- не знает `grid-gap`
- не работает с `order` у `grid`  
- не понимает `auto-fit`

Сделал для IE11 css hack на `flex`. При иконках < 4 они не будут автоматически растягиваться на всю ширину как у `grid`, а при > 4 
сразу пойдут на новую строку.

<h2>Ссылка для просмотра:</h2>
> [https://hardsign28.github.io/sirenTest/](https://hardsign28.github.io/sirenTest/)

<h3>Проверил на реальных устройствах:</h3>
- Chrome (Win 10, Android 12)
- Firefox (Win 10, Android 12)
- Opera (Win 10)
- Edge (Win 10)
- IE 11 (Win 10)
  
<h3>Проверил через Lambdatest:</h3>
- Mac Safari v12  
- iPhone 11 Safari iOS 13.3 

<br />
<br />
<br />

> P.S.Было жалко выкидывать вариант с `grid` для IE11. Вынес в отдельный URL:  
[https://hardsign28.github.io/sirenTest/alt/](https://hardsign28.github.io/sirenTest/alt/)
