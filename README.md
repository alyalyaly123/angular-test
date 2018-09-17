# Full stack developer - angular weather app
This project will likely take up to two hours. You are not timed and can take as long as you wish to complete this project. You'll be creating a new angular project, interacting with a third party API and displaying the data. Finally you'll introduce some user friendly elements to the app.
1. Create a new branch (name it after you). 
2. Create a new angular project with the features specified in this document
3. Commit the weather app to your branch.

# Instructions
1. Read through this document
2. Create a new angular project
3. Use the open weather API to retrieve weather information on at least 10 cities
4. Populate a table within the app with this data
5. Introduce pagination, sortable columns and a filter for searching by city name

# Open weather API

This project makes use of the open weather API for current weather conditions.

> The API key to use for this project is: **194333f5b09188fbda8c4a3bbfea30b2**
> See https://openweathermap.org/current for documentation on the API

If you return weather data on multiple cities, each city should contain the following data: 

```
[  
	{  
		"id":2210221,  
		"name":"Tarhuna",  
		"coord":{  
			"lon":13.6332,  
			"lat":32.43502  
		},  
		"main":{  
		"temp":17,  
		"pressure":1024,  
		"humidity":55,  
		"temp_min":17,  
		"temp_max":17  
	},  
		"dt":1485784982,  
		"wind":{  
		"speed":3.6,  
		"deg":10  
	},  
		"clouds":{  
			"all":40  
		},  
		"weather":[  
			{  
				"id":802,  
				"main":"Clouds",  
				"description":"scattered clouds",  
				"icon":"03d"  
			}  
		]  
	},  
] 
```
# Displaying the data in the app

You are free to display the data as you wish, however try to include at least the following information: 

|   City             |Weather|Description| Temperature
|----------------|-------------------------------|-----------------|------|
|London |Clouds            |mostly clear | 25|
|Paris |Rain            |light rain            |23|
|New York |Clouds|scattered clouds| 20|

