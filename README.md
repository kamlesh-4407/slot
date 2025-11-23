# Ex02 Time Table
## Date:11-09-2025

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
<!DOCTYPE html>
<html>
<head>
<title>Slot Timetable</title>
<style>
    body {
        background-color: #f7f2e8;      /* cream */
        color: #4b2e2b;                 /* deep brown */
        font-family: Arial;
    }
    table {
        background-color: #f3e9d7;      /* light cream */
        border-color: #6b4f3f;          /* dark brown */
    }
    th {
        background-color: #d9c2a3;       /* muted brownish-cream */
    }
    .free-slot {
        background-color: #f5dcb9;       /* soft beige */
        color: #4b2e2b;
    }
    caption {
        font-weight: bold;
        color: #4b2e2b;
    }
</style>
</head>

<body>
<center>
<h1><b>SLOT TIMETABLE</b></h1>
</center>
<br>

<table align="center" width="540" cellspacing="2" cellpadding="4" border="4">
<caption>SLOT TIMETABLE - Kamlesh Y-(212224100029)</caption>

<tr align="center">
	<th>Day/Time</th>
	<th>Monday</th>
	<th>Tuesday</th>
	<th>Wednesday</th>
	<th>Thursday</th>
	<th>Friday</th>
    <th>Saturday</th>
</tr>

<tr align="center">
	<th>8-10</th>
	<td>Training</td>
	<td>Employement Enrichment Skills</td>
	<td>Training</td>
	<td>Company Specific</td>
	<td>Training</td>
    <td>Fundamentals of Web Application</td>
</tr>

<tr align="center">
	<th>10-12</th>
	<td>Training</td>
	<td>Training</td>
	<td>Training</td>
	<td>Fundamentals of Web Application</td>
	<td>Training</td>
    <td>Training</td>
</tr>

<tr>
	<th>12-1</th>
	<td colspan="6" align="center">L U N C H   B R E A K</td>
</tr>

<tr align="center">
	<th>1-3</th>
	<td>cyber law and compliance</td>
	<td>Software Project Management</td>
	<td>Mentor Meet</td>
	<td>cyber law and compliance</td>
	<td>training</td>
    <td>Training</td>
</tr>

<tr align="center">
	<th>3-5</th>
	<td>Fundamentals of Web Application</td>
	<td class="free-slot">Free</td>
	<td class="free-slot">Free</td>
	<td>Software Project Management</td>
	<td class="free-slot">Free</td>
    <td class="free-slot">Free</td>
</tr>
</table>

<br>

<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr>
<td align="center">1.</td>
<td align="center">19EY712</td>
<td>Employement Enrichment Skills</td>
</tr>

<tr>
<td align="center">2.</td>
<td align="center">19CS504</td>
<td>Software Project Management</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19EY706</td>
<td>Company Specific</td>
</tr>

<tr>
<td align="center">4.</td>
<td align="center">19CS418</td>
<td>Cyber law and compliance</td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">ECA-M</td>
<td>Mentor Meet</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application</td>
</tr>
</table>

</body>
</html>

```

## OUTPUT

<img width="1853" height="991" alt="image" src="https://github.com/user-attachments/assets/92b4f81f-8b55-4865-867c-e2479360f2bd" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
