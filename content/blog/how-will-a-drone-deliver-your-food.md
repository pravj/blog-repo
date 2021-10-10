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
The title looks like a good interview question. So here is the right follow-up question, _Why?_

Let’s list down the contributing factors and follow up from there.

Have you ever been in a situation when you’re (hungry) about to place a food order and the application is showing you _40+ minutes to deliver_? It’s a complete turn-off.

* You start to think of some other food item that will be delivered early.
* You might even think of paying more if it can be delivered faster.

### Available options and their limitations

You can break down your order delivery timing in the following segments ([reference](https://bytes.swiggy.com/the-swiggy-delivery-challenge-part-one-6a2abb4f82f6)).

![](/images/how-will-drone-deliver-food-order-food-delivery-time.png)

Food delivery companies are already doing a lot to deliver it faster for you.

* They minimize the delay between _food getting prepared_ and _it getting picked up_ by ensuring the delivery partner/executive is already at the restaurant before it’s _prepared_.
* I’ve wondered if they (pseudo) accept the order even before the payment is complete.

There are a lot of optimizations at work, though not all of them are focused on _delivering food even faster for customers_ ([reference](https://bytes.swiggy.com/the-swiggy-delivery-challenge-part-two-f095930816e3)).

After all, there is Physics and ground reality at play, affecting how fast your food is delivered.

![](/images/how-will-drone-deliver-food-order-last-mile-time.png)

To tackle the first factor (_Distance_), you are only shown restaurants close enough to you.

Here is Swiggy celebrating their launch (circa, June 2021) that allows you to order from restaurants that are at a distance.

![](/images/how-will-drone-deliver-food-order-distance-limitation.png)

On a side note, _12 km away!_ isn't tempting enough, only if they showed me a famous restaurant I was missing out on.

Moving on, if we consider the second factor (_Last-mile speed_), it comes down to how fast is your food (_and the delivery partners/executives are_) moving around? Let's visit some of the available options.

![](/images/how-will-drone-deliver-food-order-option-comparison.png)

How fast the traffic moves depends not just on the vehicle, but where you live. In Bangalore, the Average Commute Speed ranges between 18-21 km/hr ([reference](https://timesofindia.indiatimes.com/city/bengaluru/at-21-2kmph-bluru-traffic-speed-up-20-in-2-years/articleshow/73000557.cms "Average Commute Speed")).

Ultimately, Swiggy/Zomato wants to expand the **Distance(restaurant, delivery-location)** so you’ve more options to choose from (eventually leading to more orders or higher average order size), but they also want to increase the Last-mile speed.

So that customers like you and me can have that \[_insert your favorite food item here_\] just as we think about it.

> _The Deliverator stands tall, your pie in thirty minutes or you can have it free, take the delivery car, file a class-action suit. --- Snow Crash_

And if they can find a solution that ensures the Last-mile time isn't increasing as they increase the distance, it's a win-win. Drones fit somewhere here.

Work is already happening in this domain. Swiggy/Zomato and a few other entities have received approval to start testing _the way their drone will deliver your food_. ([reference](https://www.livemint.com/companies/news/food-delivery-in-india-via-drones-zomato-swiggy-dunzo-can-start-testing-11591253543250.html))

### Execution risks/challenges

Now that we know it will bring a legit business advantage if we can get your food to travel at a higher speed, let's think how will this happen?

* You can’t continue to get Neeraj Chopra to throw your food because he will eventually have to prepare for the next Olympics.
* Neither we can teleport the parcel, as there is no _public_ AWS API for it yet.

There are many variables if we consider drone delivery as an option and the associated risks/challenges.

![](/images/how-will-drone-deliver-food-order-execution-risk.png)

**First-mile conditions**

* Restaurants wouldn’t want to see a lot of drones on their premises instead of visitors for dine-in. There is already discrimination against delivery partners/executives at restaurants, which shouldn’t be encouraged.
* Restaurants will not be able to maintain a dedicated space for drones.
* This might push Swiggy/Zomato to get cloud kitchens to adopt the new delivery method before it goes mainstream to all the other restaurants.

**Last-last mile conditions**

* Your Last-last mile conditions aren’t that good if you have to help navigate the delivery partner/executive every time you order.
  * _Yes! The same Himalayan shop building, near ICICI bank_
  * _No! The corner building, can you see Sri Lakshmi apartment?_
* And if you don’t have to guide them for every order, these conditions are all sorted for you (and I need your contact details).

**Vehicle safety**

* As a product person working on drone delivery, I do not want to lose more than 3 drones every 1000 orders, so that I can get my full monthly salary.
* You will have to prevent drones from getting stolen or getting damaged.

**Public safety**

* Similarly, you wouldn’t want to hit someone when the order is being delivered.
* You and your drone will have to spend the night in jail and the food will get cold.

**Government regulations**

There are many rules and regulations that you will have to adhere to as you start to utilize this new delivery method. ([reference](https://digitalsky.dgca.gov.in/assets/files/UasRules.pdf))

### Possible workflow

Overall, the drone-delivery operations will follow a phase-wise approach, moving from lesser execution risk to higher execution risk (_considering the regulations are manageable_).

![](/images/how-will-drone-deliver-food-order-last-mile-conditions-execution-risk.png)

As covered earlier, drone delivery is just an option, _you just want the food delivered faster._

Similar to the existing workflow, once the food is prepared, there will be two major lags to the journey.

![](/images/how-will-drone-deliver-food-order-delivery-lags.png)

**Restaurant to Last-mile (pre-flight)**

* Unless there is a dedicated space (at the restaurant) for setting up and launching the drones, your food might get shipped first to a place where it can be mounted on a drone.

**Restaurant to Last-mile (in-flight)**

* This might or might not have a human-in-the-loop (someone operating a drone from home), based on the flight route.

**Restaurant to Last-mile (post-flight)**

* If you live in a posh society, the Last-mile can be your own map address with a dedicated zone for Swiggy/Zomato drones to (locate and) land.
* Otherwise, it can be a special facility (closer to your location) operated by Swiggy/Zomato.

**Last-mile to Last-last mile**

* At least for a significant time (2-3 years), you shouldn’t assume a drone will ever come to your balcony. It will still be a delivery partner/executive, just that he/she will pick it from the nearest Last-mile facility.
* It will still be a delivery partner/executive, just that you will get your food faster.

But when this happens, you will get your food faster, _that’s for sure._ Don’t forget to empathize with the bunch of people that worked in the background to make that happen.