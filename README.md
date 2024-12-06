# Ex03 Time Table
# Date:
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIME TABLE</title>
    <style>
        table,th,td{
            border: 5px black;
            border-style: groove;
            border-collapse:collapse;
            text-size-adjust: 10px;
            margin: auto;}
            th{
                background-color: navy;
                font-size: 20px;
            }
            td{
                background-color: beige;
                padding: 10px;
                font-size: 20px;
            }
    </style>
</head>
<body>
    <table style="text-align: center;">
        <p style="text-align: center;">
        <img src="c:\web developmebt\WhatsApp Image 2024-12-02 at 14.28.05_a1ab6877.jpg" width="50%" height="80%" class="center">
    </p>
    <h2 style="text-align: center;">SLOT TIME TABLE-JEYA SOUNDHAR P S(24900371)</h2>
    <tr style="text-align: center;">
        <th>DAY/TIMINGS</th>
        <th><br>MONDAY</th>
        <th><br>TUESDAY</th>
        <th><br>WEDNESDAY</th>
        <th><br>THURSDAY</th>
        <th><br>FRIDAY</th>
        <th><br>SATURDAY</th>
    </tr>
    <tr style="text-align: center;">
        <th>8-10</th>
        <td>FREE TIME</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>MATHS</td>
        <td>FREE TIME</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>EDM</td>
        </tr>
        <tr style="text-align: center;">
            <th>10-12</th>
            <td>EDM</td>
            <td>PHYSICS</td>
            <td>PYTHON</td>
            <td>MATHS</td>
            <td>WEB APPLICATION</td>
            <td>WEB APPLICATION</td>
        </tr>
        <tr style="text-align: center;">
            <th>12-1</th>
            <td colspan="6">LUNCH</td>
        </tr>
        <tr style="text-align: center;">
            <th>1-3</th>
            <td>WEB APPLICATION</td>
            <td>EVS</td>
            <td>MENTOR MEETING</td>
            <td>CARRIER DEVELOPMENT SKILLS</td>
            <td>PYTHON</td>
            <td>PHYSICS</td>
        </tr>
        <tr>
            <th>3-5</th>
            <td colspan="6">FREE TIME</td>
        </tr>
    </table>
    <table style="text-align: center;">
        <tr style="text-align: center;">
            <th> S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr style="text-align: center;">
            <td>1</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION</td>
        </tr>
        <tr style="text-align: center;">
            <td>2</td>
            <td>19AI301</td>
            <td>PYTHON PROGRAMMING</td>
        </tr>
        <tr style="text-align: center;">
            <td>3</td>
            <td>19EY708</td>
            <td>CARRIER DEVELOPMENT AND SKILLS</td>
        </tr>
        <tr style="text-align: center;">
            <td>4</td>
            <td>19EN101</td>
            <td>COMMUNICATIVE ENGLISH</td>
        </tr>
        <tr style="text-align: center;">
            <td>5</td>
            <td>SH4801</td>
            <td>ENVIRONMENTAL SCIENCES AND SUSTAINABILITY</td>
        </tr>
        <tr style="text-align: center;">
            <td>6</td>;
            <td>ECA-M-SCOFT</td>
            <td>MENTOR MEETING</td>
        </tr>
        <tr style="text-align: center;">
        <td>7</td>
        <td>SH3214</td>
        <td>PHYSICS FOR QUANTUM COMPUTING</td>
        </tr>
        <tr style="text-align: center;">
            <td>8</td>;
            <td>19MA201</td>
            <td>CALCULUS AND MATRIX ALGEBRA</td>
            </tr>
            <tr style="text-align: center;">
                <td>9</td>
                <td>19AI302</td>
                <td>ENGINEERING DESIGN AND MODELLING</td>
            </tr>
    </table>
    
    
</body>
</html>
# OUTPUT
![Screenshot 2024-12-06 221340](https://github.com/user-attachments/assets/8a22290a-4616-4a48-9b81-3cb98fd1a523)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
