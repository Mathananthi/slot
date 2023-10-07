# Ex03 Time Table
## Date: 07.10.23
## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
        .table1{
            background-color: cyan;
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px;
        }
        .table2{
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color: yellow;
        }
        .c1{
            background-color: yellow;
        }
    </style>
</head>
<body>
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
        .table1{
            background-color: greenyellow;
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px;
        }
        .table2{
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color: red;
        }
        .c1{
            background-color: red;
        }
    </style>
</head>
<body>
    <img src = "logo.png" width = "800" height="150">
    <h3 class = "name">SLOT TIMETABLE - Mathan M (212221040102)</h3>
    <table border="1" class = "table1">
        <tr class = "row1">
            <th class="c1">Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td class="c1">8-10</td>
            <td>BEEE</td>
            <td>FWAD</td>
            <td>CD</td>
            <td>ML</td>
            <th colspan="2">Free</th>
        </tr>
        <tr>
            <td class="c1">10-12</td>
            <th colspan="1">Free</th>
            <td>CD</td>
            <td>BEEE</td>
            <td>GP</td>
            <th colspan="1">Free</th>
            <td>CNS</td>
            
        </tr>
        <tr>
            <td class="c1">12-1</td>
            <th colspan="6">LUNCH</th>
        </tr>
        <tr>
            <td class="c1">1-3</td>
            <td>EES</td>
            <th colspan="1">Free</th>
            <td>GP</td>
            <td>MP</td>
            <th colspan="2">Free</th>
            
        </tr>
        <tr>
            <td class="c1">3-5</td>
            <td>CNS</td>
            <td>ML</td>
            <th colspan="1">Free</th>
            <td>FWAD</td>
            <th colspan="1">Free</th>
            <td>FWAD</td>
        </tr>
    </table>
    <br>
    <br>
    <table border="1" class="table2">
        <tr>
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Applications Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS409</td>
            <td>Compiler Design (CD)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS521</td>
            <td>Cryptography and Network Security (CNS)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19AI410</td>
            <td>Machine learning (ML)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19AI513</td>
            <td>Game Programming (GP)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY705</td>
            <td>Employment Enhancement Skills (EES)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19EE305</td>
            <td>Basic Electrical and Electronics Engineering (BEEE)</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>19CS701</td>
            <td>Mini Project (MP)</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot (3).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
