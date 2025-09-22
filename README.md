# Ex03 Time Table
## Date:

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
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Slot Timetable</title>
    
  </head>

  <body>
    
    <img
      src="logo.png"  width="500"/> 
    <h3 class="name">SLOT TIMETABLE - UDHAYA PRAKASH(212224240177)</h3>
    <table border="1" class="table1">
      <tr class="row1" >
        <th bgcolor="skyblue">Day/Time</th>
        <th bgcolor="skyblue">Monday</th>
        <th bgcolor="skyblue">Tuesday</th>
        <th bgcolor="skyblue">Wednesday</th>
        <th bgcolor="skyblue">Thursday</th>
        <th bgcolor="skyblue">Friday</th>
       
      </tr>
      <tr>
        <td bgcolor="lavender">8-10</td>
        <td bgcolor="pink">web</td>
        <td bgcolor="pink">os</td>
        <td colspan="2" bgcolor="pink">beee</td>
        <td bgcolor="pink">timeseries</td>
        
        
      </tr>
      <tr>
        <td bgcolor="lavender">10-12</td>
        <td bgcolor="pink">os</td>
        <td bgcolor="pink">beee</td>
        <td bgcolor="pink">web</td>
        <td bgcolor="pink">time series</td>
        <td bgcolor="pink">evs</td>
        
      </tr>
      <tr>
        <td bgcolor="lavender">12-1</td>
        <th colspan="6" class="x" bgcolor="beige">LUNCH BREAK</th>
      </tr>
      <tr>
        <td bgcolor="lavender">1-3</td>
        <td bgcolor="pink">reasoning</td>
        <td bgcolor="pink">os</td>
        <td bgcolor="pink">timeseries</td>
        <td bgcolor="pink">WEB</td>
        <td bgcolor="pink">beee</td>
        
       
      </tr>
      <tr>
        
        
        
      </tr>
    </table>
    <br />
    <br />
    <table border="1" class="table2">
      <tr>
        <th bgcolor="orange">S.No.</th>
        <th bgcolor="orange">Subject Code</th>
        <th bgcolor="orange">Subject Name</th>
      </tr>
      <tr>
        <td bgcolor="violet">1.</td>
        <td bgcolor="yellow">19EC408</td>
        <td bgcolor="yellow">operting system</td>
      </tr>
      <tr>
        <td bgcolor="violet">2.</td>
        <td bgcolor="yellow">19AI403</td>
        <td bgcolor="yellow">Beee</td>
      </tr>
      <tr>
        <td bgcolor="violet">3.</td>
        <td bgcolor="yellow">19CS417</td>
        <td bgcolor="yellow">compter networks</td>
      </tr>
      <tr>
        <td bgcolor="violet">4.</td>
        <td bgcolor="yellow">19AI414</td>
        <td bgcolor="yellow">Fundamentals of Web Applications Development (WEB)</td>
      </tr>
      <tr>
        <td bgcolor="violet">5.</td>
        <td bgcolor="yellow">19CS504</td>
        <td bgcolor="yellow">EVS</td>
      </tr>
      <tr>
        <td bgcolor="violet">6.</td>
        <td bgcolor="yellow">19EN616</td>
        <td bgcolor="yellow">Reasoning ability</td>
      </tr>
      <tr>
        <td bgcolor="violet">7.</td>
        <td bgcolor="yellow">19EY704</td>
        <td bgcolor="yellow">Time series</td>
      </tr>
    </table>
  </body>
</html>



## OUTPUT
<img width="1920" height="1200" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/f9ac9758-f74f-407a-8ca4-46d8ab141ee0" />




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
