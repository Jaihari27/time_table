# Ex02 Time Table
# Date:
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
    <title>Timetable</title>
</head>
<body>
    <center>
        <img src="sec.png" height="150" width="700">
    </center>

    <table align="center" bgcolor="iceblue" border="2" cellspacing="5" cellpadding="5">
        <caption>Slot Time Table - S Jaihari (25008769)</caption>

        <tr align="center" bgcolor="yellow">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>

        <tr>
            <th bgcolor="yellow">8-10</th>
            <td>FREE SLOT</td>
            <td>pyt</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td> FREE SLOT</td>
        </tr>

        <tr>
            <th bgcolor="yellow">10-12</th>
            <td>FREE SLOT</td>
            <td>eng</td>
            <td>pyt</td>
            <td>eng</td>
            <td> FWAD</td>
            <td> FWAD</td>
        </tr>

        <tr>
            <th bgcolor="yellow">12-1</th>
            <td colspan="6">LUNCH TIME</td>
        </tr>

        <tr>
            <th bgcolor="yellow">1-3</th>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>mentor meet</td>
            <td>eng</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
        </tr>

        <tr>
            <th bgcolor="yellow">3-5</th>
            <td>FREE SLOT</td>
            <td>pyt</td>
            <td>pyt</td>
            <td>FREE SLOT </td>
            <td>pyt</td>
            <td>eng</td>
        </tr>
    </table>

    <br>

    <table align="center" bgcolor="red" border="2" cellspacing="5" cellpadding="5">
        <tr>
            <th>S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI301</td>
            <td>Python Programming (pyt)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>SH101</td>
            <td>Communicative English (eng)</td>
        </tr>
    </table>
</body>
</html>
```
# OUTPUT
<img width="1919" height="998" alt="image" src="https://github.com/user-attachments/assets/2cf40347-0bd5-41fa-bf01-cf4c7d8ac685" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
