# Ex03 Time Table
## Date:23/04/2025

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
    <head>
        <title>SAVEETHA ENGINEERING COLLEGE AUTONOMOUS</title>
    </head>
    <body>
        <img src="logo.png">
        <table border="1">
            <caption>SLOT TIMETABLE-MOULIKA AKSHAYA K(24900229)</caption>
            <br>
        <tr bgcolor="blue">
          <th>TIMETABLE</th>
          <th>MONDAY</th>
          <th>TUEDAY</th>
          <th>WEDNESDAY</th>
          <th>THURSDAY</th>
          <th>FRIDAY</th>
          <th>SATURDAY</th>
         
        </tr>

        <tr bgcolor="yellow">
            <td>8-10</td>
            <td>FREE SLOT</td>
            <td>BEEE</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
            <td>FREE SLOT</td>

        </tr>
        <tr bgcolor="yellow">
            <td>10-12</td>
            <td>DE</td>
            <td>MATHS</td>
            <td>BEEE</td>
            <td>C PROGRAMMING</td>
            <td>C PROGRAMMING</td>
            <td>MATHS</td>
        </tr>
        <tr bgcolor="yellow">
            <td>12-1</td>
            <td>LUNCH</td>
            <td>LUNCH</td>
            <td>LUNCH</td>
            <td>LUNCH</td>
            <td>LUNCH</td>
            <td>LUNCH</td>
        </tr>
        <tr bgcolor="yellow">
            <td>1-3</td>
            <td>WEB</td>
            <td>WEB</td>
            <td>MENTOR MEET</td>
            <td>DE</td>
            <td>YOGA</td>
            <td>CHEMISTRY</td>

        </tr>
        <tr bgcolor="yellow">
            <td>3-5</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>CHEMISTRY</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            
        </tr>
        </table>
        <br>
        <table border="1">
            <tr>
                <th>S.NO</th>
                <th>COURSE CODE</th>
                <th>COURSE NAME</th>
                </tr>
            <tr>
                <th>1</th>
                <th>19AI414</th>
                <th>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(WEB)</th>
            </tr>
            <tr>
                <th>2</th>
                <th>19AI414</th>
                <th>FUNDAMENTALS OF C PROGRAMMING(C PROGRAMMING)</th>
            </tr>
            <tr>
                <th>3</th>
                <th>19CY304</th>
                <th>PRINCIPLES OF CHEMISTRY(CHEMISTRY)</th>
            </tr>
            <tr>
                <th>4</th>
                <th>19EE305</th>
                <th>BASIC ELECRTICAL,ELECTRONICS ENGINEERING(BEEE)</th>
            </tr>
            <tr>
                <th>5</th>
                <th>19EE404</th>
                <th>DIGITAL ELECTORNICS(DE)</th>
            </tr>
            <tr>
                <th>6</th>
                <th>19MA201</th>
                <th>CALCULS AND MATRIX ALGEBRA(MATHS)</th>
            </tr>
            <tr>
                <th>7</th>
                <th>SH5616</th>
                <th>YOGA AND MEDITATION(YOGA)</th>
            </tr>
            <tr>
                <th>8</th>
                <th>ECA-M-SCOFT</th>
                <th>MENTOR MEET</th>
            </tr>
        </table>
    </body>
    
</html>
```

## OUTPUT

INCLUDE YOUR OUTPUT IMAGE

![alt text](<Screenshot (89).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
