# Chandrayee-SWE-lab
SWE LAB
<!DOCTYPE html>
<html lang="en">
<head>
    <name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Telephone Directory and Billing System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightpink;
        }
        header {
            background-color: black;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            display: flex;
            flex-direction: column;
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        h2 {
            text-align: center;
            color: blue;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
         table, th, td {
            border: 1px solid whitesmoke;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: skyblue;
        }
        .billing-table th, .billing-table td {
            text-align: center;
        }
        .add-button {
            background-color: green;
            color: white;
            padding: 15px 10px;
            text-align: center;
            border: none;
            cursor: pointer;
            margin-top: 10px;
        }
        .add-button:hover {
            background-color: green;
        }
    </style>
</head>
<body>

    <header>
    <h1>Telephone Directory and Billing System</h1>
</header>

<div class="container">

    <!-- Telephone Directory Section -->
    <div class="section">
        <h2>Telephone Directory</h2>
        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Phone Number</th>
                    <th>Address</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Sujoy Das</td>
                    <td>(333) 456-xxxx</td>
                    <td>ishapore, City, india Country</td>
                </tr>
                <tr>
                    <td>Ahana Ghose</td>
                    <td>(333) 654-xxxx</td>
                    <td>ishapore, City, india Country</td>
                </tr>
                <tr>
                    <td>Atrayee Laskar</td>
                    <td>(333) 123-xxxx</td>
                    <td>ishapore, City, india Country</td>
                </tr>
            </tbody>
        </table>
    </div>
    <!-- Billing System Section -->
    <div class="section">
        <h2>Billing System</h2>
        <table class="billing-table">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Call Duration (mins)</th>
                    <th>Cost per Minute ($)</th>
                    <th>Total Bill ($)</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Sujoy Das</td>
                    <td>10</td>
                    <td>0.2</td>
                    <td>2.00</td>
                </tr>
                <tr>
                    <td>Ahana Ghose</td>
                    <td>20</td>
                    <td>0.25</td>
                    <td>5.00</td>
                </tr>
                <tr>
                    <td>Atrayee Laskar</td>
                    <td>15</td>
                    <td>0.3</td>
                    <td>4.50</td>
                </tr>
            </tbody>
        </table>
