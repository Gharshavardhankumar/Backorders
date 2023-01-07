# Problem Statement:
Is to identify products at risk of backorder before the event occurs so that business has time to react.
# what is a Backorder?
* Backorders are products that are temporarily out of stock, but a customer is permitted to place an order against future inventory.
* A backorder generally indicates that customer demand for a product or service exceeds a company’s capacity to supply it.
* Back orders are both good and bad. Strong demand can drive back orders, but so can suboptimal planning.
# Dowload dataset: 
Backorders.csv
 # Data description
* Data file contains the historical data for the 8 weeks prior to the week we are trying to predict. The data was taken as weekly snapshots at the start of each week. Columns are defined as follows:
* sku - Random ID for the product

* national_inv - Current inventory level for the part

 * lead_time - Transit time for product (if available)

* in_transit_qty - Amount of product in transit from source

* forecast_3_month - Forecast sales for the next 3 months

* forecast_6_month - Forecast sales for the next 6 months

* forecast_9_month - Forecast sales for the next 9 months

* sales_1_month - Sales quantity for the prior 1 month time period

* sales_3_month - Sales quantity for the prior 3 month time period

* sales_6_month - Sales quantity for the prior 6 month time period

* sales_9_month - Sales quantity for the prior 9 month time period

* min_bank - Minimum recommend amount to stock

* potential_issue - Source issue for part identified

* pieces_past_due - Parts overdue from source

* perf_6_month_avg - Source performance for prior 6 month period

* perf_12_month_avg - Source performance for prior 12 month period

* local_bo_qty - Amount of stock orders overdue

* deck_risk - Part risk flag

* oe_constraint - Part risk flag

* ppap_risk - Part risk flag

* stop_auto_buy - Part risk flag

* rev_stop - Part risk flag

* went_on_backorder - Product actually went on backorder. This is the target value.

     Yes or 1 : Product backordered

     No or 0  : Product not backordered
# Broad Classification of attributes
SKU: Unique material identifier;

INV: Current inventory level of material;

TIM: Registered transit time;

FOR-: Forecast sales for the next 3, 6, and 9 months;

SAL-: Sales quantity for the prior 1, 3, 5, and 9 months;

MIN: Minimum recommended amount in stock (MIN);

OVRP: Parts overdue from source;

SUP-: Supplier performance in last 1 and 2 semesters;

OVRA: Amount of stock orders overdue (OVRA);

RSK-: General risk flags associated to the material;

BO: Product went on backorder   


