# Ex03 Time Table
## Date:15.11.2023

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
<<html>
<head>
<title>slot Timetable</title>    
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="grey">
<caption><b>SLOT TIME TABLE - PRIDEESH M(23007215)</b></caption>
<tr align="center">
<th bgcolor="PINK">Day/Time</th>
<th bgcolor="PINK">Monday</th>
<th bgcolor="PINK">Tuesday</th>
<th bgcolor="PINK">Wednesday</th>
<th bgcolor="PINK">Thursday</th>
<th bgcolor="PINK">Friday</th>
</tr>
<tr align="center">
<th bgcolor="red">8-10</th>
<td>FREE SLOT</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>FUNDAAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
</tr>
<tr align="center">
<th bgcolor="RED">10-12</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>PHYSICS IN QUANTUM COUMPUTING</td>
<td>FUNDAAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="RED">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="RED">1-3</th>
<td>SOFT SKILLS</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr align="center">
<th bgcolor="RED">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
<td>PHYSICS IN QUANTUM COUMPUTING</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>s. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19EN101</td>
<td>COMMUNICATIVE ENGLISH(CE)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING(C PROGRAME)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY701</td>
<td>SOFT SKILLS (SS)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19PH214</td>
<td>PHYSICS IN QUANTUM COUMPUTING</td>
</tr>
<tr>
<td align="centre">7.</td>
<td align="centre">19MA201</td>
<td>CALCULUS AND MATRIX ALGEBRA</d>
</table>
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot (8).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
