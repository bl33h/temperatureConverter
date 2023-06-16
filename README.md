# temperatureConverter
This project revolves around the conversion of temperature readings obtained from a temperature sensor. It involves the development and implementation of a temperature converter program in Python.

<p align="center">
  <br>
  <img src="https://media.tenor.com/_rabzV-JjTIAAAAM/very-hot-high-temperature.gif" alt="pic" width="400">
  <br>
</p>
<p align="center" >
  <a href="#Files">Files</a> •
  <a href="#functionality">Functionality</a> •
  <a href="#how-to-use">How To Use</a> 
</p>

## Files

- src: the file that implements de solution.

## Functionality
The code offers the following key functionalities:

- Acquires temperature data from a temperature sensor (Adafruit BMP280).
- Performs temperature conversion between different units (e.g., Celsius, Fahrenheit, Kelvin).
- Utilizes the Google Sheets API to store the converted temperature values in a Google Spreadsheet.
- Manages the position tracking within the spreadsheet to ensure organized storage of converted temperatures.
- Provides informative console output displaying the converted temperatures and relevant status messages.

## How To Use
To clone and run this application, you'll need [Git](https://git-scm.com) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/bl33h/temperatureConverter

# Run the app
$ python Proyecto03.py

# Install the libraries
$ pip install board # Change board for every library implemented in the code
```
To successfully use this code, it is crucial to have the required libraries and dependencies installed. Additionally, the temperature sensor should be properly connected to the designated pins. 
