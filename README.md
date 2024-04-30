Example Project: Integrations Case Study 

The VP of Customer Success and the Product Manager of the Integration Marketplace want your initial, brief perspective on: 

● What do we know about recent integration usage trends? 

● Do integrations matter for our customers? 

● What are your initial recommendations based on the data? 

● What’s your proposal for what to investigate next? 

Data Dictionary

**account_segments.csv**
contains information about each of HS’s customers.
CUSTOMER_ID 	The unique ID of the customer account.
EMPLOYEE_SIZE 	The approximate number of employees working at our customer’s business.
CUSTOMER_SEGMENT The name of the sales/support contact team for each customer. How we sell to and support our customers depends on their segment. 


**customer_metadata.csv **
contains snapshots of financial and product information about each customer
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


**integrations.csv** 
contains snapshots of information about each integrations.
INTEGRATION_ID 	The unique ID of an integration. 
Note: Integrations with “CUSTOM” in its name are integrations built outside of our Integration App Marketplace and instead make use of our API ecosystem.
CUSTOMER_ID 	The unique ID of the customer account.
SNAPSHOT_MONTH 	This is the date of the ‘snapshot’ month. The customers’ featured information may change month-to-month.

