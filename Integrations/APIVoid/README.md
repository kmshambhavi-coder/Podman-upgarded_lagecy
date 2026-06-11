
# APIVoid

Database of API services mostly focused on threat analysis and threat intelligence, that can be easily integrated anywhere.

Python Version - V3_11
#### Parameters
|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Api Root|None|True|String|https://endpoint.apivoid.com|
|Api Key|None|True|Password|*****|
|Verify SSL|None|False|Boolean|False|


#### Dependencies
| |
|-|
|TIPCommon-1.0.11-py2.py3-none-any.whl|
|idna-3.7-py3-none-any.whl|
|charset_normalizer-3.3.2-py3-none-any.whl|
|chardet-5.2.0-py3-none-any.whl|
|requests-2.31.0-py3-none-any.whl|
|certifi-2024.2.2-py3-none-any.whl|
|urllib3-2.2.1-py3-none-any.whl|


## Actions
#### Get Screenshot
Capture a high-quality screenshot of any website or URL
Timeout - 600 Seconds





#### Get Ip Reputation
Detect potentially malicious IP addresses commonly used for spam, to attack websites or to commit fraudulent activities
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Threshold|IP risk threshold. The threshold must be a numeric value. e.g. 3|True|String|0|
|Create Insights|Specify whether the action should create insights or not.|False|Boolean|true|





#### Get URL Reputation
Get safety reputation and risk score of an URL
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Threshold|URL risk threshold. The threshold must be a numeric value. e.g. 3|True|String|0|





#### Get domain reputation
Check if a domain is blacklisted by popular and trusted domain blacklist services.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Threshold|Domain risk threshold. The threshold must be a numeric value. e.g. 3|True|String|0|
|Create Insights|Specify whether the action should create insights or not.|False|Boolean|true|





#### Verify Email
Check if an email is disposable, if it has MX records and more
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Threshold|Email risk threshold. The threshold must be a numeric value. e.g. 3|True|String|0|





#### Ping
Test Connectivity
Timeout - 600 Seconds









