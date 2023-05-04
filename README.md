Simple Weather App

This is a simple weather app that displays the current weather conditions for a specified location.
Django framework(python) was used for backend and javascript for frontend.

Features

Get the current weather conditions for a specified location.
Display the temperature, humidity, wind speed, and weather condition icon.
Option to switch between Celsius and Fahrenheit temperature units.

API used

This app uses the OpenWeatherMap API to fetch the weather conditions for a specified location. 
You will need to obtain an API key from OpenWeatherMap to use this app.

Instructions to run the code

Install the following packages in the CMD

pip install Django

pip freeze>requirements.txt (which will create a list of tools required for the project)

pip install -r requirements.txt (which will install all the necessary tools)

python manage.py mitigate

If no errors appeared then the installation is done correctly.Then,run 
python manage.py runserver (which will start the server and allow you to test the application)

Usage

Enter the location for which you want to get the weather conditions in the "Location" field.
Click on the "Get Weather" button to fetch the weather conditions for the specified location.
The temperature, humidity, wind speed, and weather condition icon will be displayed on the page.
You can switch between Celsius and Fahrenheit temperature units by clicking on the corresponding button.

Credits

This app was created by Aishwarya MS.
