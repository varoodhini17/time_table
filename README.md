# Ex02 Time Table
# Date:27-11-2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
    <head>
    <title>SLOT TIMETABLE</title>
    <link rel="icon" href="/static/LOGO.jpeg">
    <img src="/static/SAVEETHA.png"height="100"width="90%">
    <style>
        table{
            background-color:rgb(214, 11, 79);
            border:3px solid black;
            width:100%;
            text-align:center;
            border-collapse:collapse;
            padding:10px;
        }
        th{
            border:3px solid black;
            text-align:center;
            padding:10px;
            background-color:lightcoral;
        }
        td{
            text-align:center;
            padding:10px;
            border:3px solid black;
            background-color:white;
        }
        h3,h2{
            text-align:center;
            background-color:rgb(228, 255, 224);
            
        }
    </style>
    </head>
    <body>
        <h2>SAVEETHA ENGINEERING COLLEGE</h2>
        <h3>VAROODHINI-25014386</h3>
        <table>
        <tr>
            <th> DAY/TIME</th>
            <th> MONDAY</th>
            <th> TUESDAY</th>
            <th> WEDNESDAY</th>
            <th> THURSDAY</th>
            <th> FRIDAY</th>
            <th> SATURDAY</th>

        
        </tr>
        <tr>
            <th>8:00 TO 10:00</th>
            <td>WEB</td>
            <td>WEB</td>
            <td>WEB</td>
            <td rowspan="2">FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>PYTHON</td>

        </tr>
        <tr>
            <th> 10:00 TO 12:00</th>
            <td> ENG</td>
            <td> PYTHON</td>
            <td>FREE SLOT</td>
            <td>ENG</td>
            <td> ENG</td>
        </tr>
        <tr>
            <th> 12:00 TO 1:00</th>
            <th colspan="6">LUNCH BREAK</th>
        </tr>
        <tr>
            <th> 1:00 TO 3:00</th>
            <td> WEB</td>
            <td> FREE SLOT</td>
            <td> MENTOR MEET</td>
            <td> FREE SLOT</td>
            <td> WEB</td>
            <td> ENG</td>
        </tr>
        <tr>
            <th>3:00 TO 5:00</th>
            <td> FREE SLOT</td>
            <td> PYTHON</td>
            <td> PYTHON</td>
            <td> PYTHON</td>
            <td> FREE SLOT</td>
            <td> FREE SLOT</td>
            
        </tr>
        </table>
        <h3></h3>
        <table>

            <tr BGcolor="lavender">
                <th> S.NO</th>
                <th> SUBJECT CODE</th>
                <th> SUBJECT NAME</th>
            </tr>
            <tr>
                <th BGcolor="lavender">1</th>
                <td> Fundamentals of Web Application Development</td>
                <td> 19AI1414</td>
                
            </tr>
            <tr>
                <th BGcolor="lavender">2</th>
                <td>Python Programming</td>
                <td> 19AI301</td>
            </tr>
            <tr>
                <th BGcolor="lavender">3</th>
                <td>Communicative English</td>
                <td>19EN101</td>
            </tr>
        </table>
    </body>
    
</html>
```
# OUTPUT
![alt text](<Screenshot (46).png>)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
