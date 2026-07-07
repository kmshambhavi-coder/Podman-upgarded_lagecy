# GitSync

## Integrations
|Name|Description|
|----|-----------|
|Azure Active Directory|Azure Active Directory (Azure AD) is Microsoft's cloud-based identity and access management service, which helps your employees sign in and access  both internal and external resources.|
|CSV|Integration designed around working with CSV files. CSV is a simple file format used to store tabular data, such as a spreadsheet or database.|
|CrowdStrike Falcon|CrowdStrike Falcon is the leader in next-generation endpoint protection, threat intelligence and incident response through cloud-based endpoint protection.|
|EmailUtilities|A set of utility actions to assist with working with emails.  Includes actions to parse EMLs and analyze email headers.|
|Google Chronicle|Google SecOps enables you to examine the aggregated security information for your enterprise going back for months or longer. Use Google SecOps to search across all of the domains accessed from within your enterprise. To enable the Google API client to communicate with the Backstory API you will need Google Developer Service Account Credential, https://developers.google.com/identity/protocols/OAuth2#serviceaccount.|
|Google SecOps AI Agents|This integration provides first-party AI agents for Google Chronicle. It allows users to leverage Google's advanced AI capabilities for security operations and threat intelligence within the Chronicle platform.|
|MISP|MISP is an open source software solution for collecting, storing, distributing and sharing cyber security indicators and threat about cyber security incidents|
|Palo Alto Cortex XDR|Cortex XDR - XDR is the world’s first detection and response app that natively integrates network, endpoint and cloud data to stop sophisticated attacks.  Cortex XDR accurately detects threats with behavioral analytics and reveals the root cause to speed up investigations.|
|TemplateEngine|Template Engine integration provides the ability to render templates using Jinja2. Jinja2 provide fast and flexible ways to create rich templates. These templates can be used in entity insights, emails, ticketing systems, or any action that can take in a text string.Jinja2 documentation can be found at https://jinja.palletsprojects.com/en/2.11.x/|


## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|29AWS Cloud Trail - Insights Connector|Pull insights from AWS Cloud Trail.|False|
|30AWS Cloud Trail - Insights Connector|Pull insights from AWS Cloud Trail.|False|
|53AWS GuardDuty - Findings Connector|Pull findings from AWS GuardDuty. Note: Whitelist works with Finding types, for example, UnauthorizedAccess:EC2/RDPBruteForce.|False|
|27AWS IAM Access Analyzer - Findings Connector|Pull findings from AWS IAM Access Analyzer. Note: Whitelist works on resource types.Example: AWS::S3::Bucket.|False|
|31AWS IAM Access Analyzer - Findings Connector|Pull findings from AWS IAM Access Analyzer. Note: Whitelist works on resource types.Example: AWS::S3::Bucket.|False|
|39AWS IAM Access Analyzer - Findings Connector|Pull findings from AWS IAM Access Analyzer. Note: Whitelist works on resource types.Example: AWS::S3::Bucket.|False|
|40AWS Security Hub - Findings Connector|Pull findings from AWS Security Hub.|False|
|25AirTable Connector|The Connector ingests records from a given table in Airtable|False|
|28AirTable Connector|The Connector ingests records from a given table in Airtable|False|
|32AirTable Connector|The Connector ingests records from a given table in Airtable|False|
|26AlienVault USM Anywhere Connector|AlienVault USM Anywhere Connector|False|
|27AlienVault USM Anywhere Connector|AlienVault USM Anywhere Connector|False|
|33AlienVault USM Anywhere Connector|AlienVault USM Anywhere Connector|False|
|16Amazon Macie - Findings Connector|Pull findings from Amazon Macie. Note: Whitelist works with Finding types, for example, SensitiveData:S3Object/Personal.|False|
|35ArcSight - Security Events Connector|Pull correlations from ArcSight. Note: dynamic list works with "name" parameter. Please refer to the doc portal for the configuration setup. This connector is suitable for Saas deployment of Chronicle SOAR and is the recommended one for production use.|False|
|50ArcSight - Security Events Connector|Pull correlations from ArcSight. Note: dynamic list works with "name" parameter. Please refer to the doc portal for the configuration setup. This connector is suitable for Saas deployment of Chronicle SOAR and is the recommended one for production use.|False|
|58ArcSight - Security Events Connector|Pull correlations from ArcSight. Note: dynamic list works with "name" parameter. Please refer to the doc portal for the configuration setup. This connector is suitable for Saas deployment of Chronicle SOAR and is the recommended one for production use.|False|
|5Arcsight ESM Connector|Arcsight ESM Connector|False|
|9ArcSight - Security Events Connector|Pull correlations from ArcSight. Note: dynamic list works with "name" parameter. Please refer to the doc portal for the configuration setup. This connector is suitable for Saas deployment of Chronicle SOAR and is the recommended one for production use.|False|
|45Azure Security Center - Security Alerts Connector|Pull security alerts from Azure Security Center. Note: whitelist works with alertType field.|False|
|48VMware Carbon Black Cloud Alerts and Events Tracking Connector|Fetch Carbon Black Cloud Alerts and Events as Events are added to Carbon Black Cloud Alerts. Connector can create multiple Siemplify alerts for single Carbon Black Cloud Alert, if Cloud Alert was updated with new events after initial ingestion by Siemplify.|False|
|60VMware Carbon Black Cloud Alerts and Events Tracking Connector|Fetch Carbon Black Cloud Alerts and Events as Events are added to Carbon Black Cloud Alerts. Connector can create multiple Siemplify alerts for single Carbon Black Cloud Alert, if Cloud Alert was updated with new events after initial ingestion by Siemplify.|False|
|10Crowdstrike Falcon Streaming Events Connector|Crowdstrike Falcon Streaming Events Connector|False|
|11Crowdstrike - Incidents Connector|Deprecated. Pull incident and related behaviors from Crowdstrike. Dynamic List works with the “incident_type” parameter.|False|
|12Crowdstrike Falcon Streaming Events Connector|Crowdstrike Falcon Streaming Events Connector|False|
|2Crowdstrike - Alerts Connector|Pull alerts from Crowdstrike. Dynamic List works with the "display_name" parameter. Note: To fetch identity protection detections use "Identity Protection Detections Connector".|False|
|43Crowdstrike - Alerts Connector|Pull alerts from Crowdstrike. Dynamic List works with the "display_name" parameter. Note: To fetch identity protection detections use "Identity Protection Detections Connector".|False|
|54Crowdstrike - Detections Connector|Deprecated. Pull detections from Crowdstrike. Whitelist works with filters that are supported by the API of Crowdstrike. For the details, please refer to the documentation portal.|False|
|8Crowdstrike - Identity Protection Detections Connector|Pull Identity Protection detections from Crowdstrike. Note: this connector requires an Identity Protection license. Dynamic List works with the “display_name” parameter.|False|
|13Google Chronicle - Chronicle Alerts Connector|Pull information about Rule based alerts from Google Chronicle. Note: dynamic list is used for filtering purposes. For all of the details please visit the documentation portal.|False|
|Google Chronicle - Chronicle Alerts Connector|Pull information about Rule based alerts from Google Chronicle. Note: dynamic list is used for filtering purposes. For all of the details please visit the documentation portal.|False|
|17Microsoft Azure Sentinel Incident Connector|DEPRECATED! Fetches Incidents from Azure Sentinel.|True|
|18Microsoft Azure Sentinel Incident Connector v2|Connector works with Microsoft Azure Sentinel incidents. Connector's Dynamic List can be used to specify the incidents names that needs to be fetched. See connector documentation for more information.|True|
|19Microsoft Azure Sentinel Incident Connector v2|Connector works with Microsoft Azure Sentinel incidents. Connector's Dynamic List can be used to specify the incidents names that needs to be fetched. See connector documentation for more information.|True|
|22Microsoft Sentinel Incident Tracking Connector|Connector works with Microsoft Azure Sentinel incidents and fetches updates to the Sentinel incidents as the new SecOps alerts. Connector's Dynamic List can be used to specify the incidents names that needs to be fetched. It is recommended to configure SecOps Alerts grouping based on SourceGroupIdentifier for this connector. See connector documentation for more information.|True|
|Microsoft Azure Sentinel Incident Connector|DEPRECATED! Fetches Incidents from Azure Sentinel.|True|
|20Microsoft Graph Mail Connector|Connector can be used to fetch emails from the Microsoft Graph Mail service. Connector dynamic list can be used to filter specific values from the email body and subject parts using regexes. By default, regex is used to filter out the urls from the email.|False|
|21Microsoft Graph Mail Delegated Connector|Connector can be used to fetch emails from the Microsoft Graph Mail service. Connector dynamic list can be used to filter specific values from the email body and subject parts using regexes. By default, regex is used to filter out the urls from the email. This connector uses Delegated Authentication in Microsoft 365 and requires interactive login of the user on behalf of which integration should communicate with Microsoft 365. To configure the connector, make sure that the integration configuration is already finished, and the refresh token needed to communicate with Office 365 is generated.|False|
|14Palo Alto Cortex XDR Connector|Pull incidents from Palo Alto XDR. Dynamic List works with the “source” parameter.|False|
|3Palo Alto Cortex XDR Connector|Pull incidents from Palo Alto XDR. Dynamic List works with the “source” parameter.|False|
|23SentinelOne - Alerts Connector|Pull alerts from SentinelOne. Dynamic List works with the “ruleInfo.name” parameter.|False|
|24SentinelOne - Threats Connector|Pull threats from SentinelOne.|False|
|15VirusTotal - Livehunt Notifications Connector|Pull information about Livehunt notifications and related files from VirusTotal. Note: this connector requires a premium API token. Dynamic list works with "rule_name" parameter.|False|
|4VirusTotal - Livehunt Notifications Connector|Pull information about Livehunt notifications and related files from VirusTotal. Note: this connector requires a premium API token. Dynamic list works with "rule_name" parameter.|False|


