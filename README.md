# mall-sales-analysis-python

Importing Different Liabraries

     import pandas as pd
     import numpy as np
     import matplotlib.pyplot as plt
     import seaborn as sns
     import plotly.graph_objects as go

     print(list(customer.columns))
     print(list(sales.columns))
     print(list(mall.columns))

output :
 ['customer_id', 'gender', 'age', 'payment_method']
 ['invoice_no', 'customer_id', 'category', 'quantity', 'invoice date', 'price', 'shopping_mall']
 ['shopping_mall', 'construction_year', 'area (sqm)', 'location', 'store_count']

 # Customer
 
    customer.head()

    customer_id	gender	age	payment_method
0	C241288	Female	    28.0	Credit Card
1	C111565	Male	         21.0	Debit Card
2	C266599	Male          20.0	Cash
3	C988172	Female	    66.0	Credit Card
4	C189076	Female	    53.0	Cash



  

