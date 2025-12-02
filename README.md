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
```html
<!DOCTYPE html>
<html>
<head>
<title>Slot Timetable</title>

<style>
    body {
        background-color: #faf7f2;
        font-family: Arial, sans-serif;
        color: #3e3e3e;
        margin: 20px;
    }

    h1 {
        text-align: center;
        font-weight: 600;
        letter-spacing: 1px;
    }

    table {
        width: 70%;
        margin: 20px auto;
        border-collapse: collapse;
        background: #ffffff;
        box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }

    caption {
        padding: 10px;
        font-size: 18px;
        font-weight: bold;
        color: #444;
    }

    th, td {
        border: 1px solid #ddd;
        padding: 10px;
        text-align: center;
    }

    th {
        background-color: #f2e9dd;
        font-weight: bold;
    }

    .free-slot {
        background-color: #f7efe6;
        color: #555;
        font-style: italic;
    }

    .lunch {
        background: #f9f3ec;
        font-weight: bold;
    }
</style>

</head>

<body>

<h1>SLOT TIMETABLE</h1>

<table>
<caption>SLOT TIMETABLE - Kamlesh Y (212224100029)</caption>

<tr>
    <th>Day/Time</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
    <th>Saturday</th>
</tr>

<tr>
    <th>8-10</th>
    <td>Training</td>
    <td>Employment Enrichment Skills</td>
    <td>Training</td>
    <td>Company Specific</td>
    <td>Training</td>
    <td>Fundamentals of Web App</td>
</tr>

<tr>
    <th>10-12</th>
    <td>Training</td>
    <td>Training</td>
    <td>Training</td>
    <td>Fundamentals of Web App</td>
    <td>Training</td>
    <td>Training</td>
</tr>

<tr>
    <th>12-1</th>
    <td class="lunch" colspan="6">LUNCH BREAK</td>
</tr>

<tr>
    <th>1-3</th>
    <td>Cyber Law & Compliance</td>
    <td>Software Project Management</td>
    <td>Mentor Meet</td>
    <td>Cyber Law & Compliance</td>
    <td>Training</td>
    <td>Training</td>
</tr>

<tr>
    <th>3-5</th>
    <td>Fundamentals of Web App</td>
    <td class="free-slot">Free</td>
    <td class="free-slot">Free</td>
    <td>Software Project Management</td>
    <td class="free-slot">Free</td>
    <td class="free-slot">Free</td>
</tr>
</table>

<table>
<tr>
    <th>S. No.</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
</tr>

<tr><td>1.</td><td>19EY712</td><td>Employment Enrichment Skills</td></tr>
<tr><td>2.</td><td>19CS504</td><td>Software Project Management</td></tr>
<tr><td>3.</td><td>19EY706</td><td>Company Specific</td></tr>
<tr><td>4.</td><td>19CS418</td><td>Cyber Law & Compliance</td></tr>
<tr><td>5.</td><td>ECA-M</td><td>Mentor Meet</td></tr>
<tr><td>6.</td><td>19AI414</td><td>Fundamentals of Web Application</td></tr>
</table>

</body>
</html>


```

## OUTPUT

<img width="1853" height="991" alt="image" src="https://github.com/user-attachments/assets/92b4f81f-8b55-4865-867c-e2479360f2bd" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
