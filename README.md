# Ex03 Time Table
## Date:16.11.2024

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
        <img src="logo.png" width="700" height="90">
<table border="2"cellspacing="5"cellpadding="5">
    <caption> SLOT TIME TABLE -MOHANAPRABHA S (24900515 ) </caption>
    <tr bgcolor="violet">
        <th>DAY/TIME</th>
        <th>MONDAY</th>++
        <th>TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
    </tr>
    <tr>
        <th>8-10 </th>
        <th>FREE SLOT</th>
        <th>WEB</th>
        <th>C PROGRAMME</th>
        <th>HV</th>
        <th colspan="2">FREE SLOT</th>
    </tr>
    <tr>
        <th>10-12</th>
        <th>MATHS</th>
        <th>FREE SLOT</th>
        <th>CHEMISTRY</th>
        <th>CAREER</th>
        <th>CHEMISTRY</th>
        <th>FREE SLOT</th>
    </tr>
    <tr>
        <th>12-1</th>
        <th colspan="6">LUNCH</th>
    </tr>
    <tr>
        <th>1-3</th>
        <th>C PROGRAMME</th>
        <th>MATHS</th>
        <th>MENTOR MEET</th>
        <th>EVS</th>
        <th>WEB</th>
        <th>WEB</th>
    </tr>
    <tr>
        <th>3-5</th>
        <th colspan="4">FREE SLOT</th>
        <th>YOGA</th>
        <th>FREE SLOT</th>
    </tr>
    </table>
    <br>
    <table border="2"cellspacing="5"cellpadding="5">
    <tr bgcolor="violet">
        <th>S.NO</th>
        <th>SUBJECT CODE</th>
        <th>SUBJECT NAME</th>
    </tr>
    <tr>
        <th>1.</th>
        <th>19EY708</th>
        <th>CAREER DEVOlPMENT SKILLS</th>
    </tr>
    <tr>
        <th>2.</th>
        <th>19MA201</th>
        <th>CALCULUS AND MATRIX ALGEBRA</th>
    </tr>
    <tr>
        <th>3.</th>
        <th>19CY205</th>
        <th>PRINCIPLES OF CHEMISTRY IN ENGINEERING</th>
    </tr>
    <tr>
        <th>4.</th>
        <th>SH4801</th>
        <th>ENVIRONMENTAL SCIENCES AND SUSTAINABILITY</th>
    </tr>
    <tr>
        <th>5.</th>
        <th>SH7801</th>
        <th>HUMAN VALUES AND PROFFESIONAL ETHICS</th>
    </tr>
    <tr>
        <th>6.</th>
        <th>ECA-M-SCOFT</th>
        <th>MENTOR MEET</th>
    </tr>
    <tr>
        <th>7.</th>
        <th>19AI414</th>
        <th>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</th>
        <tr>
            <th>8.</th>
            <th>19AI304</th>
            <th>FUNDAMENTALS OF C PROGRAMMING</th>
        </tr>
        <tr>
            <th>9.</th>
            <th>SH5616</th>
            <th>YOGA AND MEDITATION</th>
        </tr>
    </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (57).png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
