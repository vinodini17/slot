# Ex03 Time Table
## Date:18/03/2024

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
<title>Slot Timetable</title>
</head>
<body> 
<center>
<img src="logo.png" height="200" width="500">
</center>
<br>
<table align="center" border="2" width="5" cellspacing="2">
<caption> <b>SLOT TIME TABLE - VINODINI R (23012497)</caption>

<tr align="center">
<th bgcolor="pink">Day/Time</th>
<th bgcolor="pink">Monday</th>
<th bgcolor="pink">Tuesday</th>
<th bgcolor="pink">Wednesday</th>
<th bgcolor="pink">Thursday</th>
<th bgcolor="pink">Friday</th>
</tr>
<tr>
<td bgcolor="pink">7-7:20</td>
<th bgcolor="cyan" colspan="4">Free Slot</th>
<td bgcolor="cyan">Tamil</td>
</tr>
<tr>
<td bgcolor="pink">8-10</td>
<td bgcolor="cyan">PHY</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">CHEM</td>
<td bgcolor="cyan">PHY</td>
<td bgcolor="cyan">FWAD</td>
</tr>
<tr>
<td bgcolor="pink">10-12</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">FWAD</td>
<td bgcolor="cyan">BEEME</td>
<td bgcolor="cyan">MATHS</td>
<td bgcolor="cyan">C</td>
</tr>
<tr>
<td bgcolor="pink">12-1</td>
<th bgcolor="cyan" colspan="5">Lunch</th>
</tr>
<tr>
<td bgcolor="pink">1-3</td>
<td bgcolor="cyan">BEEME</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">CS</td>
<td bgcolor="cyan">CD</td>
<td bgcolor="cyan">CHEM</td>
</tr>
<tr>
<td bgcolor="pink">3-5</td>
<td bgcolor="cyan">C</td>
<td bgcolor="cyan">CD</td>
<td bgcolor="cyan">FWAD</td>
<th bgcolor="cyan" colspan="2">FREE SLOT</th>
</tr>
</table>
<br>
<table align="center" border="5" width="600" cellspacing="5">
<tr>
<th>S.No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td>1.</td>
<td>19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING(C)</td>
</tr>
<tr>
<td>2.</td>
<td>19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
</tr>
<tr>
<td>3.</td>
<td>19CS409</td>
<td>COMPILER DESIGN(CD)</td>
</tr>
<tr>
<td>4.</td>
<td>19EY702</td>
<td>CREATIVE SKILLS OF COMMUNICATION(CS)</td>
</tr>
<tr>
<td>5.</td>
<td>19CY205</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING(CHEM)</td>
</tr>
<tr>
<td>6.</td>
<td>19PH214</td>
<td>PHYSICS FOR QUANTUM COMPUTING(PHY)</td>
</tr>
<tr>
<td>7.</td>
<td>22HS102</td>
<td>TAMILS AND TECHNOLOGY(TAMIL)</td>
</tr>
<tr>
<td>6.</td>
<td>19MA222</td>
<td>PROBABILITY AND QUEUEING MODELS(MATHS)</td>
</tr>
<tr>
<td>6.</td>
<td>19EE305</td>
<td>BASIC ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING(BEEME)</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
<img width="959" alt="image" src="https://github.com/vinodini17/slot/assets/149347288/471e389f-dd59-460a-bbf9-b02b5e964c4e">


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
