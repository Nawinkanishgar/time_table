

Register Number : 212224040215

# Ex02 Time Table

# AIM
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
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <html><head><meta http-equiv="Content-Type" content="text/html; charset=windows-1252"></head>
    <style>
        body{
            background-color: rgb(236, 135, 250);
            background:linear-gradient(to right, #e2e2e2,#c9d6ff);
            font-family: Arial, Helvetica, sans-serif;
        }
    </style>
    <body>
        <img src="logo.png">
            <table border="1" cellspacing="10" cellpadding="2">
                <caption>SLOT TIME TABLE - B Harshala Reddy (212224040050)</caption>
                <tbody><tr bgcolor="lavender">
                   <th bgcolor="violet">DAY/TIME</th>
                   <th>Monday</th>
                   <th>Tuesday</th>
                   <th>Wednesday</th>
                   <th>Thursday</th>
                   <th>Friday</th>
                   <th>Saturday</th>
                </tr>
                    <tr bgcolor="beige">
                        <td bgcolor="violet">8-10</td>
                        <td>FREE SLOT</td>
                        <td>WEB</td>
                        <td>WEB</td>
                        <td>FREE SLOT</td>
                        <td>WEB</td>
                        <td>WEB</td>
                    </tr>
                <tr bgcolor="beige">
                    <td bgcolor="violet">10-12</td>
                    <td>FREE SLOT</td>
                    <td>PYTHON</td>
                    <td>FREE SLOT</td>
                    <td>PYTHON</td>
                    <td>PYTHON</td>
                    <td>CLOUD</td>
                </tr>
                <tr bgcolor="beige">
                    <td bgcolor="violet">12-1</td>
                   <td colspan="6" align="center">LUNCH</td>
                </tr>
                <tr bgcolor="beige">
                    <td bgcolor="violet">1-3</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>MENTOR MEET</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>PYTHON</td>
                </tr>
                <tr bgcolor="beige">
                    <td bgcolor="violet">3-5</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>CLOUD</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                </tr>
            </tbody></table>
            <table border="1" cellspacing="10" cellpadding="2">
                <tbody><tr bgcolor="sky blue">
                    <th bgcolor="sky blue">S.NO</th>
                    <th>Course code</th>
                    <th>Course name</th>
                </tr>
                <tr>
                    <td>1.</td>
                    <td>19AI301</td>
                    <td>PYTHON PROGRAMMING</td>
                </tr>
                <tr>
                    <td>2.</td>
                    <td>19AI414</td>
                    <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
                </tr>
                <tr>
                    <td>3.</td>
                    <td>19AI541</td>
                    <td>CLOUD COMPUTING</td>
                </tr>
                <tr>
                    <td>4.</td>
                    <td>ECA-M-SCOFT</td>
                    <td>MENTOR MEET</td>
                </tr>

            </body></table>
        
    </body></html>
```
# OUTPUT
<img width="1786" height="989" alt="image" src="https://github.com/user-attachments/assets/434b10e2-cda0-49e2-bf0f-3cd9e2399b51" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
