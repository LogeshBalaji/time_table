# Ex03 Time Table
# Date:26.11.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

## PROGRAM


~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable </title>
</head>
<body>
   <center><div><img src="WEB_LOGO-01.png" height="150px" width="1000" alt="SEC logo"></div></center>
   <center><div><h1>SLOT TIME TABLE-LOGESH B(24900577)</h1></div></center>
    <center><table border="5">
     <tr>
        <th bgcolor="green" style="color: aliceblue;">time day</th>
        <th bgcolor="green" style="color: aliceblue;">8-10</th>
        <th bgcolor="green" style="color: aliceblue;">10-12</th>
        <th rowspan="7"  bgcolor="lightblue" style="color: black;"><p style="writing-mode: vertical-rl;">LUNCH</p></th>
        <th bgcolor="green" style="color: aliceblue;">1-3</th>
        <th bgcolor="green" style="color: aliceblue;">3-5</th>
     </tr>
     <tr>
        <th bgcolor="green" style="color: aliceblue;">monday</th>
        <td bgcolor="lightblue" style="color: black;">free slot </td>
        <td bgcolor="lightblue" style="color: black;"> BEEE</td>
        <td bgcolor="lightblue" style="color: black;">fundamentals of Wed application development</td>
        <td bgcolor="lightblue" style="color: black;">free slot </td>
     </tr>
     <tr>
        <th bgcolor="green" style="color: aliceblue;"> tuesday</th>
        <td bgcolor="lightblue" style="color: black;">Career Development Skills </td>
        <td bgcolor="lightblue" style="color: black;">BEEE </td>
        <td bgcolor="lightblue" style="color: black;">Statistics and Numerical Methods</td>
        <td bgcolor="lightblue" style="color: black;">free slot</td>
     </tr>
        <th bgcolor="green" style="color: aliceblue;">wednesday</th>
        <td bgcolor="lightblue" style="color: black;">Statistics and Numerical Methods</td>
        <td bgcolor="lightblue" style="color: black;">Communicative English </td>
        <td bgcolor="lightblue" style="color: black;">Mentor meet </td>
        <td bgcolor="lightblue" style="color: black;">free slot </td>
     </tr>
     <tr>
        <th bgcolor="green" style="color: aliceblue;">Thursday</th>
        <td bgcolor="lightblue" style="color: black;">Introduction to Machine Learning </td>
        <td bgcolor="lightblue" style="color: black;"> probability of Queueing Models</td>
        <td bgcolor="lightblue" style="color: black;">Fundamentals of c Programming</td>
        <td bgcolor="lightblue" style="color: black;"> free slot</td>
     </tr>
     <tr>
        <th bgcolor="green" style="color: aliceblue;">friday</th>
        <td bgcolor="lightblue" style="color: black;"> Introduction to Machine Learning</td>
        <td bgcolor="lightblue" style="color: black;">fundamentals of Wed application development</td>
        <td bgcolor="lightblue" style="color: black;">Fundamentals of c Programming</td>
        <td bgcolor="lightblue" style="color: black;">free slot </td>
     </tr>
     <tr>
        <th bgcolor="green" style="color: aliceblue;">saturday</th>
        <td bgcolor="lightblue" style="color: black;">Communicative English </td>
        <td bgcolor="lightblue" style="color: black;">fundamentals of Wed application development</td>
        <td bgcolor="lightblue" style="color: black;">probability of Queueing Models</td>
        <td bgcolor="lightblue" style="color: black;">free slot </td>
        </tr></center>
    </table>
    </body>
    <hr>
    <table border="5" width="1000">
        <body>
            <tr>
                <th>S.NO</th>
                <th>SUBJUCT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19EE305</td>
                <td>Basic Electrical,Electronics and Measurement Engineering</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EY708</td>
                <td>Career Development Skills</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19MA211</td>
                <td>Statistics and Numerical Methods</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>6</td>
                <td>ECA-M</td>
                <td>SCOFT - Mentor Meet</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19AI410</td>
                <td>Introduction to Machine Learning</td>
            </tr>
            <tr>
                <td>8</td>
                <td>19MA222</td>
                <td>Probability and Queueing Models</td>
            </tr>
            <tr>
                <td>9</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
        </body>
    </table>
    <hr>
</html>
~~~



## OUTPUT
![Screenshot 2024-11-26 233805](https://github.com/user-attachments/assets/45226ee7-db3d-4e58-bfe1-be01121211dd)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
