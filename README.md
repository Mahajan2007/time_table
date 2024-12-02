# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Time Table</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: antiquewhite;
        }

        .logo {
            text-align: center;
        }

        table {
            border-collapse: collapse;
            margin: 20px auto;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
        }

        th, td {
            border: 2px solid #333;
            padding: 10px;
            text-align: center;
        }

        th {
            background-color: yellow;
        }

        .subject-table th {
            background-color: #333;
            color: white;
        }

        .day-table th {
            background-color: yellow;
        }

        .highlight {
            background-color: aqua;
        }

        h3 {
            text-align: center;
            margin-bottom: 20px;
        }

        img {
            display: block;
            margin: 20px auto;
        }

        .container {
            width: 80%;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <!-- Header with Logo -->
    <div class="logo">
        <img src="logo.jpg" width="1000" height="200" alt="Logo">
        <h3>Slot Time Table - Mahajanani.R (24003555)</h3>
    </div>

    <!-- Time Table -->
    <div class="container">
        <table class="day-table" width="80%" height="50%">
            <tr>
                <th>Day/Time</th>
                <th>8-10 AM</th>
                <th>10-12 PM</th>
                <th>12-1 PM</th>
                <th>1-3 PM</th>
                <th>3-5 PM</th>
            </tr>
            <tr>
                <th>Mon</th>
                <td colspan="2" class="highlight">Free Slot</td>
                <td rowspan="6" class="highlight">Lunch</td>
                <td class="highlight">Web</td>
                <td rowspan="4" class="highlight">Free Slot</td>
            </tr>
            <tr>
                <th>Tue</th>
                <td class="highlight">Chem</td>
                <td class="highlight">Free Slot</td>
                <td class="highlight">Maths for AI</td>
            </tr>
            <tr>
                <th>Wed</th>
                <td rowspan="3" class="highlight">Free Slot</td>
                <td class="highlight">Eng</td>
                <td class="highlight">Free Slot</td>
            </tr>
            <tr>
                <th>Thurs</th>
                <td class="highlight">Maths for AI</td>
                <td class="highlight">Chem</td>
            </tr>
            <tr>
                <th>Fri</th>
                <td rowspan="2" class="highlight">Web</td>
                <td rowspan="2" class="highlight">Maths for AI</td>
                <td class="highlight">Career</td>
            </tr>
            <tr>
                <th>Sat</th>
                <td class="highlight">Eng</td>
                <td class="highlight">Free Slot</td>
            </tr>
        </table>

        <!-- Subject Details Table -->
        <table class="subject-table" border="1" width="60%" height="400">
            <tr>
                <th>S.No.</th>
                <th>Subject Name</th>
                <th>Subject Code</th>
            </tr>
            <tr>
                <td>1</td>
                <td>Fundamentals of Web Application</td>
                <td>19AI401</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Maths for AI / Python / Linear Algebra</td>
                <td>19MA301</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Principles of Chemistry</td>
                <td>19CY205</td>
            </tr>
            <tr>
                <td>4</td>
                <td>Communicative English</td>
                <td>19EN101</td>
            </tr>
            <tr>
                <td>5</td>
                <td>Career Development Skills</td>
                <td>19EY708</td>
            </tr>
        </table>
    </div>
</body>
</html>


       
~~~
## OUTPUT:
![output1](output1.png)
![output2](output2.png)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.git push
