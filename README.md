# Ex.05 Design a Website for Server Side Processing
# Date:12-4-2025
# AIM:
To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side.

# FORMULA:
P = I2R
P --> Power (in watts)
 I --> Intensity
 R --> Resistance

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Create python programs for views and urls to perform server side processing.

## Step 5:
Create a HTML file to implement form based input and output.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<html>
<head>
    <title>Calculate</title>
</head>
<body>
    <h1 allign="'center">Calculating Power of a Lamp</h1>
    <form action="{% url 'home' %}" method='post'>
        {% csrf_token %}

        intensity:
        <input type="text" name="intensity-input"><br>

        resistance:
        <input type="text" name="resistance-input"><br>

        <button type="submit">Calculate</button>
        <p align="center">The power of the lamp is: {{ output }}</p>
    </form>
</body>
</html>
```
# SERVER SIDE PROCESSING:
![alt text](<WhatsApp Image 2025-04-12 at 21.27.15_95586800.jpg>)
# HOMEPAGE:
![alt text](<Screenshot 2025-04-12 212643.png>)
# RESULT:
The program for performing server side processing is completed successfully.
