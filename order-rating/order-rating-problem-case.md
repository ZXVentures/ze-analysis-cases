# Order Rating Problem Case

## The Introduction: what you need to know

Zé Delivery is a cold beer delivery service available in five capitals in Brazil: Extended São Paulo city. Rio de Janeiro, Belo Horizonte, Curitiba and Fortaleza. The value proposition of the service is to deliver cold beers to users in less than 1 hour wherever they are and charging a fair price. Users can order any type of beer they like, from mainstream to craft brands, RGB (Returnable Glass Bottle) or OW (One Way bottles). Extra products like snacks, ice and charcoal are also available at Zé Delivery.

Since its launch in January '16, the service has a rating system in which the user can rate every order he/she makes from 1 to 5 stars. Zé Delivery Operations Team is proud of the quality of the service, having achieved an average rating of 4,8 stars with around 60% of the orders being rated - last measured in June ’17. This rating request happens every time the user enters the homepage of the platform and has a last order that has not been rated. They have the option to skip the rating if they want to. The rating is also requested by a direct e-mail sent 1h30 after the order is made.

The operational side of Zé Delivery counts with many partners (POCs) spread through a city. They are totally responsible for handling the delivery. That means that Zé’s platform only take the order from a user and send it to a chosen POCs. They accept that order, delivers and charge the user.

## The Problem: what we are 

Recently the Growth Team started to invest a lot of money to exponentially increase the number of orders. However, during our meetings of results (SDG) we noticed that the average rating began to drop. Our team is now afraid that if they invest too much money on growth, the operations won’t be able to handle the demand and it will ruin what we created as a brand.

### Important to notice

* In July ’17 the platform in which Zé Delivery operated was changed to a new one we developed in-house. That coincide with the same period the order rating started to drop. 
*	The increase on marketing investment began in August ’17.
*	The rating can have 7 numbers in the data field: 1, 2, 3, 4 and 5 that represents the stars the user gave; we input the -1 tags on the data field if the user chooses to skip the rating, and blank or 0, if the user didn’t receive the rating request yet. Those last 3 are not considered in our average order rating.
*	The email for the rating request wasn’t implemented in this new platform, but we had it on the old platform
*	Angry users normally tend to rate the order before happy users do, because they normally come back to the platform trying to find a solution for the problem they might be having. 
*	The user can give the reasons for his bad rating: “More Than 1h”, “Warm Beer”, “Bad Service”, “Problem with Payment”, “Not Delivered” and “Missing Products”


## The Misson: What we expect

Identify what is the *root cause* to this operational problem and *advise the team* whether they should stop all investments or if there is a plan B they could follow to keep growing the orders.

## The Data: What you must analyze

You can find the data to analyze here: [Order Rating Problem Data](https://github.com/ZXVentures/ze-analysis-cases/blob/order-rating-challenge/order-rating/ze-delivery-order-rating-problem-data.xlsx?raw=true)

### Don't forget!

* Any extra info you may find necessary just ask and it will be provided if possible
* This case should be analyzed as an individual exam. So, please, DO NOT share any part of test with anyone.

Good luck!