## Playbooks
|Name|Description|
|----|-----------|
|01Playbook1- block and widget||
|02Playbook1- block and widget||
|1Different environment||
|7 Different environment - 2||
|Block1|An embedded workflow that can receive inputs and return an output.|
|Copy of 01Playbook1- block and widget||
|Copy of Different environment||
|Different environment||
|Playbook1- block and widget||
|testing single block|An embedded workflow that can receive inputs and return an output.|


## Visual Families
|Name|Description|
|----|-----------|
|Copy of Copy of Visual Family 1|Test Description|
|Copy of Visual Family 1|Test Description|
|Generated Visual Family 1|Auto-generated description for Generated Visual Family 1|
|Generated Visual Family 10|Auto-generated description for Generated Visual Family 10|
|Generated Visual Family 11|Auto-generated description for Generated Visual Family 11|
|Generated Visual Family 12|Auto-generated description for Generated Visual Family 12|
|Generated Visual Family 13|Auto-generated description for Generated Visual Family 13|
|Generated Visual Family 14|Auto-generated description for Generated Visual Family 14|
|Generated Visual Family 15|Auto-generated description for Generated Visual Family 15|
|Generated Visual Family 16|Auto-generated description for Generated Visual Family 16|
|Generated Visual Family 17|Auto-generated description for Generated Visual Family 17|
|Generated Visual Family 18|Auto-generated description for Generated Visual Family 18|
|Generated Visual Family 19|Auto-generated description for Generated Visual Family 19|
|Generated Visual Family 2|Auto-generated description for Generated Visual Family 2|
|Generated Visual Family 20|Auto-generated description for Generated Visual Family 20|
|Generated Visual Family 21|Auto-generated description for Generated Visual Family 21|
|Generated Visual Family 22|Auto-generated description for Generated Visual Family 22|
|Generated Visual Family 23|Auto-generated description for Generated Visual Family 23|
|Generated Visual Family 24|Auto-generated description for Generated Visual Family 24|
|Generated Visual Family 25|Auto-generated description for Generated Visual Family 25|
|Generated Visual Family 26|Auto-generated description for Generated Visual Family 26|
|Generated Visual Family 27|Auto-generated description for Generated Visual Family 27|
|Generated Visual Family 28|Auto-generated description for Generated Visual Family 28|
|Generated Visual Family 29|Auto-generated description for Generated Visual Family 29|
|Generated Visual Family 3|Auto-generated description for Generated Visual Family 3|
|Generated Visual Family 30|Auto-generated description for Generated Visual Family 30|
|Generated Visual Family 31|Auto-generated description for Generated Visual Family 31|
|Generated Visual Family 32|Auto-generated description for Generated Visual Family 32|
|Generated Visual Family 33|Auto-generated description for Generated Visual Family 33|
|Generated Visual Family 34|Auto-generated description for Generated Visual Family 34|
|Generated Visual Family 35|Auto-generated description for Generated Visual Family 35|
|Generated Visual Family 36|Auto-generated description for Generated Visual Family 36|
|Generated Visual Family 37|Auto-generated description for Generated Visual Family 37|
|Generated Visual Family 38|Auto-generated description for Generated Visual Family 38|
|Generated Visual Family 39|Auto-generated description for Generated Visual Family 39|
|Generated Visual Family 4|Auto-generated description for Generated Visual Family 4|
|Generated Visual Family 40|Auto-generated description for Generated Visual Family 40|
|Generated Visual Family 41|Auto-generated description for Generated Visual Family 41|
|Generated Visual Family 42|Auto-generated description for Generated Visual Family 42|
|Generated Visual Family 43|Auto-generated description for Generated Visual Family 43|
|Generated Visual Family 44|Auto-generated description for Generated Visual Family 44|
|Generated Visual Family 45|Auto-generated description for Generated Visual Family 45|
|Generated Visual Family 46|Auto-generated description for Generated Visual Family 46|
|Generated Visual Family 47|Auto-generated description for Generated Visual Family 47|
|Generated Visual Family 48|Auto-generated description for Generated Visual Family 48|
|Generated Visual Family 49|Auto-generated description for Generated Visual Family 49|
|Generated Visual Family 5|Auto-generated description for Generated Visual Family 5|
|Generated Visual Family 50|Auto-generated description for Generated Visual Family 50|
|Generated Visual Family 51|Auto-generated description for Generated Visual Family 51|
|Generated Visual Family 52|Auto-generated description for Generated Visual Family 52|
|Generated Visual Family 53|Auto-generated description for Generated Visual Family 53|
|Generated Visual Family 54|Auto-generated description for Generated Visual Family 54|
|Generated Visual Family 55|Auto-generated description for Generated Visual Family 55|
|Generated Visual Family 56|Auto-generated description for Generated Visual Family 56|
|Generated Visual Family 57|Auto-generated description for Generated Visual Family 57|
|Generated Visual Family 58|Auto-generated description for Generated Visual Family 58|
|Generated Visual Family 59|Auto-generated description for Generated Visual Family 59|
|Generated Visual Family 6|Auto-generated description for Generated Visual Family 6|
|Generated Visual Family 60|Auto-generated description for Generated Visual Family 60|
|Generated Visual Family 7|Auto-generated description for Generated Visual Family 7|
|Generated Visual Family 8|Auto-generated description for Generated Visual Family 8|
|Generated Visual Family 9|Auto-generated description for Generated Visual Family 9|
|Visual Family 1|Test Description|
|v1alpha Test Family With Rule|Test Description|


## Jobs
|Name|Description|
|----|-----------|
|Google Chronicle Alerts Creator Job|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|Google Chronicle Sync Job|This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM. Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.|

