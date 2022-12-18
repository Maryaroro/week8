# week8

Вопросы 💎

1. Какие основные преимущества Bootstrap?

1) Адаптивность
2) Кросс-браузерность
3) Легкость в использовании и быстрота в освоении
4) Понятный код
5) Единство стилей

2. Как сделать желтую кнопку с помощью Bootstrap?
   <button type="button" class="btn btn-warning">Предупреждение</button>
3. Каким кодом можно сделать такую сетку?
   Не получилось разобраться,буду обсуждать на созвоне(
4. Каким компонентом Bootstrap можно задать такой элемент?
<div class="progress">
  <div class="progress-bar" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">25%</div>
</div>

5. Как убрать поля между колонками?
   class="row no-gutters"

6. Как сделать навигацию на Bootstrap?
<nav class="nav">
  <a class="nav-link active" href="#">Active</a>
  <a class="nav-link" href="#">Link</a>
  <a class="nav-link" href="#">Link</a>
  <a class="nav-link disabled" href="#">Disabled</a>
</nav>

7. Что такое колонка auto-layout ?
   Это свойство адаптивности bootstrap.
8. Как сделать центрирование содержимого по горизонтали? А по вертикали?
   class="row align-items-center”
   class="row justify-content-center"

9. Как задать адаптивность для колонки шириной в 50%, чтобы при ширине экрана меньше 768px она становилась шириной на весь экран?
<div class="col-6 col-md-12"> </div>
10. Что произойдет, если колонок станет больше 12?
    Лишние колонки будут переноситься на следующую строку по правилам FlexBox.

11. Как задать иконку инстаграм через font awasome?
    <i class="fa fa-instagram" aria-hidden="true"></i>

12. Чем отличается container от container-fluid?

1) Контейнер с фиксированной шириной, для центровки контейнера по середине шаблона.
<div class="container"></div>
2) Контейнер с шириной во весь экран.
<div class="container-fluid"></div>
