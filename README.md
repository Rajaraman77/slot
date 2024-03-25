# Ex03 Time Table
## Date:25-03-2024

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
        <title>My TimeTable</title>
    </head>
    <body>
         <center>
        <center>
        <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-03-22 134619.png" height="100">
        </center>
        <table border="3" bgcolor="SKY BLUE">
            <caption align="center"><b>SLOT TIME-TABLE RAJARAMAN V (212223110048)</b></caption>
            <tr bgcolor="ORANGE">
               <th bgcolor="violet">DAY</th>
               <th colspan="2">8:00-10:00</th>
               <th colspan="2">10:00-12:00</th>
               <th colspan="2">12:00-1:00</th>
               <th colspan="2">1:00-3:00</th>
               <th colspan="2">3:00-5:00</th>
            </tr>
            <tr>
                <th bgcolor="violet">MONDAY</th>
                <td colspan="2">WEB DEVELOPMENT</td>
               <td colspan="2">FREE</td>
               <td colspan="2" rowspan="5" align="center" bgcolor="yellow">LUNCH</td>
               <td colspan="2">COMPUTER NETWORKS</td>
               <td colspan="2">FREE</td>
            </tr>
            <tr>
                <th bgcolor="Violet">TUESDAY</th>
                <td colspan="2">DIGITAL ELECTRONICS</td>
                <td colspan="2">C PROGRAMMING</td>
                <td colspan="4" align="center">FREE</td>
            </tr>
            <tr>
                <th bgcolor="violet">WEDNESDAY</th>
                <td colspan="2">THEORY OF COMPUTATION</td>
                <td colspan="2">PROBABLITY</td>
                <td colspan="2" align="center">CREATIVE SKILLS</td> 
                <td colspan="2">FREE</td>
            </tr>
            <tr>
                <th bgcolor="violet">THURSDAY</th>
                <td colspan="2">DIGITAL ELECTRONICS</td>
                <td colspan="2">C PROGRAMMING</td>
                <td colspan="2">WEB DEVELOPMENT</td> 
                <td colspan="2">FREE</td
            </tr>
            <tr>
                <th bgcolor="violet">FRIDAY</th>
                <td colspan="2">FREE</td>
                <td >COMPUTER NETWORKS</td>              
                <td >     </td>
                <td colspan="2">WEB DEVELOPMENT</td>
                <td colspan="2">FREE</td>

            </tr>

        </table>
        <br><br>
        <table border="3" bgcolor=" pink">
            <tr bgcolor="cyan">
                <th bgcolor="cyan">S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td align="center" bgcolor="cyan">1.</td>
                <td align="center" bgcolor="red">19AI414</td>
                <td>WEB DEVELOPMENT</td>
            </tr>
            <tr>
                <td align="center" bgcolor="cyan">2.</td>
                <td align="center" bgcolor="red">19MA222</td>
                <td>PROBABLITY AND QUEEUING MODALS</td>
            </tr>
            <tr>
                <td align="center" bgcolor="cyan">3.</td>
                <td align="center" bgcolor="red">19EY702</td>
                <td>CREATIVE SKILLS</td>
            </tr>
            <tr>
                <td align="center" bgcolor="cyan">4.</td>
                <td align="center" bgcolor="red">19AI304</td>
                <td>C PROGRAMMING</td>
            </tr>
            <tr>
                <td align="center" bgcolor="cyan">5.</td>
                <td align="center" bgcolor="red">19CS406</td>
                <td>COMPUTER NETWORKS</td>
            </tr>
            <tr>
                <td align="center" bgcolor="cyan">6.</td>
                <td align="center" bgcolor="red">19CS407</td>
                <td>THEORY OF COMPUTATION</td>
            </tr>
            <tr>
                <td align="center" bgcolor="cyan">7.</td>
                <td align="center" bgcolor="red">19EE404</td>
                <td>DIGITAL ELECTRONICS</td>
            </tr>
            
            
        </table>
</center>
    </body>
</html>
```

## OUTPUT
![Screenshot 2024-03-25 093821](https://github.com/Rajaraman77/slot/assets/150319383/758e8bdf-c7cb-4b08-b3fc-618005d36ebd)
![Screenshot 2024-03-25 093609](https://github.com/Rajaraman77/slot/assets/150319383/c97fd620-d551-44c3-9d77-1fd8d06cf3e7)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
