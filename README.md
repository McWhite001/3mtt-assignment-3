# 3mtt-assignment-3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Records</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f4;
        }

        .header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .content {
            padding: 20px;
        }

        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th {
            background-color: #333;
            color: white;
            padding: 10px;
        }

        td {
            padding: 10px;
            text-align: center;
        }

        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <div class="header">
        <h1>Student Records</h1>
        <p>Assignment 3 - Web Development</p>
    </div>

    <!-- Content Section -->
    <div class="content">
        <h2>Student Table</h2>

        <table>
            <tr>
                <th>Name</th>
                <th>Course</th>
                <th>Score</th>
            </tr>
            <tr>
                <td>Adorere</td>
                <td>Computer Science</td>
                <td>85</td>
            </tr>
            <tr>
                <td>suberu</td>
                <td>Software Engineering</td>
                <td>90</td>
            </tr>
            <tr>
                <td>Samuel</td>
                <td>Information Technology</td>
                <td>78</td>
            </tr>
            <tr>
                <td>Grace Itopa</td>
                <td>Data Science</td>
                <td>88</td>
            </tr>
        </table>
    </div>

    <!-- Footer Section -->
    <div class="footer">
        <p>&copy; 2026 Student Records Page</p>
    </div>

</body>
</html>