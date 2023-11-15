# Ex.08 Design of a Standard Calculator
## Date:
26/10/23

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
<!DOCTYPE html> 
<html> 
  
<head> 
    <title>HTML Calculator</title> 
  
    <!-- For styling -->
    <style> 
        table { 
            border: 1px solid black; 
            margin-left: auto; 
            margin-right: auto; 
        } 
          
        input[type="button"] { 
            width: 100%; 
            padding: 20px 40px; 
            background-color: cyan; 
            color: white; 
            font-size: 24px; 
            font-weight: bold; 
            border: none; 
            border-radius: 5px; 
        } 
          
        input[type="text"] { 
            padding: 20px 30px; 
            font-size: 24px; 
            font-weight: bold; 
            border: none; 
            border-radius: 5px; 
            border: 2px solid black; 
        } 
    </style> 
</head> 
  
<body> 
  
    <!-- Create table -->
    <table id="calcu"> 
        <tr> 
            <td colspan="3"> 
                <input type="text" id="result"> 
            </td> 
            <td><input type="button" value="c"></td> 
        </tr> 
  
        <tr> 
            <td><input type="button" value="1"></td> 
            <td><input type="button" value="2"></td> 
            <td><input type="button" value="3"></td> 
            <td><input type="button" value="/"></td> 
        </tr> 
        <tr> 
            <td><input type="button" value="4"></td> 
            <td><input type="button" value="5"></td> 
            <td><input type="button" value="6"></td> 
            <td><input type="button" value="*"></td> 
        </tr> 
        <tr> 
            <td><input type="button" value="7"></td> 
            <td><input type="button" value="8"></td> 
            <td><input type="button" value="9"></td> 
            <td><input type="button" value="-"></td> 
        </tr> 
        <tr> 
            <td><input type="button" value="0"></td> 
            <td><input type="button" value="."></td> 
            <td><input type="button" value="="></td> 
            <td><input type="button" value="+"></td> 
        </tr> 
    </table> 
</body> 
  
</html>  

## OUTPUT:
![Screenshot (6)](https://github.com/kavisree86/Calc/assets/145759687/497c1e0d-7f3f-4a6b-ab24-8a4c036c39da)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
