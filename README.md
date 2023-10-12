# Ex03 Time Table

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

## CODE
    <html>
    <head>
        <meta charset="UTF-8">
        <title>Second Semester Timetable</title>
        <style>
            /* Add some basic CSS styling to make it visually appealing */
            body {
                font-family: Arial, sans-serif;
                background-color: #f2f2f2;
                margin: 0;
                padding: 20px;
            }
    
            h1 {
                text-align: center;
            }
    
            table {
                width: 80%;
                margin: 0 auto;
                border-collapse: collapse;
                background-color: white;
                border-radius: 5px;
                box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            }
    
            th, td {
                padding: 10px;
                text-align: center;
            }
    
            th {
                background-color: #333;
                color: rgb(255, 255, 255);
            }
    
            tr:nth-child(even) {
                background-color: #ffffff;
            }
    
            /* Add black color background to the first row from the left and the five columns of that row */
            tr:first-child {
                background-color: black;
                color: rgb(0, 0, 0);
            }
            tr:first-child td:nth-child(1), tr:first-child td:nth-child(2), tr:first-child td:nth-child(3), tr:first-child td:nth-child(4), tr:first-child td:nth-child(5), tr:first-child td:nth-child(6) {
                background-color: black;
                color: rgb(0, 0, 0);
            }
        </style>
    </head>
    <body>
        <h1>Semester Timetable</h1>
        <table>
            <tr>
                <th>Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <td>8:00 AM - 10:00 AM</td>
                <td>FWAD</td>
                <td>CD</td>
                <td>DPSD</td>
                <td>CA</td>
                <td>Mathematics</td>
                <td>C++</td>
            </tr>
            <tr>
                <td>10:00 AM - 12:00 AM</td>
                <td>ED</td>
                <td>MPMC</td>
                <td>TOC</td>
                <td>INT TO DS</td>
                <td>K & DOR</td>
                <td>IOT</td>
            </tr>
            <tr>
                <td>12:00 AM - 1:00 PM</td>
                <td>Lunch</td>
                <td>Lunch</td>
                <td>Lunch</td>
                <td>Lunch</td>
                <td>Lunch</td>
                <td>Lunch</td>
            </tr>
            <tr>
                <td>1:00 PM - 3:00 PM</td>
                <td>FWAD</td>
                <td>CA</td>
                <td>CD</td>
                <td>DPSD</td>
                <td>MATHEMATICS</td>
                <td>Elective Course</td>
            </tr>
            <tr>
                <td>3:00 PM - 5:00 PM</td>
                <td>MPMC</td>
                <td>TOC</td>
                <td>IOT</td>
                <td>ED</td>
                <td>INT TO DS</td>
                <td>K & DOR</td>
            </tr>
        </table>
    </body>
    </html>

## OUTPUT
![Web capture_5-10-2023_978_](https://github.com/Kathir-2703/FWAD-EXP-3/assets/64436376/ab3e616f-a571-40cc-8b30-33916a8ab94a)

## HTML VALIDATOR
<img width="960" alt="KFWAD1output pdf" src="https://github.com/Kathir-2703/FWAD-EXP-3/assets/64436376/198f2720-2fb6-44f8-89c9-114ac9c765f2">

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
