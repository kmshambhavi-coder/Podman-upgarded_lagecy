
# SentinelOneV2

Endpoint security software that defends every endpoint against every type of attack, at every stage in the threat lifecycle.

Python Version - V3_11
#### Parameters
|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Api Root|None|True|String||
|API Token|None|True|Password||
|Verify SSL|None|False|Boolean||


#### Dependencies
| |
|-|
|requests_toolbelt-1.0.0-py2.py3-none-any.whl|
|proto_plus-1.27.2-py3-none-any.whl|
|uritemplate-4.2.0-py3-none-any.whl|
|rsa-4.9.1-py3-none-any.whl|
|googleapis_common_protos-1.74.0-py3-none-any.whl|
|pycparser-3.0-py3-none-any.whl|
|python_dateutil-2.9.0.post0-py2.py3-none-any.whl|
|cryptography-46.0.7-cp311-abi3-manylinux_2_34_x86_64.whl|
|protobuf-7.34.1-cp310-abi3-manylinux2014_x86_64.whl|
|anyio-4.13.0-py3-none-any.whl|
|types_python_dateutil-2.9.0.20240821-py3-none-any.whl|
|chardet-5.2.0-py3-none-any.whl|
|google_auth_httplib2-0.3.0-py3-none-any.whl|
|pyparsing-3.3.2-py3-none-any.whl|
|sniffio-1.3.1-py3-none-any.whl|
|httpx-0.28.1-py3-none-any.whl|
|pyasn1_modules-0.4.2-py3-none-any.whl|
|six-1.16.0-py2.py3-none-any.whl|
|google_api_python_client-2.188.0-py3-none-any.whl|
|httplib2-0.31.2-py3-none-any.whl|
|google_api_core-2.30.3-py3-none-any.whl|
|idna-3.11-py3-none-any.whl|
|cffi-2.0.0-cp311-cp311-manylinux2014_x86_64.manylinux_2_17_x86_64.whl|
|arrow-1.3.0-py3-none-any.whl|
|typing_extensions-4.15.0-py3-none-any.whl|
|requests-2.32.5-py3-none-any.whl|
|h11-0.16.0-py3-none-any.whl|
|TIPCommon-2.3.4-py3-none-any.whl|
|google_auth-2.47.0-py3-none-any.whl|
|pycryptodome-3.23.0-cp37-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl|
|charset_normalizer-3.4.7-cp311-cp311-manylinux2014_x86_64.manylinux_2_17_x86_64.manylinux_2_28_x86_64.whl|
|urllib3-2.6.3-py3-none-any.whl|
|pyopenssl-25.3.0-py3-none-any.whl|
|EnvironmentCommon-1.0.2-py2.py3-none-any.whl|
|pyasn1-0.6.3-py3-none-any.whl|
|httpcore-1.0.9-py3-none-any.whl|
|certifi-2026.2.25-py3-none-any.whl|
|cachetools-6.2.4-py3-none-any.whl|


## Actions
#### Create Device Control Rule
Create a Device Control Rule in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Rule JSON|JSON object of the device control rule.|True|None||
|Scope JSON|JSON object of the scope rule.|True|None||



#### Create Hash Blacklist Record
Add hashes to a blacklist in SentinelOne. Note: Only SHA1 hashes are supported.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Operating System|Specify the OS for the hash. Possible values: windows, windows_legacy, macos, linux.|True|None||
|Site IDs|Specify a comma-separated list of site ids, where hash needs to be sent to the blacklist.|False|None||
|Group IDs|Specify a comma-separated list of group ids, where hash needs to be sent to the blacklist.|False|None||
|Account IDs|Specify a comma-separated list of account ids, where hash needs to be sent to the blacklist.|False|None||
|Description|Specify additional information related to the hash.|False|None||
|Add to global black list|If enabled, action will add the hash to the global blacklist. Note: when this parameter is enabled, parameters “Site IDs“, “Group IDs“ and “Account IDs“ are ignored.|False|None||



