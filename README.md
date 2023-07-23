Привет всем, кто зашел на мою страницу.
<p> Меня зовут Александр Егоров, я начинающий аналитик данных из Новосибирска.<p>
В настоящее время прохожу обучение по профессии аналитик данных.

## Навыки и технологии
- Инструменты анализа данных: SQL, Excel
- Языки программирования и библиотеки: Python
- Системы управления базами данных: PostgreSQL

В этом репозитарии вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
## Проект 1: Моделирование изменения балансов студентов
<p>Что нужно было сделать:<p>
<ol>
  <li>Посмотреть на изменения балансов студентов </li>
  <li>Создать визуализацию итогового результата </li>
</ol>
<p>Краткое описание решения <p>
  <li>Узнаем, когда была первая транзакция для каждого студента</li>
  <li>Собераем таблицу с датами за каждый календарный день 2016 года</li>
  <li>Создаем CTE, где будут храниться все даты жизни студента после того, как произошла его первая транзакция</li>
  <li>Находим все изменения балансов, связанные с успешными транзакциями</li>
  <li>Находим изменения балансов из-за прохождения уроков</li>
  <li>Создаем CTE «balances» с вычисленными балансами каждого студента</li>
  <li>Посмотрим, как менялось общее количество уроков на балансах студентов</li>
<p>
<p>  <a href="https://github.com/Alexx-andr/My-porfolio/blob/main/%D0%9A%D0%BE%D0%B4%20SQL%20%D0%B4%D0%BB%D1%8F%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%201.txt">Ссылка на проект 1 (код SQL)</a> <p>
<p>
<p>  <a href="https://github.com/Alexx-andr/My-porfolio/blob/main/%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%201%20(1).xlsx">Результат проекта</a> <p>
<p>
<p>  <a href="https://github.com/Alexx-andr/My-porfolio/blob/main/%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%201.png">График</a> <p>

Выводы:

В итоговой таблице можно увидеть, что к концу 2016 года накопительный итог по урокам был: 4534, студентам было начислено больше уроков, чем было пройдено. Если было установлено прохождение уроков по месяцам, то можно увидеть, что в начале 2016 года приход был небольшим, по сравнению с концом года. Можно сделать вывод, что к концу года учащиеся получают ответы на вопросы по урокам, поэтому ситуация намного выше. Появляются из выводов выше, что студенты бросают обучение медленно или последовательно, провоцируют тем самые исключения "хвостов", которые идут на следующий год.
## Проект 2: Построение витрины для модели машинного обучения в банке
<p>Что нужно было сделать:<p>
<ol>
  <li>Написать скрипт, который сделает витрину со столбцами </li>
</ol>
