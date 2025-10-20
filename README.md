b<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>3x3 Table with Colspan</title>
<style>
table { width: 80%; /* Adjust as needed */ border-collapse: collapse;margin: 20px auto; /* Center the table */ }
th, td {border: 1px solid black;padding: 10px;text-align: center; }
th { background-color: #f2f2f2;}
</style>
</head>
<body>
<table>
<thead>
<tr><th colspan="2">Merged Header (Spans 2 Columns)</th>
<th>Header 3</th>
</tr>
</thead>
<tbody>
<tr>
<td>Row 1, Col 1</td>
<td>Row 1, Col 2</td>
<td>Row 1, Col 3</td>
</tr>
<tr>
<td>Row 2, Col 1</td>
<td>Row 2, Col 2</td>
<td>Row 2, Col 3</td>
</tr>
<tr>
<td>Row 3, Col 1</td>
<td>Row 3, Col 2</td>
<td>Row 3, Col 3</td>
</tr>
</tbody>
</table>
</body>
</html>