#### Create Hash Exclusion Record
Add hash to the exclusion list in SentinelOne. Note: Only SHA1 hashes are supported.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Operation System|Specify the OS for the hash. Possible values: windows, windows_legacy, macos, linux.|True|None||
|Site IDs|Specify a comma-separated list of site ids, where hash needs to be sent to the exclusion list.|False|None||
|Group IDs|Specify a comma-separated list of group ids, where hash needs to be sent to the exclusion list.|False|None||
|Account IDs|Specify a comma-separated list of account ids, where hash needs to be sent to the exclusion list.|False|None||
|Description|Specify additional information related to the hash.|False|None||
|Add to global exclusion list|If enabled, action will add the hash to the global exclusion list. Note: when this parameter is enabled, parameters “Site IDs“, “Group IDs“ and “Account IDs“ are ignored.|False|None||



#### Create Path Exclusion Record
Add path to the exclusion list in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Path|Specify the path that needs to be added to the exclusion list.|True|None||
|Operation System|Specify the OS for the path. Possible values: windows, windows_legacy, macos, linux.|True|None||
|Site IDs|Specify a comma-separated list of site ids, where path needs to be sent to the exclusion list.|False|None||
|Group IDs|Specify a comma-separated list of group ids, where path needs to be sent to the exclusion list.|False|None||
|Account IDs|Specify a comma-separated list of account ids, where path needs to be sent to the exclusion list.|False|None||
|Description|Specify additional information related to the path.|False|None||
|Add to global exclusion list|If enabled, action will add the path to the global exclusion list. Note: when this parameter is enabled, parameters “Site IDs“, “Group IDs“ and “Account IDs“ are ignored.|False|None||
|Include Subfolders|If enabled, action will include subfolders for the provided path. This feature only works, if user provides folder path and not file path.|False|None||
|Mode|Specify what mode should be used for the excluded path.|False|None||



#### Delete Device Control Rule
Delete a Device Control Rule in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Rule ID|ID of the rule that needs to be deleted.|True|None||
|Scope Type|Scope type in which the alert is available.|False|None||
|Scope ID|ID of the scope.|True|None||



#### Delete Hash Blacklist Record
Delete hashes from a blacklist in SentinelOne. Note: Only SHA1 hashes are supported.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Site IDs|Specify a comma-separated list of site ids, from where the hash needs to be removed.|False|None||
|Group IDs|Specify a comma-separated list of group ids, from where the hash needs to be removed.|False|None||
|Account IDs|Specify a comma-separated list of account ids, from where the hash needs to be removed.|False|None||
|Remove from global black list|If enabled, action will remove the hash from the global black list. Note: when this parameter is enabled, parameters "Site IDs", "Group IDs" and "Account IDs" are ignored.|False|None||



#### Disconnect Agent From Network
Disconnect agent from network by it's host name or IP address.
Timeout - 600 Seconds



#### Download Threat File
Download file related to threat in SentinelOne. Note: Your user role must have permissions to Fetch Threat File - Admin, IR Team, SOC.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Threat ID|Specify the id of the threat for which you want to download the file.|True|None||
|Password|Specify the password for the zip that contains the threat file. Password requirements: At least 10 characters. Three of these: uppercase, lowercase, digits, special symbols. Maximum length is 256 characters.|True|None||
|Download Folder Path|Specify the path to the folder, where you want to store the threat file.|True|None||
|Overwrite|If enabled, action will overwrite the file with the same name.|False|None||



#### Enrich Endpoint
Enrich information about the endpoint by IP address or Hostname.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Create Insight|If enabled, action will create an insight with information about endpoints.|False|None||
|Only Infected Endpoints Insights|If enabled, action will only create insights for the infected endpoints.|False|None||



#### Get Agent Status
Retrieve information about the status of the agents on the endpoints based on the IP or Hostname entity.
Timeout - 600 Seconds



#### Get Application List For Endpoint
Retrieve information about available applications on the endpoint by IP or Hostname.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Max Applications To Return|Specify how many applications to return. If nothing is specified action will return all of the applications.|False|None||



#### Get Blacklist
Get a list of all the items available in the blacklist in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Hash|Specify a comma-separated list of hashes that need to be checked in blacklist. Only hashes that were found will be returned. If nothing is specified here action will return all hashes. Note: if "Hash" parameter is provided then "Limit" parameter is ignored.|False|None||
|Site IDs|Specify a comma-separated list of site ids, which should be used to return blacklist items.|False|None||
|Group IDs|Specify a comma-separated list of group ids, which should be used to return blacklist items.|False|None||
|Account IDs|Specify a comma-separated list of account ids, which should be used to return blacklist items.|False|None||
|Limit|Specify how many blacklist items should be returned. Note: if "Hash" parameter has values, then this parameter is ignored. Maximum is 1000.|False|None||
|Query|Specify the query that needs to be used in order to filter the results.|False|None||
|Use Global Blacklist|If enabled, action will also return hashes from the global blacklist.|False|None||



