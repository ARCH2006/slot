# Ex03 Time Table
## Date:

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
'''
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
    <img src="logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="yellow">
<caption><b>SLOT TIME TABLE - S ARCHANA (212223040019)</b></caption>
<tr align="center">
<th bgcolor="cyan">Day/Time</th>
<th bgcolor="cyan">Monday
<th bgcolor="cyan">Tuesday
<th bgcolor="cyan">Wednesday
<th bgcolor="cyan">Thursday
<th bgcolor="cyan">Friday
</tr>
</tr align="center">
<th bgcolor="purple">8-10</th>
<td >FREE</td>
<td >FREE</td>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td >FREE</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
</tr>
<tr align="center">
<th bgcolor="purple">10-12</th>
<td >SOFT SKILLS</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
<td >FREE</td>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td >FREE</td>
</tr>
<tr>
<th bgcolor="purple">12-01</th>
<td colspan="5" align="center"> L U N C H</td>
</tr>
<tr>
<tr align="center">
<th bgcolor="purple">01-03</th>
<td >PRINCIPLES OF CHEMISTRY</td>
<td >COMMUNICATIVE ENGLISH</td>
<td >PRINCIPLES OF CHEMISTRY</td>
<td >COMMUNICATIVE ENGLISH</td>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr align="center">
<th bgcolor="purple">03-05</th>
<td >FREE</td>
<td >FREE</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
<td >FREE</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>No.</th>
<th>Subject code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EN101</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI301C</td>
<td>PYTHON AND LINEAR ALGEBRA(PYTHON PROGRAM AND LINEAR ALGEBRA)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY701</td>
<td>SOFT SKILLS(SS)</td>
</tr
</table>
</body>
</html>
'''


## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
