# TechneuroInternship_TemperatureConversion_Python
Task:1 Temperature Conversion Script:
Convert temperatures from Celsius to Fahrenheit using a Python script. It's a fundamental and practical program that beginners can grasp.

1. The code begins with a couple of print statements, which display a header for the program:

print('By SHRUTI GODSE\n')
print('TEMPERATURE CONVERSION Python program ')
print('(Converting Temperatures from CELSIUS to FAHRENHEIT):- \n')

These lines print some information about the program, including the author's name and a brief description of what the program does.

2. The code defines a function called celsius_to_fahrenheit that takes a temperature in Celsius as an argument and returns the equivalent temperature in Fahrenheit:

def celsius_to_fahrenheit(celsius):
    fahrenheit = (celsius * 9/5) + 32
    return fahrenheit
    
This function uses the formula (Celsius * 9/5) + 32 to convert Celsius to Fahrenheit.

3. The program then prompts the user to enter a temperature in Celsius:

celsius = float(input("Enter temperature in Celsius: "))

The input function is used to get user input, and float is used to convert the input to a floating-point number.

4. The program calls the celsius_to_fahrenheit function with the user-input Celsius temperature to get the equivalent temperature in Fahrenheit:

fahrenheit = celsius_to_fahrenheit(celsius)

5. Finally, the program displays the result using the print function:

print("Temperature in Fahrenheit:", fahrenheit)

This line prints the converted temperature in Fahrenheit.

So, when you run the program and enter a temperature in Celsius (for example, 66), the program will convert it to Fahrenheit using the defined function and display the result, which, in this case, is 150.8.





