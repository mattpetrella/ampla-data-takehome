# ampla-data-takehome
Data Analyst Take Home Exercise (December 2021)

You have been provided with the e-commerce order history for 3 different companies. Each row provides information on: 
- `order_id`: a unique identifier for the order 
- `company_id`: the Company name 
- `created_at`: the date on which the order was created
- `status`: the status of the order 
- `total_price`: the total order value 	
- `order_refunds`: the total that got refunded if at all 	
- `customer_id`: a unique identifier of the customer who make the purchase	
- `customer_order_count`: the total number of orders placed by the customer by the time the order was created, including the current one 
- `customer_total_spent`: the total amount spent by the customer by the time the order was created, including the current one 	
- `customer_created_at`: and the date on which the customer was created / registered


Your Chief Risk Officer, Jimbo is interested in projecting each company's total ecommerce revenue in the next 180 days. However, Jimbo doesn't just want to have a single estimated revenue but would like to understand the likelihood that a company will reach each marginal dollar of revenue. 

Construct a model that you believe best assists in answering this question. For example, you might ask yourself what is the likelihood that a company will receive at least $1 in revenue in the next 60 days (this would probably be very high) and likewise the likelihood that the company might receive $10M (this might be very low).
Based on the results of your analysis, Jimbo will decide the amount of risk Gourmet Growth is willing to take for this company and thus how much credit to extend. 


Requirements and Hints: 
- For purposes of this exercise you can assume revenue to be `total_price` net of `order_refunds` for all `paid` orders.
- Please commit your solution in a separate branch and create an Merge Request with your changes. 
- Please write your answer in python. You are welcome to use any open source packages / libraries in the python ecocosystem. 
- Please provide some minimal documentation on how to run your model. 
- Please provide a brief (1-2 page max) write-up explaining your approach to the model and defending its usefulness (including, for instance, how you may have tested it).
- Bonus: Explore whether customer repeat purchasing habits might impact the outcome of the model. 

Do not hesitate to reach out if you have any questions as you're working through the exercise!
