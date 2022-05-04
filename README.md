<h3>Ссылка для просмотра:</h3>
https://hardsign28.github.io/sirenTest/
<br>
<h2>Описание</h2>
Постарался реализовать поддержку иконок от 2 до 6 без внесения правок в css. Для этих целей отлично подошел <code>grid</code>.<br>
В современных браузерах все работает отлично. А вот IE11 поддержкой <code>grid</code> разочаровал.
<br>
<br>
В ходе работы выяснилось, что IE11:
<ul>
  <li>не знает <code>grid-gap</code></li>
  <li>не понимает <code>order</code> у grid</li>
  <li>не умеет <code>auto-fit</code></li>
</ul>
Поэтому сделал для IE11 css hack на <code>flex</code>.
<br>
<br>
<h3>Проверил на реальных устройствах:</h3>
<ul>
  <li>Chrome (Win 10, Android 12)</li>
  <li>Firefox (Win 10, Android 12)</li>
  <li>Opera (Win 10)</li>
  <li>Edge (Win 10)</li>
  <li>IE 11 (Win 10)</li>
</ul>
  
<h3>Проверил через Lambdatest:</h3>
<ul>
  <li>Mac Safari v12</li>
  <li>iPad Pro(11-inch) Safari iOS 13.4</li>
  <li>iPhone 11 Safari iOS 13.3 </li>  
</ul>