# socialspeed

- [Project](#project)
- [Social speed?](#social-speed)
- [I need your help!](#i-need-your-help)

##Project

Get people together to create an open source calculator for the lenght of a trip using the concept of generalized speed from Ivan Illich.

##Social speed? 

###Short explanation

The generalized speed (also called social speed) is a speed that takes into account the time spent to 'afford' the trip. 

[Read more](http://ranprieur.com/readings/illichcars.html) or see some examples below.

###Examples:

If Sharon can use her car to ride 200kms from A to B in 4 hours, her speed is 50km/h.
But taking into account the price of gaz, tolls, parking and other expenses from car ownership this trip costs 40usd.
If her hourly salary is 20usd/hour then it means Sharon has to spend 2 hours working to pay this trip. The generalized speed takes into account both the duration of the trip and the time spent to pay the trip.
The generalized speed of Sharon is thus: 200km / (4h trip duration + 2h time spent to pay for the trip)
= 33km/h

If Sharon prefers to use the train that takes 4 and a half hours for the same distance. Her speed is slower at 44km/h but the ticket only costs 10usd. She only has to work 30 minutes to afford the ticket.
Her generalized speed with the train is consequently: 200km / (4.5h trip duration + 30min time spent to pay for the trip)
= 40km/h

In this example one can see that although the trip itself is shorter with the car, taking the train is faster for Sharon if she thinks about the total amount of time she dedicates to transportation (which include earning money to finance the trip).

![Drive Work Drive](http://40.media.tumblr.com/1cf0128b7de533373caacf66d36f2fa0/tumblr_ndg1qorShX1qdw1kro1_540.jpg)

Another stunning example comes when aplying this concept to a society as a whole. In the USA, the yearly budget of the auto industry is 1,653.7 billion, the cost of road accidents alone is around a trillion dollars and there is a labor force of 157 million. With an average salary of 25$ per hour, we can assume that the workforce is dedicating 
((1,653,700,000,000+1,000,000,000,000)/(157,000,000*25)) = 676 hours each to 'afford cars'.

On yearly average people spend 540 hours in their car and travel 21687km. Their social speed is
21687km / (540 trip duration + 676 time spent to pay for the trip) =
18km/h 

The generalized speed of American society with a car in this example is estimated here at 18km/h, which is the average speed of a bicycle. Including  other costs related to car such as pollution, climate change and oil conflicts would  decrease this generalized speed even closer to that of a pedestrian (6km/h).

##I need your help!

The first aim for the calculator is to place it on the French carfree website (carfree.fr). 
I'm new to github and don't know much about web programming. That's why any help is welcome for this project.
The site carfree.fr uses wordpress. 

###Work done so far

I've found [caldera forms](https://github.com/Desertsnowman/Caldera-Forms) which is a free plugin for wordpress. I could make a nice first calculator draft (sorry it's in French):
![piccalculator](https://lh3.googleusercontent.com/QSXYiTiPT61n6FA43XNTQDWSmyZ6UhlWmx9NY5OMOg=w386-h400-no)

This basic picture  shows that input fields are:

  +Type of transportation  
      Walking
      Cycling
      Train
      Car
      Rideshare
      Hitchhiking
      ..
    
  +Hourly salary
  
  +Distance and time taken for the trip
  
  +Cost of the transportation per kilometer
  
The outputs are the generalized time and speed for the trip.
  
###I need help for the following

####Map integration

I would like the user to be able to input a place of departure and destination from google maps or something equivalent. Then the time and distance for the trip are automaticaly calculated and fed as input for the form.
Of course the trip distance and time need to depend on the transportation choosen.  

I saw that in this [project](https://github.com/hitautodestruct/trip-price-calculator) you can [enter a start and end point with autocompletion](http://hitautodestruct.github.io/trip-price-calculator/) from google map. 
In this [other project](https://github.com/wildlyinaccurate/trip-planner), [the trip distance and time](https://wildlyinaccurate.com/trip-planner/) is calculated.






FRENCH
http://carfree.fr/index.php/2005/07/16/vers-lautomobile-immobile/
http://noodlejs.com/ (can scrap data from websites)
https://github.com/hpneo/gmaps (calculte itinerary from google map to give trip duration and distance)



