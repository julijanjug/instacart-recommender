# instacart-recommender
Predicting users reorders.
<a href="https://www.kaggle.com/c/instacart-market-basket-analysis">Kaggle</a>

Data can be found <a href="https://www.kaggle.com/c/instacart-market-basket-analysis/data">here</a>.


<h1>LightGBM recommender</h1>
<ul>
    <li> Public score: 0.37977</li>
    <li> Private score: 0.37967</li>
</ul>
<h2>Features</h2>
<h3>User features</h3>
<ul>
    <li>user_total_orders</li>
    <li>user_total_items</li>
    <li>total_distinct_items</li>
    <li>user_average_days_between_orders</li>
    <li>user_average_basket</li>
</ul>

<h3>Product features</h3>
<ul>
    <li>product_orders</li>
    <li>product_reorders</li>
    <li>product_reorder_rate</li>
</ul>

<h3>Order features</h3>
<ul>
    <li>aisle_id</li>
    <li>department_id</li>
    <li>order_hour_of_day</li>
    <li>days_since_prior_order</li>
    <li>days_since_ratio</li>
</ul>

<h3>User-product features</h3>
<ul>
    <li>UP_orders</li>
    <li>UP_orders_ratio</li>
    <li>UP_average_pos_in_cart</li>
    <li>UP_reorder_rate</li>
    <li>UP_orders_since_last</li>
    <li>UP_delta_hour_vs_last</li>
    <li>UP_total_buys_n5</li>
</ul>

<h1>Association rules recommender</h1>


