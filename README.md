# socialspeed

- [Project](#project)
- [Social speed?](#social-speed)
- [I need your help!](#i-need-your-help)

##Project

Get people together to create a calculator for the length of a trip using the concept of generalized speed from Ivan Illich.

##Social speed? 

###Short explanation

The generalized speed (also called social speed) is a speed that takes into account the time spent to 'afford' the trip. 

[Read more](http://ranprieur.com/readings/illichcars.html) or see some examples below.

###Examples:

If Sharon can use her car to ride 200kms from A to B in 4 hours, her speed is 50km/h.
But taking into account the price of gas, tolls, parking and other expenses from car ownership this trip costs 40usd.
If her hourly salary is 20usd/hour then it means Sharon has to spend 2 hours working to pay this trip. The generalized speed takes into account both the duration of the trip and the time spent to pay the trip.
The generalized speed of Sharon is thus: 200km / (4h trip duration + 2h time spent to pay for the trip)
= 33km/h

If Sharon prefers to use the train that takes 4 and a half hours for the same distance. Her speed is slower at 44km/h but the ticket only costs 10usd. She only has to work 30 minutes to afford the ticket.
Her generalized speed with the train is consequently: 200km / (4.5h trip duration + 30min time spent to pay for the trip)
= 40km/h

In this example one can see that although the trip itself is shorter with the car, taking the train is faster for Sharon if she thinks about the total amount of time she dedicates to transportation (which include earning money to finance the trip).

![Drive Work Drive](http://40.media.tumblr.com/1cf0128b7de533373caacf66d36f2fa0/tumblr_ndg1qorShX1qdw1kro1_540.jpg)

Another stunning example comes when applying this concept to a society as a whole. In the USA, the yearly budget of the auto industry is 1,653.7 billion, the cost of road accidents alone is around a trillion dollars and there is a labor force of 157 million. With an average salary of 25$ per hour, we can assume that the workforce is dedicating 
((1,653,700,000,000+1,000,000,000,000)/(157,000,000*25)) = 676 hours each to 'afford cars'.

On yearly average people spend 540 hours in their car and travel 21687km. Their social speed is
21687km / (540 trip duration + 676 time spent to pay for the trip) =
18km/h 

The generalized speed of American society with a car in this example is estimated here at 18km/h, which is the average speed of a bicycle. Including  other costs related to car such as pollution, climate change and oil conflicts would  decrease this generalized speed even lower to that of a pedestrian (6km/h).

##I need your help!

I'm new to github and don't know much about web programming. That's why any help is welcome for this project. Let's work together!

###Why you should  help?

This calculator aims to contribute to decrease the numbers of cars on this planet by helping people realize that the car is actually one of the slowest transportation when generalized time is considered.

Each car that disappears means less chances for kids to develop eczema or asthma, less chances of being killed on the public space, less public money spending, less impact on climate change,  less resources consumed and more social interactions.. Taking part in that will just make you a hero basically. :)

###Goals

- Have a trip calculator that gives the time and money it costs to afford the trip
- Make a version that's easy to translate in other languages and make it avalaible to any website that wants to use it


###Work done so far

It's javascript with google map api for the calculator here:
![http://codepen.io/hdkw/full/RRGLWR/](http://codepen.io/hdkw/full/RRGLWR/)
June 2016: the calculator is finally functionnal, now time for the design phase!

Input fields are:

  +Type of transportation  
  
      -Walking
      
      -Cycling
      
      -Train
      
      -Car
      
      -Rideshare
      
      -Hitchhiking
      
      -Plane
    
  +Hourly salary
  
  +Distance and time taken for the trip
  
  +Cost of the transportation per kilometer
  
The outputs are the generalized time and speed for the trip with the formula:

```
Generalized-time = trip-time + (trip-distance * cost-per-km) / hourly-salary

Generalized-speed = trip-distance / Generalized-time
```
  
###I need help for the following

Clean the code, improve the design of the calculator or provide feedback

http://codepen.io/hdkw/full/RRGLWR/

####Contact me!

Through github or by email : H   D    K   W    T   W   at google's mail provider..





