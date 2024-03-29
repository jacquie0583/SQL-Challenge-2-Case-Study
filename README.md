# SQL-Challenge-2-Case-Study
Data collection was critical for the business’ growth.  An entity relationship diagram of the database design was created.  Cleaning of the data and applying calculations proved necessary to better direct his runners and optimize Pizza Runner’s operations.  All datasets exist within the pizza_runner database schema - included in this reference within the SQL scripts.  Exploration of the data provided answers the case study.

<p align="center">
  <img width="500" height="300" src="https://github.com/jacquie0583/SQL-Challenge-2-Case-Study/blob/main/Picture1.png">
</p>

#  A. Pizza Metrics  Customer's Questions:
1.	How many pizzas were ordered?

<p align="center">
  <img width="500" height="300" src="https://github.com/jacquie0583/SQL-Challenge-2-Case-Study/blob/main/Picture2.png">
</p>

2.	How many unique customer orders were made?

<p align="center">
  <img width="500" height="300" src="https://github.com/jacquie0583/SQL-Challenge-2-Case-Study/blob/main/Picture3.png">
</p>

3.	How many successful orders were delivered by each runner?

<p align="center">
  <img width="300" height="200" src="https://github.com/jacquie0583/SQL-Challenge-2-Case-Study/blob/main/Picture4.png">
</p>


4.	How many of each type of pizza was delivered?

<p align="center">
  <img width="300" height="200" src="https://github.com/jacquie0583/SQL-Challenge-2-Case-Study/blob/main/Picture5.png">
</p>


5.	How many Vegetarian and Meatlovers were ordered by each customer?
6.	What was the maximum number of pizzas delivered in a single order?
7.	For each customer, how many delivered pizzas had at least 1 change and how many had no changes?
8.	How many pizzas were delivered that had both exclusions and extras?
9.	What was the total volume of pizzas ordered for each hour of the day?
10.	What was the volume of orders for each day of the week?
B. Runner and Customer Experience
1.	How many runners signed up for each 1 week period? (i.e. week starts 2021-01-01)
2.	What was the average time in minutes it took for each runner to arrive at the Pizza Runner HQ to pickup the order?
3.	Is there any relationship between the number of pizzas and how long the order takes to prepare?
4.	What was the average distance travelled for each customer?
5.	What was the difference between the longest and shortest delivery times for all orders?
6.	What was the average speed for each runner for each delivery and do you notice any trend for these values?
7.	What is the successful delivery percentage for each runner?
C. Ingredient Optimisation
1.	What are the standard ingredients for each pizza?
2.	What was the most commonly added extra?
3.	What was the most common exclusion?
4.	Generate an order item for each record in the customers_orders table in the format of one of the following:
o	Meat Lovers
o	Meat Lovers - Exclude Beef
o	Meat Lovers - Extra Bacon
o	Meat Lovers - Exclude Cheese, Bacon - Extra Mushroom, Peppers
5.	Generate an alphabetically ordered comma separated ingredient list for each pizza order from the customer_orders table and add a 2x in front of any relevant ingredients
o	For example: "Meat Lovers: 2xBacon, Beef, ... , Salami"
6.	What is the total quantity of each ingredient used in all delivered pizzas sorted by most frequent first?
D. Pricing and Ratings
1.	If a Meat Lovers pizza costs $12 and Vegetarian costs $10 and there were no charges for changes - how much money has Pizza Runner made so far if there are no delivery fees?
2.	What if there was an additional $1 charge for any pizza extras?
o	Add cheese is $1 extra
3.	The Pizza Runner team now wants to add an additional ratings system that allows customers to rate their runner, how would you design an additional table for this new dataset - generate a schema for this new table and insert your own data for ratings for each successful customer order between 1 to 5.
4.	Using your newly generated table - can you join all of the information together to form a table which has the following information for successful deliveries?
o	customer_id
o	order_id
o	runner_id
o	rating
o	order_time
o	pickup_time
o	Time between order and pickup
o	Delivery duration
o	Average speed
o	Total number of pizzas
5.	If a Meat Lovers pizza was $12 and Vegetarian $10 fixed prices with no cost for extras and each runner is paid $0.30 per kilometre traveled - how much money does Pizza Runner have left over after these deliveries?
E. Bonus Questions
If Danny wants to expand his range of pizzas - how would this impact the existing data design? Write an INSERT statement to demonstrate what would happen if a new Supreme pizza with all the toppings was added to the Pizza Runner menu?