#### Get Deep Visibility Query Result
Retrieve information about deep visibility query results. Note: this action should be used in combination with “Initiate Deep Visibility Query“.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Query ID|Specify the ID of the query for which you want to return results. This ID is available in the JSON result of the action “Initiate Deep Visibility Query“ as “query_id“ parameter.|True|None||
|Limit|Specify how many events to return. Default: 50. Maximum is 100.|False|None||



#### Get Events For Endpoint Hours Back
Retrieve information about the latest events on the endpoint. Works with IP and Hostname entities.Note: this action uses an endpoint that has rate limiting. Only one endpoint can be processed per minute․
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Hours Back|Specify how many hours backwards to fetch events.|True|None||
|Events Amount Limit|Specify how many events to return per event type. Default: 50.|False|None||
|Include File Events Information|If enabled, action will also query information about file events.|False|None||
|Include Indicator Events Information|If enabled, action will also query information about indicator events.|False|None||
|Include DNS Events Information|If enabled, action will also query information about DNS events.|False|None||
|Include Network Actions Events Information|If enabled, action will also query information about “network actions” events.|False|None||
|Include URL Events Information|If enabled, action will also query information about URL events.|False|None||
|Include Registry Events Information|If enabled, action will also query information about registry events.|False|None||
|Include Scheduled Task Events Information|If enabled, action will also query information about scheduled task events.|False|None||



#### Get Group Details
Retrieve detailed information about the provided groups.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Group Names|Specify a comma-separated list of group names for which you want to retrieve details.|True|None||



#### Get Hash Reputation
Deprecated! Retrieve information about the hashes from SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Reputation Threshold|Specify what should be the reputation threshold in order it to be marked as suspicious. If nothing is provided, action will not mark entites as suspicious. Maximum: 10.|False|None||
|Create Insight|If enabled, action will create an insight containing information about the reputation.|False|None||
|Only Suspicious Hashes Insight|If enabled, action will only create insight for hashes that have higher or equal reputation to “Reputation Threshold“ value.|False|None||



#### Get Site Agents
Get information about agents related to a Site in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Site Name|The name of the site to return.|True|None||
|Max Agents To Return|The maximum number of agents to return. Maximum: 1000.|True|None||



#### Get System Status
Fetch system status.
Timeout - 600 Seconds



#### Get System Version
Fetch system version.
Timeout - 600 Seconds



#### Get Threats
Retrieve information about threats in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Mitigation Status|Specify the comma-separated list of threat statuses. Only threats that match the statuses will be returned. Possible values: mitigated, active, blocked, suspicious, suspicious_resolved|False|None||
|Created until|Specify the end time for the threats. Example: 2020-03-02T21:30:13.014874Z|False|None||
|Created from|Specify the start time for the threats. Example: 2020-03-02T21:30:13.014874Z|False|None||
|Resolved Threats|If enabled, action will only return resolved threats.|False|None||
|Threat Display Name|Specify a display name of the threat that you want to return. Partial name will also work.|False|None||
|Limit|Specify how many threats to return. Default: 10.|False|None||
|API Version|Specify what version of API to use in the action. If nothing is provided connector will use version 2.1. Note: JSON result structure is different between API versions. It is recommended to use the latest one.|False|None||



#### Initiate Deep Visibility Query
Initiate a Deep Visibility Query search. Returns query id, which should be used in the action "Get Deep Visibility Query Result".
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Query|Specify the query for the search.|True|None||
|Start Date|Specify the start date for the search. If nothing is specified, action will fetch events from 30 days ago.|False|None||
|End Date|Specify the end date for the search. If nothing is specified, action will use current time.|False|None||



#### Initiate Full Scan
Initiate a full disk scan on the endpoint in SentinelOne.
Timeout - 600 Seconds



