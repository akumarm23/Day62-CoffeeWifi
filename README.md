# Coffee & Wifi Python App

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/Python-3.8-pink.svg)](https://www.python.org/downloads/release/python-380/)
[![Version](https://img.shields.io/badge/Version-1.0-brightgreen.svg)](https://github.com/akumarm23/Day62-CoffeeWifi/releases/tag/v1.0)
[![Coffee](https://img.shields.io/badge/Coffee-%E2%98%95%EF%B8%8F-brown.svg)](https://github.com/akumarm23/Day62-CoffeeWifi)
[![Wifi](https://img.shields.io/badge/Wifi-%F0%9F%92%AA-blue.svg)](https://github.com/akumarm23/Day62-CoffeeWifi)

## Overview

Day62-CoffeeWifi is a Flask web application that allows users to submit and view information about cafes, including their names, locations, opening and closing times, coffee ratings, wifi strength ratings, and power socket availability. The application uses Flask for the web framework, Bootstrap5 for styling, and WTForms for form handling. The cafe data is stored in a CSV file named `cafe-data.csv`.

## Prerequisites

Before running the application, make sure to install the required packages. Open the terminal in your PyCharm IDE and run the following command:

### For Windows:

```bash
python -m pip install -r requirements.txt
```

### For MacOS:

```bash
pip3 install -r requirements.txt
```

This will install the necessary packages specified in the `requirements.txt` file.

## Usage

1. Run the Flask application by executing the `main.py` file.
2. Access the application in your web browser at [http://127.0.0.1:5002/](http://127.0.0.1:5002/).
3. Navigate to the homepage to view existing cafes.
4. Click on the "Add a Cafe" link to submit information about a new cafe.

## Cafe Submission Form

- **Cafe Name**: Enter the name of the cafe.
- **Cafe Location (Google Maps URL)**: Provide the Google Maps URL of the cafe's location.
- **Opening Time**: Specify the opening time of the cafe (e.g., 8AM).
- **Closing Time**: Specify the closing time of the cafe (e.g., 5:30PM).
- **Coffee Rating**: Select the coffee rating using emojis.
- **Wifi Strength Rating**: Select the wifi strength rating using emojis.
- **Power Socket Availability**: Select the power socket availability using emojis.
- Click the "Submit" button to add the cafe to the database.

## Viewing Cafes

- Access the "Cafes" page to see a list of all cafes along with their information.
- The data is read from the `cafe-data.csv` file.

## Important Note

- The application uses a CSV file (`cafe-data.csv`) to store cafe information. Make sure the file is accessible and writable by the application.

## Author

- [akumarm23](https://github.com/akumarm23)

Feel free to explore, contribute, and enhance the application!