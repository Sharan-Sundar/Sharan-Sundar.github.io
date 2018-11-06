---
layout: post
title:  "Speed Control of DC Motor using Arduino"
date:   2018-09-13
excerpt: "A polynomial regression algorithm to stabilize the error between the user and sense speed under no load and loaded conditions for a 12 V DC motor."
project: true
publication: false
tag:
- Arduino 
- Occupancy
- Features
- Forecasting
comments: true
---
# ML for DC_Motor_Control

A polynomial regression algorithm to stabilize the error between the User-given and Sensed-speed under no load and loaded conditions for a 12 V DC motor.


### Conventional method

I guess some Electronics stuff.

### Deploying Machine Learning 
 The behaviour of the DC motor is polymial as observed from the graph below.

<figure>
	<a href="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_b.jpg"><img src="Graph.png"></a>
	<figcaption><center>RPM vs PWM of 2 different 12V DC motors</a>.</center></figcaption>
</figure>

The similar behaviour of the graphs of motors of different specifications leads to the assumption that different motors behave almost similarly and that the graph of any other DC motor can be mapped on to the base polynomial function found.
* Obtain the coefficients of the polynomial function using polynomial regression.
* Recreate the function in arudino.
