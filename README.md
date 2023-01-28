# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
~~~
{% load static %}

<html>
    <head>
        <title>SEC</title>
        <link rel="stylesheet" type="text/css" href="{% static 'css/index.css' %}">
    </head>
    <body>
    
        <img src="{% static 'img/logo.png' %}" alt="My image" id="img">
        
        <table>
            <tr id="tr">
                <th></th>
                <th></th>
                <th>Time Table</th>
                <th></th>
                <th></th>
            </tr>
            <tr>
                <th>Reference ID:</th>
                <th>22008489</th>
                <th></th>
                <th>Name:</th>
                <th>R.Vignesh</th>
                <th></th>
            </tr>
            <tr>
                <th>Day</th>
                <th>1</th>
                <th>2</th>
                <th>3</th>
                <th>4</th>
                <th>5</th>
            </tr>
            <tr>
                <td>Monday</td>
                <td>Python</td>
                <td>Web</td>
                <td>Chemistry</td>
                <td>Physics</td>
                <td>Maths</td>
            </tr>
            <tr>
                <td>Tuesday</td>
                <td>Web</td>
                <td>Engilsh</td>
                <td>Maths</td>
                <td>Physics</td>
                <td>Chemistry</td>
            </tr>
            <tr>
                <td>Wednesday</td>
                <td>Ed</td>
                <td>English</td>
                <td>Python</td>
                <td>c</td>
                <td>Maths</td>
            </tr>
            <tr>
                <td>Thursday</td>
                <td>Design</td>
                <td>C</td>
                <td>C++</td>
                <td>Python</td>
                <td>Chemistry</td>
            </tr>
            <tr>
                <td>Friday</td>
                <td>EDM</td>
                <td>English</td>
                <td>P.E</td>
                <td>Yoga</td>
                <td>Chemistry</td>
            </tr>
        </table>
    
    </body>
</html>


~~~
# OUPUT
![output2](/Screenshot%20from%202023-01-18%2022-52-52.png)

# RESULT
The program displays the timetable

