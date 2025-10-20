!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table with List</title>
    <style>
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 8px;
            text-align: left;
        }
        caption {
            font-weight: bold;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <table>
        <caption>Product Information</caption>
        <thead>
            <tr>
                <th colspan="2">Product Details</th>
                <th>Price</th>
                <th>Availability</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Item A</td>
                <td>Description for Item A</td>
                <td>$10.99</td>
                <td>In Stock</td>
            </tr>
            <tr>
                <td>Item B</td>
                <td>Description for Item B</td>
                <td>$25.50</td>
                <td>Limited Stock</td>
            </tr>
            <tr>
                <td>Item C</td>
                <td>Description for Item C</td>
                <td>$5.00</td>
                <td>Out of Stock</td>
            </tr>
        </tbody>
    </table>

    <h3>Important Notes:</h3>
    <ul>
        <li>Free shipping on orders over $50.</li>
        <li>Returns accepted within 30 days of purchase.</li>
        <li>Customer support available 24/7.</li>
    </ul>

</body>
</html>

