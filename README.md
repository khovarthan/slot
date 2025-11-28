# Ex02 Time Table
## Date:28.11.2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

```
<html>
    <head>
        <title>Timetable</title>
    </head>
    <body>
        <img src="logo.png" width="594px;">
        <br>
        <br>
        <table border="4" cellspacing="3" cellpadding="6" style="background-color: rgb(107, 208, 112);">
            <caption><b>SLOT TIME TABLE - Khovarthan v (25012253)</b></caption>
            <tr bgcolor="Yellow" align="center">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="Blue" align="center">
                <td bgcolor="Yellow">8-10</td>
                <td>CRYPTO</td>
                <td>FREE</td>
                <td>FWAD</td>
                <td>FREE</td>
                <td>C</td>
                <td>FWAD</td>
            </tr>
            <tr bgcolor="Blue" align="center">
                <td bgcolor="Yellow">10-12</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>FREE</td>
                <td>CRYPTO</td>
                <td>FREE</td>
            </tr>
            <tr bgcolor="Blue" align="center">
                <td bgcolor="Yellow">12-1</td>
                <td colspan="6">LUNCH BREAK</td>
            </tr>
            <tr bgcolor="Blue" align="center">
                <td bgcolor="Yellow">1-3</td>
                <td>FREE</td>
                <td>CRYPTO</td>
                <td>MM</td>
                <td colspan="2">FREE</td>
                <td>CRYPTO</td>
            </tr>
            <tr bgcolor="Blue" align="center">
                <td bgcolor="Yellow">3-5</td>
                <td>C</td>
                <td>C</td>
                <td>C</td>
                <td>C</td>
                <td colspan="2">FREE</td>
            </tr>
        </table>
        <br>
        <table border="3" cellspacing="4" cellpadding="4">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th style="width: 408px;">Subject Name</th>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI304</td>
                <td>Fundamentals of C Programming (C)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19CS547</td>
                <td>Fundamentals of Cryptocurrency (CRYPTO)</td>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
        </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (31).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
