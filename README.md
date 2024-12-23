# Ex03 Time Table
# Date:
# AIM:
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
    <title>time table</title>
    </head>
    <body>
        <h1 align="center"><img src="seclogo.png"
         height="100" width="600"></h1>
        <table border="1" cellspacing="5" cellpadding="5" bgcolor="cyan" align="center">
            <caption align="center"><font size><b>TIME TABLE - SUBASH MIRACLE RAJ E (24000572)</b></font></caption >
            <tr>
                <TH bgcolor="teal">DAY</TH>
                <th bgcolor="teal">8-10</th>
                <th bgcolor="teal">10-12</th>
                <th bgcolor="teal">12-1</th>
                <th bgcolor="teal">1-3</th>
                <th bgcolor="teal">3-5</th>
            </tr>
            <tr>
                <th bgcolor="teal">MONDAY</th>
                <td bgcolor="yellow" align="center">DE</td>
                <td bgcolor="yellow" align="center">WEB</td>
                <td bgcolor="yellow" rowspan ="6">LUNCH</td>
                <td bgcolor="yellow" align="center">FREE SLOT</td>
                <td bgcolor="yellow" rowspan="5" align="center">FREE SLOT</td>
            </tr>
            <tr>
                <th bgcolor="teal">TUESDAY</th>
                <td bgcolor="yellow" align="center">ENGLISH</td>
                <td bgcolor="yellow" align="center">MATHS</td>
                <td bgcolor="yellow" align="center">DE</td>
            </tr>
            <tr>
                <th bgcolor="teal">WEDNESDAY</th>
                <td bgcolor="yellow" colspan="2" align="center">FREE SLOT</td>
                <td bgcolor="yellow" align="center">MENTOR</td>
            </tr>
            <tr>
                <th bgcolor="teal">THURSDAY</th>
                <td bgcolor="yellow" align="center">PHYSICS</td>
                <td bgcolor="yellow" align="center">SS</td>
                <td bgcolor="yellow" align="center">WEB</td>
            </tr>
            <tr>
                <th bgcolor="teal">FRIDAY</th>
                <td bgcolor="yellow" align="center">ENGLISH</td>
                <td bgcolor="yellow" align="center">PYTHON</td>
                <Td bgcolor="yellow" align="center">PHYSICS</Td>
            </tr>
            <tr>
                <th bgcolor="teal">SATURDAY</th>
                <td bgcolor="yellow" align="center">FREE SLOT</td>
                <td bgcolor="yellow" align="center">MATHS</td>
                <td bgcolor="yellow" align="center">FREE SLOT</td>
                <td bgcolor="yellow" align="center">WEB</td>
            </tr>
        </table><br>
        </body>
        <body>
        <table border="1" cellspacing="5" cellpadding="5" align="center" width="575" height="10">
            <tr>
                <th>S.NO</th>
                <TH>SUBJECT CODE</TH>
                <TH>SUBJECT NAME</TH>
            </tr>
            <TR>
                <th>1</th>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </TR>
            <tr>
                <th>2</th>
                <TD>19AL414</TD>
                <td>Fundamental of Web Application</td>
            </tr>
            <tr>
                <th>3</th>
                <td>19AL301</td>
                <td>Python Programming</td>    
            </tr>
            <tr>
                <TH>3</TH>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <TR>
                <th>4</th>
                <td>19MA201</td>
                <td>Calculus and matrix algebra</td>
            </TR>
            <TR>
                <TH>5</TH>
                <td>SH3214</td>
                <td>Physics for Quantum Computing</td>
            </TR>
            <TR>
                <th>6</th>
                <td>19EY708</td>
                <td>Carrer development skills(ss)</td>
            </TR>
        </table>
        </body>
        </html>
```
# OUTPUT
![alt text](<Screenshot 2024-11-25 154012.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
