**Data Dictionary for Gold Layer**

Overview
Tha Gold Layer is the business-level data representation, structured to support analytical and reporting use cases. It consist of dimension tables and fact tables for specific business metrics.

**1. gold.dim_customers**
   * Purpose: Stores customer details enriched with demographic and geographic data.
   * Columns:
     
  |Column Name|Data Type| Description|
   |---|---|---|
   |customer_key|INT|Surrogate key uniquely identifying each customer record in the dimension table.|
   |customer_id|INT|Unique numerical identifier assigned to each customer.|
   |customer_number|NVARCHAR(50)|Alphanumeric identifier  representing the customer, used for tracink and reference|
   |first_name|NVARCHAR(50)|The customer's firts name, as recorded in the system.|
   |last_name|NVARCHAR(50)|The customer's last name or family name|
   |country|NVARCHAR(50)|The country if residence for the customer (e.g., 'Australia').|
   |marital_status|NVARCHAR(50)| The arital status of the customer (e.g., 'Married', 'Single').|
   |gender|NVARCHAR(50)|The gender of the customer (e.g., 'Male', 'Female', 'n/a').|
   |birthdate|DATE|The date of birth of the customer, formatted as YYYY-MM-DD (e.g., 1971-10-06).|
   |create_date|DATE|The date and time when the customer record was created in the system.|


  |
  
