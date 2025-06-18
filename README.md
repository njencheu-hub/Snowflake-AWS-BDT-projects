# Snowflake-AWS-BDT-projects

### ETL SCD1 Automation Using Snowflake Tasks, Streams, and Stored Procedures  

Designed and implemented a fully automated Type 1 Slowly Changing Dimension (SCD1) data pipeline using Snowflake.  
Leveraged Python, AWS S3, and Anaconda notebooks to upload raw and change data files to S3, triggered ingestion through Snowflake’s Tasks and Streams, and executed SCD1 logic via Stored Procedures.  
Validated updates based on composite primary keys (`CONTACTFIRSTNAME`, `CONTACTLASTNAME`) to ensure in-place updates of customer records and insertion of new ones.  
Results included end-to-end automation of SCD1 processing, near-real-time updates to the customer table, and streamlined integration between cloud storage and Snowflake for scalable ETL execution.

### ETL SCD2 Automation Using DBT and Snowflake   

Designed and implemented an SCD Type 2 data pipeline using DBT Cloud integrated with Snowflake, supporting a full bronze-silver-gold architecture.  
Automated table creation, transformations, and versioned history capture using DBT macros, snapshots, and custom schema layering (silver: transient tables, gold: views).  
Enabled integration with AWS S3 staging and Snowflake file formats, with modular project design and YAML-based configurations for reproducibility and maintainability.

### Data Visualization with Snowflake and Tableau  

Connected Tableau to Snowflake using custom SQL queries to visualize large-scale transactional data from the TPCH_SF1000 sample schema.  
Built interactive dashboards to display:  
- Top 5 customers by order count  
- Top 5 nations by average quantity shipped  
- Monthly order volume and revenue for 1997  

Optimized query performance using `ROW_NUMBER`, aggregation, and efficient joins. Enhanced dashboard readability with labels, colors, and chart types such as bar and area graphs.  
Resulted in faster insights and improved storytelling from Snowflake-hosted data.