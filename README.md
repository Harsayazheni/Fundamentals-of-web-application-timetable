# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
Create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Timetable</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        table {
            border-collapse: collapse;
            margin: 20px auto;
            width: 80%;
            text-align: center;
        }
        th, td {
            border: 2px solid #333;
            padding: 10px;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        tr:hover {
            background-color: #d6eaf8;
        }
    </style>
</head>
<body>
    <h2 style="text-align: center;">Weekly Timetable</h2>
    <table>
        <tr>
            <th>8:00 - 10:00</th>
            <th>10:00 - 12:00</th>
            <th>1:00 - 3:00</th>
            <th>3:00 - 5:00</th>
        </tr>
        <tr>
            <td>Communicative English</td>
            <td>Principles of Chemistry in Engineering</td>
            <td>FREE</td>
            <td>FREE</td>
        </tr>
        <tr>
            <td>Python Programming</td>
            <td>FREE</td>
            <td>Programming in C</td>
            <td>Computational Physics</td>
        </tr>
        <tr>
            <td>Fundamentals of Web Application Development</td>
            <td>Communicative English</td>
            <td>Principles of Chemistry in Engineering</td>
            <td>Calculus and Matrix Algebra</td>
        </tr>
        <tr>
            <td>FREE</td>
            <td>Calculus and Matrix Algebra</td>
            <td>Fundamentals of Web Application Development</td>
            <td>Python Programming</td>
        </tr>
        <tr>
            <td>Programming in C</td>
            <td>Communicative English</td>
            <td>Computational Physics</td>
            <td>Soft Skills</td>
        </tr>
    </table>
</body>
</html>

```
# OUPUT
![OUTPUT](http://harsayazheni.student.saveetha.in/static/images/out1.png?raw=true)

# VALIDATOR
![OUTPUT](http://harsayazheni.student.saveetha.in/static/images/valid.png?raw=true)
