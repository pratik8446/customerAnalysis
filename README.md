# customerAnalysis

## Task

Our (hypothetical) marketing department needs some help in focussing on the most important market segment. Instead of marketing to everyone, they need our help in identifying who our most profitable customers are. Are they married or unmarried, working or retired, premium or budget buyers etc… This will help them position things better.

Also, they need help in identifying the bestselling products. 

So, given the transaction data, help us identify the top 3 most profitable products and characteristics of our most loyal customers.  Also include your hypothesis of why you think the loyal customers.

I'll analyze the provided transaction and purchase behavior data to identify:

The top 3 most profitable products.
Characteristics of the most loyal customers.
A hypothesis on why loyal customers prefer certain products.
Let me first inspect the contents of both files to understand their structure.

Data Overview
Transaction Data (transaction_data.csv)
Contains 264,836 rows with columns for date, store number, customer loyalty card number, transaction ID, product number, product name, quantity purchased, and total sales.
Purchase Behavior Data (purchase_behaviour.csv)
Contains 72,637 rows with columns for loyalty card number, customer lifestage, and premium customer status.
Now, I'll:

Identify the top 3 most profitable products based on total sales.
Merge both datasets to analyze customer characteristics for loyalty and profitability trends.

 ​​
Top 3 Most Profitable Products

Dorito Corn Chip Supreme 380g – $40,352
Smiths Crinkle Chip Original Big Bag 380g – $36,367.60
Smiths Crinkle Chips Salt & Vinegar 330g – $34,804.20
Now, I'll analyze customer loyalty by merging both datasets based on LYLTY_CARD_NBR and identifying the characteristics of the most loyal customers. ​​

Most Loyal Customer Segments

Older Families (Budget buyers) – $168,363.25
Young Singles/Couples (Mainstream buyers) – $157,621.60
Retirees (Mainstream buyers) – $155,677.05

Hypothesis on Loyalty Trends

Older Families (Budget Buyers) likely prefer affordability while making bulk purchases, explaining their high spending.
Young Singles/Couples (Mainstream Buyers) may be brand-conscious and willing to spend more for convenience and quality.
Retirees (Mainstream Buyers) may have stable consumption patterns and prefer familiar brands, leading to consistent purchases.
