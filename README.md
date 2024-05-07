# Weather-Dashboard
A powerful responsive weather dashboard is being designed and developed using Angular JAVA(Version : 17.3.7), HTML, CSS , bootstrap and WeatherAPIs to call the weather calls in the UI

The dashboard enables the user to locate any location's weather in the search placeholder.
The dashboard shows the current weather for the searched location, including current temperature, hourly temperature for the current day and also weekly forecast for upcoming days' weather.
It gives a detailed information on UV index, Wind Status, Sunrise, Sunset, Humidity, Visibility and Air Quality.
The dashboard has a special functionality of seeing the weather temperature in both Celsius and Fahrenheit degree.
The dashboard has used WeatherAPIs (https://www.weatherapi.com/) to call the weather calls to the UI.
The dashboard is completely owned by me.
The APIs used in this project are:
1.http://api.weatherapi.com/v1/search.json
2.http://api.weatherapi.com/v1/forecast.json

Instructions :
The dashboard has the following components

1. The left-container component consists of all the HTML codes and the typescript logic for the left-side of the dashboard
2. The right-container component consists of all the HTML codes and the typescript logic for the right-hand side (background color light yellow) of the dashboard.
3. Models component consists of all the data models and their types to extract those data from the weather API JSON payload.
4. Services component consists of the weather.service.ts file which consists of all the business logics to transfer the data from Client API to Dashboard UI
5. Environment Variables consists of the API key name and the API key value which needs to be taken from the weatherAPI.com and pasted there.
The API Key value is present inside the EnvironmentVariables.ts file inside Environment folder where you need to use your API key value and run the project.

Use ng serve --open to execute the project.

**Note:
How to extract the file :
Download and move both weatherapp.7z.001 and weatherapp.7z.002 files in a same specific location and extract the folder of  weatherapp.7z.001 file only. Then, directly open  the weatherapp folder inside VS code application and add your API key in EnvironmentVariables.ts file. Execute and the dashboard would be running successfully.

