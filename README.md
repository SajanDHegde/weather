### Weather_API with flask
This projects allows the users to retrieve the information which contains the current weather information for multiple locations, this data is taken with the help of generated API key which was generated using OpenWeatherMap API.

## Brief Procedure
Install the required libraries.
To run the program we need to generate the API key using the OpenWeatherMap API key.
Run the application , once the code is compiled , open the Postman and create a new request to http://127.0.0.1:5000/weather with the GET method.
Add a query parameter 'city' with the value being the city.
For example (city=Mysore).
Once its done , send the request and get the output.To check the accuracy of the Output which contains the weather data by OpenWeatherMap.

## Screenshots
<img width="960" alt="Screenshot 2023-11-28 221143" src="https://github.com/SajanDHegde/weather/assets/150254430/e86873c0-23ea-4bba-8a7e-55fd44dbfc87">

<img width="960" alt="Screenshot 2023-11-28 221047" src="https://github.com/SajanDHegde/weather/assets/150254430/0be8f006-dead-4408-8f74-b15ad4579258">

<img width="960" alt="Screenshot 2023-11-28 221126" src="https://github.com/SajanDHegde/weather/assets/150254430/a4d1c774-94d6-42fc-8e7a-a21663c99650">


## Additionals
The code includes the ability to retrieve weather information for multiple locations through the /weather endpoint , and even the code has try-except blocks to catch and handle exceptions which may occur during the API requests.