#### List Sites
List available sites in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Filter Key|Specify the key that needs to be used to filter sites.|False|None||
|Filter Logic|Specify what filter logic should be applied. Filtering logic is working based on the value provided in the "Filter Key" parameter.|False|None||
|Filter Value|Specify what value should be used in the filter. If "Equal" is selected, action will try to find the exact match among results and if "Contains" is selected, action will try to find results that contain that substring. If nothing is provided in this parameter, the filter will not be applied. Filtering logic is working based on the value  provided in the "Filter Key" parameter.|False|None||
|Max Records To Return|Specify how many records to return.|False|None||



#### Mark as Threat
Marks suspicious threats as a true positive threat in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Threat IDs|Specify a comma-separated list of threat IDs that should be marked.|True|None||



#### Mitigate Threat
Executes mitigation actions on the threats in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Mitigation action|Specify the mitigation actions for the provided threats.|True|None||
|Threat IDs|Specify a comma-separated list of threat IDs that should be mitigated.|True|None||



#### Move Agents
Move agents to the provided group. This action works with Hostname and IP address entities. Note: the group should be from the same site.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Group ID|Specify the ID of the group, where to move the agents.|False|None||
|Group Name|Specify the name of the group, where to move the agents. Note: if both Group ID and Group Name are provided, action will put “Group ID“ in the priority.|False|None||



#### Ping
Test integration connectivity.
Timeout - 600 Seconds



#### Reconnect Agent To The Network
Reconnect disconnected endpoint to the network. Works with Hostname and IP entities.
Timeout - 600 Seconds



#### Resolve Threat
Resolve threats in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Threat IDs|Specify a comma-separated list of threat IDs that need to be resolved.|True|None||
|Annotation|Specify an annotation describing, why the threat can be resolved.|False|None||



#### Update Alert
Update an alert in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Alert ID|Specify the ID of the alert that needs to be updated.|True|None||
|Status|Specify the status for the alert.|False|None||
|Verdict|Specify the verdict for the alert.|False|None||



#### Update Analyst Verdict
Update analyst verdict of the threat in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Threat ID|Specify a comma-separated list of threat ids for which you want to update the analyst verdict.|True|None||
|Analyst Verdict|Specify the analyst verdict.|True|None||



#### Update Device Control Rule
Update a Device Control Rule in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Rule ID|ID of the rule that needs to be updated|True|None||
|Rule JSON|JSON object of the device control rule.|True|None||



#### Add Threat Note
Add a note to the threat in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Threat ID|Specify the id of the threat for which you want to add a note.|True|None||
|Note|Specify the note that needs to be added to the threat.|True|None||



#### Update Incident Status
Update threat incident status in SentinelOne.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Threat ID|Specify a comma-separated list of threat ids for which you want to update the incident status.|True|None||
|Status|Specify the incident status.|True|None||






## Jobs

#### Sync Alerts
This job will synchronize Google SecOps Alerts and SentinelOne alerts. The job synchronizes status. Requires “SentinelOne Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” you will need to add an “Alert_ID” Alert Context Value for the job to be able to find the correct information.

|Name|IsMandatory|Type|DefaultValue|
|----|-----------|----|------------|
|Environment Name|True|None|Default Environment|
|API Root|True|None||
|API Token|True|None||
|Max Hours Backwards|False|None|24|
|Verify SSL|False|None|true|

#### Sync Threats
This job will synchronize Google SecOps Alerts and SentinelOne threats. The job synchronizes comments and status. Requires “SentinelOne Threat” tag on the case. Note: If the alert didn’t originate from “Threats Connector” you will need to add an “Threat_ID” Alert Context Value for the job to be able to find the correct information. 

|Name|IsMandatory|Type|DefaultValue|
|----|-----------|----|------------|
|Environment Name|True|None|Default Environment|
|API Root|True|None||
|API Token|True|None||
|Max Hours Backwards|True|None|24|
|Verify SSL|False|None|true|



## Connectors
#### SentinelOne - Alerts Connector
Pull alerts from SentinelOne. Dynamic List works with the “ruleInfo.name” parameter.

