Price Optimization Project

This project aims to optimize pricing strategies for maximizing revenue and profitability. By leveraging data analytics techniques and machine learning algorithms, we seek to identify optimal pricing points that balance customer demand, market competition, and business objectives. 

Dataset used: https://www.kaggle.com/datasets/suddharshan/retail-price-optimization 

ِِA brief description of each column present in the Retail price optimization dataset:

➔ customers (integer): monthly demand for a given subcategory of goods

➔ freight_price (float): freight price of the company goods

➔ fp1, fp2, fp3 (float): freight price of competitors 1, 2, and 3 goods, respectively

➔ product_category_name (categorical) broad group category name

➔ product_id (categorical): detailed group subcategory name

➔ product_description_length (integer) number of words in the subcategory description

➔ product_score (float): user rating for subcategories of the goods

➔ ps1, ps2, ps3 (float): user rating for subcategories of competitors 1,2,3 respectively

➔ product_photos_qty (integer): number of photos for each subcategory (product_id)

➔ product_weight_g (integer): unit weight in grams

➔ total_price (float): monthly revenue, which can be calculated using formula: total_price = unit_price * qty

➔ month_year (string): data in the format (dd-mm-yyyy) within the range between 01-01-2017 and 01-08-2018. Only months and years are important here.

➔ year (integer): year which was taken from the 'month_year'

➔ month (integer): month which was taken from the 'month_year'

➔ qty (integer): monthly sales per subcategory

➔ unit_price (float): monthly unit price of subcategory goods of company goods

➔ comp_1, comp_2, comp_3 (float): unit price of within the subcategory of competitors 1,2,3 goods, respectively

➔ lag_price (float): unit price on the previous month

➔ weekend (integer): number of weekends per month

➔ weekday (integer): number of weekdays per month

➔ holiday (integer): number of holidays per month

➔ s (float): yet unknown parameter
