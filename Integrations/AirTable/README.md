
# AirTable

Airtable can store information in a spreadsheet that's visually appealing and easy-to-use, but it's also powerful enough to act as a database that businesses can use for customer-relationship management (CRM), task management, project planning, and tracking inventory.

Python Version - V3_11
#### Parameters
|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Api key|The API key is used to create the connection with airtable|False|Password||
|Base id|.|False|String||
|Table name|.|False|String||


#### Dependencies
| |
|-|
|charset_normalizer-3.4.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl|
|idna-3.10-py3-none-any.whl|
|urllib3-2.5.0-py3-none-any.whl|
|airtable_python_wrapper-0.15.3-py2.py3-none-any.whl|
|certifi-2025.6.15-py3-none-any.whl|
|requests-2.32.4-py3-none-any.whl|


## Actions
#### AddOrUpdate

Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Base id|Base id|True|None||
|Table name|Table name|True|None||
|Field name|Field name|True|None||
|Json fields|Json fields|True|None||



#### Get All Records
Retrieves all the records from a given table
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Base Id|Base is a database in Airtable in which you store data. The base ID can be found in the URL of the API page of the base.|True|None||
|Table name|Each Base can include multiple tables. The parameter indicates the name of the table within the base.|True|None||
|Max Records|The maximum rows that will be affected by the action|True|None||
|Sort by|The column name you would like to sort by|False|None||
|Sort Direction|The direction of the records you would like to sort by - Descending\Ascending|True|None||



#### Enrich Entities From Table
Search specific fields (columns) in a table
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Enrichment Prefix|Prefix to use for entity enrichment|False|None||
|Max records|The maximum records (rows) that will be affected by the action|False|None||
|Base id|Base is a database in Airtable in which you store data.The base ID can be found in the URL of the API page of the base. |True|None||
|Table name|A table stores similar (structured) data, and each base can have multiple tables.  This parameter indicates the name of the table within the base.|True|None||
|Field name|The name of a specific field (column) in the table|True|None||
|Entity Field|Entity field to used for AirTable search (Can be Identifier or any other enrichment field). Default is Identifier|False|None||



#### Delete All Records
Deletes all the records in a given table
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Base Id|Base is a database in Airtable in which you store data. The base ID can be found in the URL of the API page of the base.|True|None||
|Table name|Each Base can include multiple tables. The parameter indicates the name of the table within the base.|True|None||



#### Ping
Test connection to the AirTable product
Timeout - 600 Seconds



#### Create
Create new records in a specific table
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Base id|Base is a database in Airtable in which you store data.The base ID can be found in the URL of the API page of the base. |True|None||
|Table name|A table stores similar (structured) data, and each base can have multiple tables.  This parameter indicates the name of the table within the base.|True|None||
|Json fields|The fields (columns) and their value in a JSON format. This action supports creation of multiple rows. |True|None||



#### Update
Update specific fields  in a table
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Max records|The maximum records (rows) that will be affected by the action|True|None||
|Json fields|The fields (columns) and their value in a JSON format. |True|None||
|Field value|The value of a specific field in a table|True|None||
|Field name|The name of a specific field (column) in the table|True|None||
|Table name|A table stores similar (structured) data, and each base can have multiple tables.  This parameter indicates the name of the table within the base.|True|None||
|Base id|Base is a database in Airtable in which you store data.The base ID can be found in the URL of the API page of the base. |True|None||



#### Delete
Delete specific fields (columns)  in a table
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Field value|The value of a specific field in a table|True|None||
|Field name|The name of a specific field (column) in the table|True|None||
|Table name|A table stores similar (structured) data, and each base can have multiple tables.  This parameter indicates the name of the table within the base.|True|None||
|Base id|Base is a database in Airtable in which you store data.The base ID can be found in the URL of the API page of the base. |True|None||
|Max records|The maximum records (rows) that will be affected by the action|True|None||



#### Search
Search specific fields (columns) in a table
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Field value|The value of a specific field in a table|True|None||
|Field name|The name of a specific field (column) in the table|True|None||
|Table name|A table stores similar (structured) data, and each base can have multiple tables.  This parameter indicates the name of the table within the base.|True|None||
|Base id|Base is a database in Airtable in which you store data.The base ID can be found in the URL of the API page of the base. |True|None||
|Max records|The maximum records (rows) that will be affected by the action|False|None||









## Connectors
#### AirTable Connector
The Connector ingests records from a given table in Airtable

|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Alert name field|Determines the Alert name based on the airtable column name defined in the parameter|False|None|<alert_name_field>|
|Alert name prefix|The alert name prefix|False|None|<alert_name_prefix>|
|Alert type|Determines the Alert type based on the airtable column name defined in the parameter|True|None|<alert_type>|
|Api key|Your API Key can be found in your account overview under API|True|None||
|Base id|Base is a database in Airtable in which you store data. The base ID can be found in the URL of the API page of the base.|True|None|<base_id>|
|Field name|The field name that you would like to search the value by|False|None|<field_name>|
|Field value|The value that you would like to search for under the relevant field name|False|None|<field_value>|
|Max records|The maximum rows in the table that will be affected by the action|True|None|300|
|Table name|Each Base can include multiple tables. The parameter indicates the name of the table within the base.|True|None|<table_name>|




