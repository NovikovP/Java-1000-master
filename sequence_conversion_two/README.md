<h1 class="title">Преобразование последовательности - 2 (29%)</h1>
<p><a href="https://acmp.ru/index.asp?main=task&id_task=326" target="_blank">Ссылка на задачу</a></p>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 29%</b></p>
<p>Задана последовательность, содержащая n целых чисел. Необходимо найти число, которое встречается в этой последовательности наибольшее количество раз, а если таких чисел несколько, то найти минимальное из них, и после этого переместить все такие числа в конец заданной последовательности. Порядок расположения остальных чисел должен остаться без изменения.</p>
<p>Например, последовательность 1, 2, 3, 2, 3, 1, 2 после преобразования должна превратиться в последовательность 1, 3, 3, 1, 2, 2, 2.</p>
<p>Требуется написать программу, которая решает данную задачу.</p>
<h2>Формат ввода</h2>
<p>Первая строка входного файла input.txt содержит число n — количество чисел во входной последовательности (3 ≤ n ≤ 100). Следующая строка содержит входную последовательность, состоящую из n целых чисел, не превышающих по модулю 100. Все числа в строке разделены пробелом.</p>
<h2>Формат вывода</h2>
<p>В выходной файл output.txt выводится последовательность чисел, которая получается в результате названного преобразования. Все числа в последовательности должны быть разделены пробелом.</p>
<h3>Примеры</h3>
<table class="sample-tests">
  <thead>
     <tr>
        <th>Ввод</th>
        <th>Вывод</th>
     </tr>
  </thead>
  <tbody>
     <tr>
        <td>7<br>
            1 2 3 2 3 1 2</td>
        <td>1 3 3 1 2 2 2</td>
     </tr>
  </tbody>
</table>