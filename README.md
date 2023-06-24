
# App 6 Weather Api
This project is a Flask application that provides an API and web pages to access and display temperature data from weather stations. The application utilizes the Flask framework and pandas library to handle data processing and rendering.

## Prerequisites
Ensure that you have the following dependencies installed in your Python environment:

- Flask
- pandas
  
You can install these dependencies by running the following command:

```bash
pip install Flask pandas
```

## Usage
1. Run the Flask application by executing the following command in the project directory:
```bash
python app.py
```
2. Access the home page by navigating to http://localhost:5001/. This page will display the station data in an HTML table.
3. Access the API endpoints to retrieve temperature data:

- /api/v1/<station>/<date>: Retrieves the temperature for a specific station and date.
- /api/v1/<station>/: Retrieves all temperature data for a specific station.
- /api/v1/yearly/<station>/<year>: Retrieves temperature data for a specific station and year.
  
Replace <station> and <date> with the desired station ID and date in the format of YYYY-MM-DD, respectively.

## Contact
If you have any questions or suggestions regarding this project, please feel free to contact Barış Umut Baykal at barisumutbaykal@gmail.com.

Enjoy exploring the weather station temperature data!
