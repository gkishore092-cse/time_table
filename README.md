# Ex03 Time Table
# Date:3/10/2025
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

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SLOT TIMETABLE</title>
</head>
<body>
    <center>
        <img src="sec.png" height="100" width="540"    </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4"border="5" bgcolor="cyan">
            <caption><b>SLOT TIME TABLE - KISHORE G (25009791)</b></caption>
            <tr align="center">
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">8-10</th>
                <th bgcolor="yellow">10-12</th>
                <th bgcolor="yellow">12-1</th>
                <th bgcolor="yellow">1-3</th>
                <th bgcolor="yellow">3-5</th>
                
     </tr>
     <tr align ="center">
        <th bgcolor="yellow">MONDAY</th>
        <td> FWAD</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</th>
        <td> FREE</td>
        <td> FREE</td>
        <td>FREE</td> 
     
     </tr>     
     
     <tr align="center">
        <th bgcolor ="yellow">TUESDAY</th>
        <td> FREE</td>
        <td>FREE</td>
        <td> FREE</td>
        <td> FREE</td>
        <td>FREE</td>
    
     </tr>  
     <tr align="center">
        <th bgcolor ="yellow">WEDNESDAY</th>
        <td> FWAD</td>
        <td>FWAD</td>
        <td> FREE</td>
        <td> MENTOR MEETING</td>
        <td>FUNDAMENTALS OF C PROGRAMMING </td>
     </tr>  
     <tr align="center">
        <th bgcolor ="yellow">THURSDAY</th>
        <td> FREE</td>
        <td>FREE</td>
        <td> FREE</td>
        <td> FREE</td>
        <td>FREE</td>

     </tr>
     <tr align="center">
        <th bgcolor ="yellow">FRIDAY</th>
        <td> FREE</td>
        <td>FWAD</td>
        <td>FREE </td>
        <td>FUNDAMENTALS OF C PROGRAMMING </td>
        <td>FREE</td>
        
     </tr>   
     <tr align="center">
        <th bgcolor ="yellow">SATURDAY</th>
        <td> FREE</td>
        <td>FWAD</td>
        <td> FREE</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td> FUNDAMENTALS OF C PROGRAMMING</td>
        
     </tr>  

     </table>
     <table align="center" cellspacing="2" cellpadding="4"  border="2"  >
        <tr align="center">
            <th> S.NO</th>
            <th>Subject code</th>
            <th>Subject Name</th>
        </tr>
        <tr align="center">
            <td> 1.</td>
            <td>19AI414</td>
            <td>FWAD </td>
        </tr>
        <tr align="center">
            <td>2.</td>
            <td> 19AI304</td>
            <td>FUNDAMENTALS OF C PROGRAMMING </td>
        </tr>
     </table>
</body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2025-10-03 192542.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