|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Max Hours Backwards|Amount of hours from where to fetch alerts.|True|None|24|
|Environment Field Name|Describes the name of the field where the environment name is stored. If the environment field isn't found, the environment is the default environment.|False|None||
|Environment Regex Pattern|A regex pattern to run on the value found in the "Environment Field Name" field. Default is .* to catch all and return the value unchanged. Used to allow the user to manipulate the environment field via regex logic. If the regex pattern is null or empty, or the environment value is null, the final environment result is the default environment.|False|None|.*|
|API Root|Address of SentinelOne API root.|True|None||
|API Token|SentinelOne API token.|True|None||
|Status Filter|Comma-separated list of status that should be ingested. Possible values: Unresolved, In Progress, Resolved. If nothing is provided, the connector will fetch alerts with statuses Unresolved and InProgress.|False|None|Unresolved, In Progress|
|Case Name Template|When provided, connector will add a new key called "custom_case_name" to the Event. It can used to have a customer case name. Please refer to the documentation portal for more details. You can provide placeholders in the following format: [name of the field]. Example: Phishing - [event_mailbox]. Note: connector will use first Siemplify Event for placeholders. Only keys that have string value will be handled.|False|None||
|Alert Name Template|If provided, connector will use this value for Alert Name. Please refer to the documentation portal for more details. You can provide placeholders in the following format: [name of the field]. Example: Phishing - [event_mailbox]. Note: connector will use first Siemplify Event for placeholders. Only keys that have string value will be handled. If nothing is provided or user provides an invalid template, connector will use the default alert name.|False|None||
|Lowest Severity To Fetch|Lowest severity of the alerts to fetch. If nothing is provided, the connector will ingest alerts with all severities. Possible Values: Info, Low, Medium, High, Critical.|False|None||
|Max Alerts To Fetch|How many alerts to process per one connector iteration. Maximum: 100.|True|None|10|
|Use dynamic list as a blocklist|If enabled, the dynamic list will be used as a blocklist.|False|None|false|
|Disable Overflow|If enabled, connector will ignore the overflow mechanism.|False|None|true|
|Verify SSL|If enabled, verify the SSL certificate for the connection to the SentinelOne server is valid.|False|None|true|
|Proxy Server Address|The address of the proxy server to use.|False|None||
|Proxy Username|The proxy username to authenticate with.|False|None||
|Proxy Password|The proxy password to authenticate with.|False|None||


#### SentinelOne - Threats Connector
Pull threats from SentinelOne.

|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|API Root|Address of SentinelOne API root.|True|None|https://usea1-partners.sentinelone.net/|
|API Token|SentinelOne API token.|True|None||
|Verify SSL|If enabled, verify the SSL certificate for the connection to the Sentinel public cloud server is valid.|False|None|TRUE|
|Fetch Max Days Backwards|Number of days before the first connector iteration to retrieve threats from. This parameter applies to the initial connector iteration after you enable the connector for the first time, or used as a fallback value in cases where connector's last run timestamp expires.|False|None|1|
|Disable Overflow|If enabled, connector will ignore the overflow mechanism.|False|None|false|
|Max Alerts Per Cycle|How many alerts should be processed during one connector run.|True|None|25|
|Event Object Type Filter|A comma-separated list of event objects that need to be returned alongside threat info. This parameter is used as a filter to only return certain objects. Examples: process,ip,indicators. If nothing is provided, the connector will ingest all event object types.|False|None||
|Event Type Filter|A comma-separated list of event types that need to be returned alongside threat info. This parameter is used as a filter to only return certain event types. Examples: Process Creation, Behavioral Indicators.|False|None||
|Max Events To Return|How many events to return per threat. Maximum: 199.|False|None|199|
|Use whitelist as a blacklist|If enabled, whitelist will be used as a blacklist.|False|None|FALSE|
|Environment Field Name|Describes the name of the field where the environment name is stored. If the environment field isn't found, the environment is the default environment.|False|None||
|Environment Regex Pattern|A regex pattern to run on the value found in the "Environment Field Name" field. Default is .* to catch all and return the value unchanged. Used to allow the user to manipulate the environment field via regex logic. If the regex pattern is null or empty, or the environment value is null, the final environment result is the default environment.|False|None|.*|
|Proxy Server Address|The address of the proxy server to use.|False|None||
|Proxy Username|The proxy username to authenticate with.|False|None||
|Proxy Password|The proxy password to authenticate with.|False|None||
|API Version|Specify what version of api to use in the connector. If nothing is provided connector will use version 2.1. Note: Siemplify Event structure is different between API versions. It is recommended to use the latest one. Possible values: 2.0, 2.1.|False|None|2.0|




