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
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
    <center>
       <img src="/static/sec logo.png" width="1500px" height="120px">
    </center>
<head>
<title>Timetable</title> 
<style>
    table,th,td{
         border:6px gray;
         border-style:groove;
         border-collapse:collapse;
         margin: auto;
    }
     td{
         padding: 10px;
    }
</style>   
</head>
<body style="background-color: yellowgreen;">
    <h1 style="text-align: center"> Timetable</h1>
    <table>
        <tr>
            <th style="background-color:blueviolet">Day</th>
            <th style="background-color:blueviolet">8-10</th>
            <th style="background-color:blueviolet">10-12</th>
            <th style="background-color:blueviolet">12-1</th>
            <th style="background-color:blueviolet">1-3</th>
            <th style="background-color:blueviolet">3-5</th>
        </tr>
        <tr>
            <th style="background-color:blueviolet">Monday</th>
            <td style="background-color:pink"></td>
            <td style="background-color:pink">Web</td>
            <td rowspan="6" style="background-color:pink">L<Br>U<br>N<br>C<br>H</td>
            <td style="background-color:pink">Car Dev</td>
            <td style="background-color:pink"></td>
        </tr>
        <tr>
            <th style="background-color:blueviolet">Tuesday</th>
            <td style="background-color:pink"></td>
            <td style="background-color:pink">Phy</td>
            <td style="background-color:pink">Com Eng</td>
            <td style="background-color:pink"></td>
        </tr>
        <tr>
            <th style="background-color:blueviolet">Wednesday</th>
            <td style="background-color:pink"></td>
            <td style="background-color:pink">D.E</td>
            <td style="background-color:pink">Men Met</td>
            <td style="background-color:pink"></td>
        </tr>
        <tr>
            <th style="background-color:blueviolet">Thursday</th>
            <td style="background-color:pink"></td>
            <td style="background-color:pink">Com Eng</td>
            <td style="background-color:pink">Web</td>
            <td style="background-color:pink"></td>
        </tr>
        <tr>
            <th style="background-color:blueviolet">Friday</th>
            <td style="background-color:pink">Prob</td>
            <td style="background-color:pink"></td>
            <td style="background-color:pink">Hum Val</td>
            <td style="background-color:pink"></td>
        </tr>
        <tr>
            <th style="background-color:blueviolet">Saturday</th>
            <td style="background-color:pink">D.E</td>
            <td style="background-color:pink">Prob</td>
            <td style="background-color:pink">Phy</td>
            <td style="background-color:pink">Web</td>
        </tr>
    
    </table>
</body>
</html>     
<br>





</br>
<html>
<style>
    table,th,td{
        border:6px black
        border-style:groove;
        border-collapse:collapse;
        margin: auto;
    }
        td{
            padding:10px; 
    }
</style>
<body>
    <table>
        <tr>
             <th style="background-color: blueviolet;">slots</th>
             <th style="background-color: blueviolet;">subjects</th>
        </tr>
             <td style="background-color: blueviolet;">19A1414</td>
             <td style="background-color:pink ;">Fundamentals of Web Application development</td>
        <tr>
             <td style="background-color: blueviolet;">19EE404</td>
             <td style="background-color:pink ;">Digital Electronics</td>
        </tr>
        <tr>
             <td style="background-color: blueviolet;">19EN101</td>
             <td style="background-color:pink ;">Communicative English</td>
        </tr>
        <tr>
             <td style="background-color: blueviolet;">19EY708</td>
             <td style="background-color:pink ;">Career Development</td>
        </tr>
        <tr>
             <td style="background-color: blueviolet;">19MA222</td>
             <td style="background-color:pink ;">Probability and queueing Models</td>
        </tr>
        <tr>
             <td style="background-color: blueviolet;">SH3214</td>
             <td style="background-color:pink ;">Physics for Quantum Computing</td>
        </tr>
        <tr>
            <td style="background-color: blueviolet;">SH7801</td>
            <td style="background-color:pink ;">Human Values and professional Ethics</td>
        </tr>
    </table>
</body>
```
# OUTPUT 

![alt text](<Screenshot 2024-12-05 173747.png>)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
