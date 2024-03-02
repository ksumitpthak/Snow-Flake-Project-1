# Snow-Flake-Project-1

**Dataset** - https://www.kaggle.com/competitions/instacart-market-basket-analysis/data

**Orders Table:**
| Column Name | Data Type | Description |
| --- | --- | --- |
| order_id | integer | Unique identifier for an order |
| user_id | integer | Unique identifier for a user |
| order_number | integer | A counter for the orders of a user |
| order_dow | integer | The day of the week the order was placed |
| order_hour_of_day | integer | The hour of the day the order was placed |
| days_since_prior_order | integer | Number of days since the previous order |

**Products Table:**
| Column Name | Data Type | Description |
| --- | --- | --- |
| product_id | integer | Unique identifier for a product |
| product_name | varchar | Name of the product |
| aisle_id | integer | Unique identifier for an aisle |
| department_id | integer | Unique identifier for a department |

**Order Products Table:**
| Column Name | Data Type | Description |
| --- | --- | --- |
| order_id | integer | Unique identifier for an order |
| product_id | integer | Unique identifier for a product |
| add_to_cart_order | integer | The order in which the product was added to the cart |
| reordered | boolean | Has the product been ordered by this user in the past? |

**Aisles Table:**
| Column Name | Data Type | Description |
| --- | --- | --- |
| aisle_id | integer | Unique identifier for an aisle |
| aisle | varchar | Name of the aisle |

**Departments Table:**
| Column Name | Data Type | Description |
| --- | --- | --- |
| department_id | integer | Unique identifier for a department |
| department | varchar | Name of the department |
