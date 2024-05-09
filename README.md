# Ex03 Time Table
## Date: 18-03-24

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
		<title>
			Time Table
		</title>


	</head>
	<body align="center" bgcolor="skyblue" >
		 <center>
            <img src= "/static/logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="yellow">
			<caption>SLOT TIME TABLE- SWETHA A (212223110013) </caption>
<br>
<tr>
    <th bgcolor="lightgray"> Day/Time </th>
    <th bgcolor="lightgray"> Monday </th>
    <th bgcolor="lightgray"> Tuesday </th>
    <th bgcolor="lightgray"> Wednesday </th>
    <th bgcolor="lightgray"> Thursday </th>
    <th bgcolor="lightgray"> Friday </th>
    <th bgcolor="lightgray"> Saturday </th>
</tr>
<tr>
    <th bgcolor="cyan"> 8-10 </td>
    <td> Free SLOT </td>
    <td> Free SLOT </td>
    <td> Chemisty </td>
    <td> Free SLOT </td>
    <td> Web Application </td>
    <td> Creative skills </td>
</tr>
<tr>
    <th bgcolor="dark blue"> 10-12 </th>
    <td> Free SLOT </td>
    <td> OS </td>
    <td>PROB </td>
    <td> OS </td>
    <td> FUND OF C </td>
    <td> Chemistry </td>
</tr>
<tr>
    <th bgcolor="sky blue"> 12-1 </th>
    <td colspan="6" align="center"> LUNCH </td>
</tr>
<tr>
    <th bgcolor="sky blue"> 1-3 </th>
<td> Free SLOT </td>
<td> Web Application </td>
<td> ENG </td>
<td> Web Application  </td>
<td> CN </td>
<td> PROB </td>
</tr>
<tr>
<th bgcolor="light green"> 3-5 </td>
<td> FUND of C </td>
<td> Free SLOT </td>
<td> CN </td>
<td> Free SLOT  </td>
<td> ENG </td>
<td> FREE SLOT </td>
</tr>
</table>
<br>
<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="pink">
<br>
<tr>
    <th align="center"> S.No </th>
    <th align="center"> Subject Code </th>
    <th align="center"> Subject Name </th>
</tr>
<tr>
    <th> 1. </td>
    <td align="center">19MA222 </td>
    <td align="center"> PROB </td>
</tr>
<tr>
    <th align="center"> 2. </td>
    <td align="center"> 19AI414 </td>
<td align="center"> Fundamentals of web applications (FWAD) </td>
</tr>
<tr>
    <th align="center"> 3. </td>
    <td align="center"> 19AI304 </td>
    <td align="center"> Fundamentals of C programming (FUND OF C) </td>
</tr>
<tr>
    <th align="center"> 4. </td>
    <td align="center"> 19EN101 </td>
    <td align="center"> English (ENG) </td>
</tr>
<tr>
    <th align="center"> 5. </td>
    <td align="center"> 19CY205 </td>
    <td align="center"> Chemistry </td>
</tr>
<tr>
    <th align="center"> 6. </td>
    <td align="center"> 19CS406 </td>
    <td align="center"> CN  </td>
</tr>
<tr>
    <th align="center"> 7. </td>
    <td align="center"> 19405</td>
    <td align="center"> OS </td>
</tr>
<tr>
    <th align="center"> 8. </td>
    <td align="center"> 19EY702 </td>
    <td align="center"> Creative skills for communication (CRT SKILLS) </td>
</tr>

</table>
</body>

</html>

```
## OUTPUT
![alt text](<Screenshot 2024-03-18 195501.png>) 

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
