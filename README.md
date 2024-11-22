# Ex03 Time Table
## Date:22.11.2024

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

## PROGRAM
```
<html>
    <body>
        <center>
            <img src="logo.png" height="100" width="540">       
        </center>
         <table border="2" bgcolor="cyan" cellpadding="20">
            <caption>
                SLOT TIMETABLE
            </caption>
            <tr>
                <th>S.NO</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>Physics</td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>web application</td>
                <td>calculus and matrix algebra</td>
                <td>web application</td>
                <td>Career development</td>
                <td>Python programming</td>
                <td>Calculus and Matrix algebra</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Basic EEE</td>
                <td>Basic EEE</td>
                <td>Mentor meet</td>
                <td>Python programming</td>
                <td>Physics</td>
                <td>web application
            </tr>

            
        </table>
    </body>
</html>   
<table border="2">
    <tr bgcolor="red">
        <th>S.no</th>
        <th>Course code</th>
        <th>Course name</th>
    </tr>
    <tr bgcolor="aqua">
        <td>1</td>
        <td>19AI414</td>
        <td>FUNDAMENTALS OF WEB APPLICATION</td>
    </tr>
    <tr bgcolor="aqua">
        <td>2</td>
        <td>19MA201</td>
        <td>CALCULUS AND MATRIX ALGEBRA </td>
    </tr>
    <tr bgcolor="aqua">
        <td>3</td>
        <td>19AI301</td>
        <td>PYTHON PROGRAMMING</td>
    </tr>
    <tr bgcolor="aqua">
        <td>4</td>
        <td>SH3214</td>
        <td>PHYSICS FOR QUANTUM COMPUTING</td>
    </tr>
    <tr bgcolor="aqua">
        <td>5</td>
        <td>19CS305</td>
        <td>COMPUTER ARCHITECTURE</td>
    </tr>
    <tr bgcolor="aqua">
        <td>6</td>
        <td>19EE305</td>
        <td>BASIC ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING</td>
    </tr>
</table>
</html>

```
## OUTPUT
![alt text](<Screenshot 2024-11-22 120236.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
