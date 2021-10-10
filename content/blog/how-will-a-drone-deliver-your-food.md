+++
aliases = []
date = 2021-10-10T06:30:00Z
description = "Visualising the experience that will set a new benchmark in how you will get your food delivered faster."
draft = true
pageimage = ""
tags = ["Product", "Design", "Experience", "Last-mile"]
title = "How will a drone deliver your food?"
url = "/blog/how-will-drone-deliver-food-order/"

+++
> How will a drone deliver your food?

This looks like a good interview question. So let’s ask the right follow-up question, _Why?_

Let’s list down the contributing factors and follow up from there.

Have you ever been in a situation when you’re (hungry) about to place a food order and the application is showing you _40+ minutes to deliver_?

It’s a complete turn-off.

* You start to think of some other food item that will be delivered early.
* You might even think of paying more if it can be delivered faster.

#### Available options and their limitations

You can break down your order delivery timing in the following segments ([reference](https://bytes.swiggy.com/the-swiggy-delivery-challenge-part-one-6a2abb4f82f6)).

* Food delivery Time = Max (first-mile time, food-preparation time) + Last-mile time

Food delivery companies are already doing a lot to deliver it faster for you.

* They minimize the delay between _food getting prepared_ and _it getting picked up_ by ensuring the delivery partner/executive is already at the restaurant before it’s _prepared_.
* I’ve wondered if they (pseudo) accept the order even before the payment is complete.

There are a lot of optimizations at work, though not all of them are focused on _delivering food even faster for customers_ ([reference](https://bytes.swiggy.com/the-swiggy-delivery-challenge-part-two-f095930816e3)).

After all, there is Physics and ground reality at play, affecting how fast your food is delivered.

* Last-mile time = Distance(resturant, delivery-location) / Last-mile speed

To tackle the first factor, you are only shown restaurants close enough to you.

![](/images/how-will-drone-deliver-food-order-distance-limitation.png)

And if we consider the second factor in Last-mile speed, it comes down to how fast are the delivery partners/executives moving around?

There are quite some options available that can help them move around. Let’s have a look.

* Speed: 5 km/hr (walking on foot like it’s 1968)
* Speed: 10-15 km/hr (using a bicycle or electric bike)
* Speed: 15-20 km/hr (using a bike or electric bike, speed capped based on the city)
* Speed: 50-90 km/hr (using a drone, speed capped as per regulations)
* Speed: 100-120 km/hr (getting Neeraj Chopra to throw the food)
* Speed: 1.079e+9 km/hr (teleporting or making it at home)

How fast the traffic moves depends not just on the vehicle, but where you live. In Bangalore, the Average Commute Speed ranges between 18-21 km/hr.

Ultimately, Swiggy/Zomato wants to expand the Distance(restaurant, delivery-location) so you’ve more options to choose from (eventually leading to more orders or higher average order size), but they also want to increase the Last-mile speed.

So that customers like you and me can have that \[placeholder\] just when we think about it.

_The Deliverator stands tall, your pie in thirty minutes or you can have it free, take the delivery car, file a class-action suit. ---- Snow Crash_

Work is already happening in this domain. Swiggy/Zomato and a few other entities have received approval to start testing _the way their drone will deliver your food_. ([reference](https://www.livemint.com/companies/news/food-delivery-in-india-via-drones-zomato-swiggy-dunzo-can-start-testing-11591253543250.html))