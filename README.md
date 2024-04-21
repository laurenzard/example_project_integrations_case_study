# integrations_case_study
Case Study

We are a data-driven company. Teams across the organization use data to make the best decisions possible - providing these data-backed recommendations is a key responsibility of Ops & Strategy roles. This exercise is a great opportunity for you as a candidate to see a real-life example of the types of problems we tackle. 
Over the past few years, we’ve launched a number of products designed to help scaling companies grow better. In addition to releasing new products, another way HubSpot can grow is through integrations. Integrations allow customers to connect different, often disparate, systems with HubSpot so that the data contained in each system becomes part of a larger, more comprehensive ecosystem. 
HubSpot aims to become the #1 CRM platform for companies to effectively run and grow their businesses. Integrations are a core component to help HubSpot become a remarkable platform that customers love. 
Objective 
The VP of Customer Success and the Product Manager of the Integration Marketplace want your initial, brief perspective on: 
● What do we know about recent integration usage trends? 
● Do integrations matter for our customers? 
● What are your initial recommendations based on the data? 
● What’s your proposal for what to investigate next? 
They expect a presentation roughly ~15 minutes in duration (~25-30 minutes with discussion). For this analysis, we’ve provided you with three datasets. Attached below is a brief overview / dictionary of the data provided. 
Although we want a clear example of thoughtful and detailed analysis, we do not expect you to cover all the insights the data offers. 
Please conduct an analysis that helps us see… 
a. your approach to data-informed decision making, 
b. examples of how you use descriptive statistics, and 
c. example(s) of how you use advanced analytics (e.g., a regression, random forest, etc.) …to help stakeholders understand the value of customers using integrations. 
While we want to see substantial thought in your approach, we do not expect a perfect analysis. 


**Delivery Format **
Your final submission should include two components: 
1. A deliverable appropriate for the VP of Customer Success and the Product Manager of the Integration Marketplace. 
○ Preferred formats are a slide deck (Powerpoint/Slides, etc.) 
or a written readout (Word/Docs, PDF, etc.) 
○ Notes that illustrate your assumptions, framework, findings, recommendations, and next steps are helpful. 
2. The workbook you used (Python or R) to analyze the data.  (Imagine that a fellow analyst may use this to understand your methodologies). 
After your presentation in the interview, we’ll discuss your analytical approaches, review the findings from your analyses, and walk through your workbook. 
Timeline to Complete 
● You have one week to complete the assignment. 
We expect this to take ~6-12 hours to thoughtfully complete, though how much time you ultimately spend on this exercise is up to you. 
● If you have concerns, questions, or conflicts that make this timeline difficult, reach out to the hiring manager or recruiter. 
Additional Context 
HubSpot is a software-as-a-service (SaaS) company and therefore focused on retaining and growing our customer base. One metric we use to think about performance is customer cancellation rate -- that is, the value of lost customers divided by the beginning customer value over a certain time period. However, customer cancellation rate is just one metric used to measure the performance of customers - customer growth or upgrade rate is another way to think about customer success. 
If you are interested in how a software-as-a-service (SaaS) company operates, feel free to read this online article (https://www.forentrepreneurs.com/saas-metrics-2/) that discusses how HubSpot and other companies view their metrics. You are not required to read this article, but it can help you frame your approach if SaaS metrics are new to you. Similarly, feel free to use this as a starting point, although other approaches are welcome. 
Additionally and optionally, perusing HubSpot’s pricing page may help contextualize how we currently offer different product lines (like Marketing and Sales Hub) and different editions (like Starter or Professional). If you want more examples of integrations that our customers may leverage, you can check out our App Marketplace here. 

**Tips to be Successful **
● Keep in mind your audience - a Product Manager and a VP of Customer Success (who may not know much about the current Integrations performance). 
They may not have the data savvy (or time) to pore through pages of tables, stats, and slides. So, as possible, synthesize your key findings and analyses to ensure your stakeholders are clear on your results and recommendations. 
● The data provided is enough to help you build an initial point of view for your audience but what pieces of data would you pursue to further explore the problem? 
Datasets 
Please note that this information is intended to be illustrative and was prepared by HS to only be used during recruitment. We have adjusted the data to avoid sharing sensitive information. We ask that you do not share any documents and /or assessments produced from this case study externally without our prior written consent. 


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


![image](https://github.com/laurenzard/integrations_case_study/assets/28792951/a5dde51c-4a9f-495a-8e8d-9523b33a0a3b)
