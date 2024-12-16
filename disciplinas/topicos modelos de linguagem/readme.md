Tabela com os Acertos referentes ao Trabalho de QA Tabular utilizando mistral-large e mistral-small

<html>
<head>
<style>
table {
  border-collapse: collapse;
  border-spacing: 0;
  width: 100%;
  border: 1px solid #ddd;
}

th {
  text-align: center;
  padding: 8px;
  font-weight: bold;
}

tr:nth-child(even) {
  background-color: #f2f2f2;
}

td{
  text-align: center;
  padding: 8px;
}

</style>
</head>

<table>
    <tr>
        <th colspan='7' style="text-align: center;">mistral-large</th>
    </tr>
    <tr>
        <th>datasets</th>
        <th>boolean</th>
        <th>number</th>
        <th>category</th>
        <th>list[category]</th>
        <th>list[number]</th>
        <th>total_acertos</th>
    </tr>
    <tr>
        <th>central-all</th>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
    </tr>
    <tr>
        <th>central-sample</th>
        <td>3</td>
        <td>4</td>
        <td>1</td>
        <td>1</td>
        <td>4</td>
        <td>13</td>
    </tr>
    <tr>
        <th>disney-all</th>
        <td>2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
    </tr>
    <tr>
        <th>disney-sample</th>
        <td>3</td>
        <td>1</td>
        <td>4</td>
        <td>2</td>
        <td>1</td>
        <td>11</td>
    </tr>
    <tr>
        <th>holiday-all</th>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>2</td>
    </tr>
    <tr>
        <th>holiday-sample</th>
        <td>1</td>
        <td>0</td>
        <td>4</td>
        <td>2</td>
        <td>0</td>
        <td>7</td>
    </tr>
    <tr>
        <th>titanic-all</th>
        <td>2</td>
        <td>1</td>
        <td>3</td>
        <td>2</td>
        <td>0</td>
        <td>8</td>
    </tr>
    <tr>
        <th>titanic-sample</th>
        <td>3</td>
        <td>3</td>
        <td>3</td>
        <td>2</td>
        <td>2</td>
        <td>13</td>
    </tr>
</table>

<br><br><br>

<table>
    <tr>
        <th colspan='7' style="text-align: center;">mistral-small</th>
    </tr>
    <tr>
        <th>datasets</th>
        <th>boolean</th>
        <th>number</th>
        <th>category</th>
        <th>list[category]</th>
        <th>list[number]</th>
        <th>total_acertos</th>
    </tr>
    <tr>
        <th>central-all</th>
        <td>2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
    </tr>
    <tr>
        <th>central-sample</th>
        <td>2</td>
        <td>3</td>
        <td>3</td>
        <td>0</td>
        <td>2</td>
        <td>10</td>
    </tr>
    <tr>
        <th>disney-all</th>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
    </tr>
    <tr>
        <th>disney-sample</th>
        <td>0</td>
        <td>2</td>
        <td>4</td>
        <td>1</td>
        <td>1</td>
        <td>8</td>
    </tr>
    <tr>
        <th>holiday-all</th>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>2</td>
        <td>0</td>
        <td>3</td>
    </tr>
    <tr>
        <th>holiday-sample</th>
        <td>1</td>
        <td>1</td>
        <td>4</td>
        <td>2</td>
        <td>0</td>
        <td>8</td>
    </tr>
    <tr>
        <th>titanic-all</th>
        <td>2</td>
        <td>0</td>
        <td>4</td>
        <td>2</td>
        <td>0</td>
        <td>8</td>
    </tr>
    <tr>
        <th>titanic-sample</th>
        <td>1</td>
        <td>2</td>
        <td>3</td>
        <td>1</td>
        <td>0</td>
        <td>7</td>
    </tr>
</table>

</html>
