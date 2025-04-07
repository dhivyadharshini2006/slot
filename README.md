# Ex03 Time Table
## Date: 7/04/25

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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - Dhivya Dharshini B </title>
</head>
<body>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - DHIVYA DHARSHINI B[23008727]</h3>

    <table border="1" bgcolor="cyan" cellpadding="1" >
        <tr>
            <th bgcolor="yellow">Day/Time</th>
            <th bgcolor="yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
            <th bgcolor="yellow">Saturday</th>
        </tr>
        <tr>
            <td bgcolor="yellow"> 8-10</td>
            <td>FUND OF AI</td>
            <td>FREE SLOT</td>
            <td>BB</td>
            <td>FREE SLOT</td>
            <td>HRM</td>
            <td></td>
        </tr>
        <tr>
            <td bgcolor="yellow">10-12</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>CN</td>
            <td>DS</td>
            <td></td>

        </tr>
        <tr>
            <td bgcolor="yellow">12-1</td>
            <td colspan="6">LUNCH</td>
        </tr>
        <tr>
            <td bgcolor="yellow">1-3</td>
            <td>BB</td>
            <td>HRM</td>
            <td>MM</td>
            <td>QA-1</td>
            <td>CN</td>
            <td></td>

 
        </tr>
        <tr>
            <td bgcolor="yellow">3-5</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FUND OF AI</td>
            <td>DS</td>
            <td>FREE SLOT</td>
            <td></td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EY710</td>
            <td>Quantitative Ability-1(QA-1)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS406</td>
            <td>Computer Networks</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19AI547</td>
            <td>Blockchain for Business</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19AI405</td>
            <td>Fundamental of Artificial Intelligence</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19MS156</td>
            <td>Human Resource Management</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19AI403</td>
            <td>Introduction to Data Science</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>ECA-M</td>
            <td>Mentor Meeting</td>
        </tr>
    </table>
</body>
</html>

```

## OUTPUT
![image](https://github.com/user-attachments/assets/b65ee38c-948c-4492-a7a6-e63ce23c9379)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
