# BigQuery

Ways to access BigQuery :
  - CLI
  - Console
  - API Call
  
## IAM Priveleges :
  - bigquery.user
  - bigquery.jobUser
  - bigquery.admin
  
### NOTE :

There are two SQL dialects available:
  - Standard SQL
  - Legacy SQL


By default BigQuery runs on Standard SQL.

To enable Legacysql,do the following:
  - Console : Before starting query use #legacysql
  - CLI : bq query --use_legacy_sql=true \
  
  
  ### Syntax
    -  bq - to use in commandline to start bigquery
   
    - 'bq query' - to start querying
    
    - 'bq ls'  - to list the datasets available
    
    - 'bq mk' - to create your own dataset








 ### BQ for Py :
   - from google.cloud import bigquery
   - initialize client API  -- client = bigquery.Client()
   -- write Query -- query = client.query()
