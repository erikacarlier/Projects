Project description

I worked as an analyst for Zuber, a new ride-sharing company that's launching in Chicago. My task was to find patterns in the available information. My objective was to understand passenger preferences and the impact of external factors on rides.

I worked with the following database, I analyzed data from competitors and tested a hypothesis about the impact of weather on ride frequency. 

Description of the data

A database with info on taxi rides in Chicago:
    
    neighborhoods table: data on city neighborhoods
        name: name of the neighborhood
        neighborhood_id: neighborhood code
    cabs table: data on taxis
        cab_id: vehicle code
        vehicle_id: the vehicle's technical ID
        company_name: the company that owns the vehicle
    trips table: data on rides
        trip_id: ride code
        cab_id: code of the vehicle operating the ride
        start_ts: date and time of the beginning of the ride (time rounded to the hour)
        end_ts: date and time of the end of the ride (time rounded to the hour)
        duration_seconds: ride duration in seconds
        distance_miles: ride distance in miles
        pickup_location_id: pickup neighborhood code
        dropoff_location_id: dropoff neighborhood code
    weather_records table: data on weather
        record_id: weather record code
        ts: record date and time (time rounded to the hour)
        temperature: temperature when the record was taken
        description: brief description of weather conditions, e.g. "light rain" or "scattered clouds"


The process

I completed expoloratory data analysis in order to determine which were the two most popular taxi companies in Chicago in November of 2017. After further analysis I was able to determine the weather conditions of each ride that started at the Loop and ended at O'Hare.

<img width="1369" alt="Task 1" src="https://github.com/erikacarlier/TripleTen-Projects/assets/155183853/b6e355e5-84b8-433a-946f-342074593bfe">

<img width="1361" alt="Screenshot 2024-01-11 at 9 44 13 AM" src="https://github.com/erikacarlier/TripleTen-Projects/assets/155183853/8e6989b5-abb1-4d7c-8a67-f79d880ff5dd">
<img width="673" alt="Screenshot 2024-01-11 at 9 44 25 AM" src="https://github.com/erikacarlier/TripleTen-Projects/assets/155183853/53ca3122-7ae8-4859-b6d7-2f7f847cb123">

<img width="1363" alt="Task 3" src="https://github.com/erikacarlier/TripleTen-Projects/assets/155183853/e37d9acd-6810-4bd1-830c-ac5ffee3d42e">

<img width="1366" alt="Task 4" src="https://github.com/erikacarlier/TripleTen-Projects/assets/155183853/fe6fea5a-5d00-42ec-bb75-0f51d79f1aa4">

<img width="1361" alt="Task 5" src="https://github.com/erikacarlier/TripleTen-Projects/assets/155183853/59da13da-8551-41ed-8d43-3ec6b9f7c998">

<img width="1365" alt="Task 6" src="https://github.com/erikacarlier/TripleTen-Projects/assets/155183853/72b2861f-2eff-419d-b0c2-b86ef457e6f9">
