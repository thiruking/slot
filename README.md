# Ex03 Time Table
## Date:17-11-2024

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
<body>
    <center>
    <img src="slot/thiru/slotapp/static/WEB_LOGO-01.png">
    
    <br>
    <br>
    <br>
     <h2>SLOT TIME TABLE - THIRUMALAI K (24900491)</h2>
        <table border="2">
            <style>
                table{ 
                    width: 50%;
                    height: 30%;
                }
            </style>
        <TR>
            <th align="center" bgcolor="green">DAYS</th>
            <Th align="center" bgcolor="green">8-10</Th>
            <Th align="center" bgcolor="green"> 10-12</Th>
            <Th align="center" bgcolor="green">12-1</Th>
            <Th align="center" bgcolor="green">1-3</Th>
            <Th align="center" bgcolor="green">3-5</Th>
        </TR >
    <tr>
        <th align="center" bgcolor="green">MONDAY</th>
        <TD align="center" bgcolor="sky blue">---</TD>
        <TD  align="center" bgcolor="sky blue">FWAD</TD>
        <TD style="position: vertical;" rowspan="6" align="center" bgcolor="sky blue">LUNCH</TD>
        <TD  align="center" bgcolor="sky blue">PRINCIPLE OF CHEMISTRY</TD>
        <TD align="center" bgcolor="sky blue">---</TD>
    </tr>
    <TR>
       <th align="center"bgcolor="green" >TUESDAY</th>
       <td align="center" bgcolor="sky blue">---</td>
       <td align="center" bgcolor="sky blue">EDM</td>
       <td align="center" bgcolor="sky blue">DE</td>
       <td align="center" bgcolor="sky blue">---</td>
    </TR>
    <tr>
        <th align="center"bgcolor="green">WEDNESDAY</th>
        <td  align="center" bgcolor="sky blue">DE</td>
        <td align="center" bgcolor="sky blue">FWAD</td>
        <td align="center" bgcolor="sky blue">MENTOR MEET</td>
        <TD align="center" bgcolor="sky blue">---</TD>
    </tr>
    <tr>
        <th align="center"bgcolor="green">THURSDAY</th>
        <td  align="center" bgcolor="sky blue">---</td>
        <td align="center" bgcolor="sky blue"> PRINCIPLE OF CHEMISTRY</td>
        <td  align="center" bgcolor="sky blue">CARRIER SKILL</td>
        <td align="center" bgcolor="sky blue">---</td>
    </tr>
    <tr>
        <th align="center"bgcolor="green">FRIDAY</th>
        <TD align="center" bgcolor="sky blue">---</TD>
        <td align="center" bgcolor="sky blue">BEEE</td>
        <td align="center" bgcolor="sky blue">EDM</td>
        <td align="center" bgcolor="sky blue">---</td>
    </tr>
    <tr>
        <th align="center"bgcolor="green">SATURDAY</th>
        <td align="center" bgcolor="sky blue">---</td>
        <td align="center" bgcolor="sky blue">---</td>
        <td align="center" bgcolor="sky blue">FWAD</td>
        <td align="center" bgcolor="sky blue">BEEE</td>
    </tr>
    
    </table>
    <br>
    <br>
    <br>
    
    
        <table border="2" >
            <tr>
            <td>S.NO</td>
            <td>SUB CODE</td>
            <td>SUBJECT</td>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td> 
            <td>Fundamental of WEB DEVELOPEMENT</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19CY205</td>
            <td>PRINCIPLE OF CHEMISTRY</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19EE305</td>
            <td>Basic Electrical,Electronic and Mesurement Engineering</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19EY708</td>
            <td>Career Development Skills</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19AI302</td>
            <td>ENGINEERING DESIGN AND MODELLING</td>
        </tr>
        <tr>
            <td>7</td>
            <td>EC-M-SCOFT</td>
            <td>Mentor Meet</td>
        </tr>
       
        </table>
    </center>
    </body>



## OUTPUT

![screenshot 2024-11-17 ](https://github.com/user-attachments/assets/a0d8cffd-5bfb-44b4-8b1f-6b12b87e81de)





## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
