PIZZA SALES DATA ANALYSIS PROJECT WITH MS EXCEL.

NOTE: THE IMAGES OBTAINED FROM THIS ANALYSIS ARE CONTAINED IN THE PIZZA SALES ANALYSIS-IMAGES PDF https://github.com/PraiseTheDataGuy/Excel-Projects/blob/main/Pizza%20Sales%20Analysis-%20images..pdf. THE IMAGES COULD NOT BE UPLOADED DIRECTLY DUE TO THE NATURE OF GITHUB.

Pizza, Italy’s famous tasty and affordable meal, has a way of drawing me to itself. It is no surprise I decided to go for Pizza when looking for a dataset to analyze on Kaggle.

Data analysis can be basically summarized as analyzing data to obtain insights, notice trends, give recommendations and actions. The common idea of someone new into the data analysis field is that it is all about beautiful dashboards but there is much more to analyzing data than dashboards.


I will quickly give a brief explanation of each columns to give my esteemed reader, more understanding of what the dataset contains.

pizza_id: This column contains the total number of pizzas that were sold within the order dates contained in the dataset.

order_id: This contains the number of orders contained in the dataset. For example, an individual can order three(3) packs of pizzas, this means the pizza_id of the purchase is different but the order_id would be the same since it is coming through a single order.

pizza_name_id: This column contains the id of the pizza, more like a short form of the pizza name.

quantity: This contains the total number of orders purchased with respect to the order_id.

order_date: This contains the date at which the pizzas were ordered starting from January 1, 2015 through to December 31, 2015.

order_time: This column contains the time of the day at which the orders for pizzas were placed.

unit_price: This contains the price for a single unit of a particular pizza brand.

total_price: This column contains the total price of the pizzas bought in a single order from the same brand. For example, an order was placed for 2 units of Pizza A, the total price is the unit price of A multiplied by 2.

pizza_size: This contains details of the size of the pizza, the alphabet S, M, L, XL and XXL representing small, medium, large, extra large and extra extra large respectively.

pizza_category: This column contains the different categories of pizza that were sold. Examples of categories on sale are Classic, Veggie, Supreme and Chicken. Great options to pick from, eh?

pizza_name: This column contains the full name of each pizzas. The brand of the pizza with the highest count would obviously be the category with most orders.

The next step I took after skimming through the dataset was:

DATA CLEANING

Data cleaning is a very important step towards proper analysis of your data. Analyzing an unclean data is as good as doing nothing because your analysis would be incorrect and flawed, also you would not derive proper insights from the dataset. Hence, it is important to clean your data. I will outline the steps I took towards cleaning my data:

First thing I checked was for removal of duplicates. Always ensure you remove all duplicates before proceeding with your analysis. This dataset contained NO duplicates.
Next thing was converting the date to text. This would enable the data to be properly accessed as texts, you can use the “TEXT” function on Excel to carr this out.
I also changed the unit_price and total_price from general to number, so as to make the decimal places of each values to be uniform at 2 d.p., to obtain clarity and prevent the dataset from looking messy.
I added filters and checked through for blanks and outliers or weird values.
I was probably lucky enough to have a dataset that does not require too many actions to be carried out to make it clean. Lucky me.

After carrying out the data cleaning, what I consider as an exercise, yes it is, right? I proceeded to preparing:

PIVOT TABLE.

This aspect is just as important as anything else in analyzing data.

After creating pivot table, I used the table to create appropriate pivot charts and visuals.

I would describe each pivot section in form of a question and answer. Okay? Let’s go.

What category of the pizza was demanded the most?

I was curious to know which category was demanded the most. Which one do people prefer and why? Turned out the classic category was the most demanded. Followed by Supreme, Chicken and lastly Veggie. I have to admit my shock at Chicken being the third, it’s my favourite, so you would forgive me for expecting everyone to be like me. I wondered if the prices had to do with their choices. I discovered it was fair to say so, because the classic category was relatively cheaper compared to the rest but not by much though.


Treemap chart representing the category by %
I had earlier represented this in a pie chart but I felt the tree map would be look better, reducing the size of the chart, alters the position of each section, I tingled with it more than a couple of times before I settled for the one above.


Pizza category by demand
This is similar to the first image, but I wanted to see it in real values and not in the percentage format, that is the sole reason why I created the second pivot chart. They essentially depict the same information but in different formats.

Which Pizza brand brought in more sales in total price?

Different pizzas were sold with varying prices and different quantities, so which of the pizza brand brought in more sales. We have our answer below.


Pizza by Total Price
There are 30 brands in the dataset, I cannot include them all to avoid a messy chart, so I went with the top 10. Not to my surprise, chicken pizzas had the top 3 spots. Despite the fact that it is the second least demanded, still it brought it more profit. It only means one thing and what is it? They are more expensive than the remaining pizza categories.

What pizza size was ordered the most?

There are different sizes of pizza to order, so which of the sizes has the largest market. The large(L) size has the most market. I just assumed Pizzas were ordered by groups of people to share together or I probably have no idea how much pizza people consume, the latter might be the answer.


Pizza size by quantity
The medium size is closely followed by the small size. It was not surprising seeing what the bottom two were very small compared to the first three.

At what time of the day do pizza sales peak?

Most services rendering consumables have to stay for long hours of the day because people would like to get what to eat at different times. Services cannot afford to disappoint their customers. So when do sales peak?

Here is my finding:


Pizza demand with time
From the chart above, using the bold line in the chart, sales peak exactly at midday. It is also worthy to note that sales pick up around the hours of 5 and 6 in the evening. My deduction is that people order pizzas during the closing hours of their work.

The dotted lines represent the trendline as it can be used to observe trends over time and make predictions as to what should be done at peak sales period to maximize profits.

DASHBOARD

The dashboard represents a visual format of all the insights and answers obtained from the pivot section.



RECOMMENDATIONS.

From the insights obtained from the pivot section above, to maximize profits, here are some of my recommendations:

It was observed that chicken category brings the most sales despite the fact that it is the second least demanded and it was the most expensive. It means consumers might prefer chicken pizzas but might look to elsewhere due to cost. To achieve more profits, more pizza types from the chicken category should be produced at budget-friendly prices.
The production of more pizzas of the large, medium and small sizes should be continued as they are the take the major share of the market.
It was observed that sales peak at midday and at they rise as the work of the day comes to a close around the hours of 5pm amd 6pm. It must be ensured that more than enough pizzas are available around that time so as not to run out of stock leading to the disappointment of customers in what could have been totally prevented.

CONCLUSION.

In conclusion, analyzing the data is not the end of it all, putting the insights gained, trends observed and recommendations into action to satisfy customers and maximize profits is the ultimate goal.
