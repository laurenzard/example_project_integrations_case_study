Example Project: Integrations Case Study 

The VP of Customer Success and the Product Manager of the Integration Marketplace want your initial, brief perspective on: 

● What do we know about recent integration usage trends? 

● Do integrations matter for our customers? 

● What are your initial recommendations based on the data? 

● What’s your proposal for what to investigate next? 

**account_segments.csv**
contains information about each of HS’s customers.
CUSTOMER_ID 	The unique ID of the customer account.
EMPLOYEE_SIZE 	The approximate number of employees working at our customer’s business.
CUSTOMER_SEGMENT The name of the sales/support contact team for each customer. How we sell to and support our customers depends on their segment. 
● We run a partner program in which 3rd-party service agencies help 
our customers use and adopt HubSpot. The partner handles billing 
and the customer relationship, receiving a commission from us in 
return. 
● Our direct, “low-touch”, and “high-touch” teams are all internal 
sales/support teams. 
○ Our “low-touch” teams generally service lower-value or 
older customers who require less support. These segments 
have one HubSpotter supporting many customers. 
○ Our “high-touch” teams provide tailored support. These 
segments have one HubSpotter supporting only a handful 
of customers at a time. 
○ Our direct team manages customers who do not meet 
either definition for our low-touch or high-touch teams. 


**customer_metadata.csv **
contains snapshots of financial and product information about each of HubSpot’s customers.
CUSTOMER_ID The unique ID of the customer account.
SNAPSHOT_MONTH This is the ‘snapshot’ period. The customers’ featured information may change month-to-month.
PRODUCT_TIER This denotes which tier/edition our customer purchased of our Marketing Hub product at the beginning of the month. 
We sell our product in tiers/editions, from lowest to highest 
value: Free, Starter, Basic (a legacy product that we would like our 
customers to leave), Pro, Enterprise
NUM_OF_INTEGRATIONS The number of integrations a customer had at the beginning of the month.
CUSTOMER_VALUE_BEGINNING_OF_MONTH The monthly recurring revenue we expected from the customer as of the beginning of the month
CUSTOMER_VALUE_END_OF_MONTH The monthly recurring revenue we expected from the customer as of the end of the month
CUSTOMER_CANCELLATION_DOLLARS The monthly recurring revenue we lost due to a customer cancellation during the month 
Note: Cancellation Dollars is not always the difference 
between beginning and end of month value. This is due to 
how we define individual products. A customer may own 
both Sales and Marketing Products but only cancel one. 
You can use this column as a source of truth for 
cancellation dollars.


**integrations.csv** 
contains snapshots of information about each of HubSpot’s integrations.
INTEGRATION_ID 	The unique ID of an integration. 
Note: Integrations with “CUSTOM” in its name are integrations built outside of our Integration App Marketplace and instead make use of our API ecosystem.
CUSTOMER_ID 	The unique ID of the customer account.
SNAPSHOT_MONTH 	This is the date of the ‘snapshot’ month. The customers’ featured information may change month-to-month.

