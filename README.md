# Oracle-Database-Sample-Schema-Query

SQL project in Fall semester (Sep-Dec) 2023

Thanks to professor Jim Myronic guidance

1)	Install the Oracle sample schemas

Confirmation the schemas have been successfully installed;

2)	Query the installed schemas

From SQL Developer or SQL Plus, the SQL DML query and query results (i.e., result set) that successfully demonstrate:

i.	The joining of 5 tables (Note: add a row to one table that requires an outer join);

ii.	A 4 level subquery (i.e., 3 inner queries feeding a result to the outer query);

iii.	A SET query showing row and aggregate values;

iv.	A correlated subquery;

v.	Use of analytic functions: SUM(), RANK(), DENSE_RANK(), LEAD(), LAG() and CUME_DIST(), each involving PARTITION clauses.


Download the Oracle Database Sample Schemas here:
https://github.com/oracle-samples/db-sample-schemas

Install it with some configuration and changing the address path to your own installing path.
reference: https://www.youtube.com/watch?v=o7g5K-0EXb4 

Here are the first few pictures after I success installed the mksample.sql, which include BI, HR, IX, OE, PM, SH schemas:
![Picture1](https://github.com/coolerlee90/Oracle-Database-Sample-Schema-Query/assets/152518453/aea3c32f-c9ca-48d0-82fb-f72a0b0b1f82)

I found the mksample.sql does not include all the schemas. Then, except these schemas, I tried to install the CO and QS schemas individually.
For CO schema:
![Picture3](https://github.com/coolerlee90/Oracle-Database-Sample-Schema-Query/assets/152518453/d55bec67-a3c9-434a-89c7-cac674f3c2a7)
![Picture2](https://github.com/coolerlee90/Oracle-Database-Sample-Schema-Query/assets/152518453/6eecc367-a95c-4058-8387-5fed879c4a97)

Then I checked all the schema users’ status:
![Picture4](https://github.com/coolerlee90/Oracle-Database-Sample-Schema-Query/assets/152518453/03dbef35-a323-4e4b-9173-c074eec462b4)
![Picture5](https://github.com/coolerlee90/Oracle-Database-Sample-Schema-Query/assets/152518453/4cb5ca6f-9153-4dc5-b608-19f0a7b5ca8d)

Then connected my sql developer with all these schemas:
![Picture6](https://github.com/coolerlee90/Oracle-Database-Sample-Schema-Query/assets/152518453/ac9c178f-1ff1-4f88-9631-ebe0e8ad2a01)
![Picture7](https://github.com/coolerlee90/Oracle-Database-Sample-Schema-Query/assets/152518453/b59ed9ad-4a90-483c-9845-cd1320c80471)
![Picture8](https://github.com/coolerlee90/Oracle-Database-Sample-Schema-Query/assets/152518453/53eee4c9-c642-4fc6-8aaf-d8da7bcde5b7)

I found that there are just 5 tables in the CO schema, and these 5 tables connect by primary and foreign keys. These keys are product_id, order_id, customer_id, store_id. 

![Picture9](https://github.com/coolerlee90/Oracle-Database-Sample-Schema-Query/assets/152518453/756ccf00-db98-418b-a92e-be710fe9c4fc)






