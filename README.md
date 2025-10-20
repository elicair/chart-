body{
            margin:10px;
      }

      table, th, td {
        border: 1px solid black;
        border-collapse: collapse;
        padding:5px;
      }
<table style="width:100%">
  <tr>
    <th rowspan="2" colspan="2">One</th>
    <th colspan="2">two</th> 
    <th colspan="8">Three</th>
  </tr>
  <tr>
    <td colspan="2">Two A</td>
    <td colspan="2">Three A</td>
    <td colspan="2">Three B</td>
    <td colspan="2">Three C</td>
    <td colspan="2">Three D</td>
  </tr>
  <tr>
    <td>One A</td>
    <td>One B</td>
    <td>Col 1</td>
    <td>Col 2</td>
    <td>Col 1</td>
    <td>Col 2</td>
    <td>Col 1</td>
    <td>Col 2</td>
    <td>Col 1</td>
    <td>Col 2</td>
    <td>Col 1</td>
    <td>Col 2</td>
  </tr>
  <tr>
    <td colspan="12"></td>
  </tr>
</table>
