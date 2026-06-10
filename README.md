# GitSync

## Integrations
|Name|Description|
|----|-----------|
|AWS Cloud Trail|AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command line tools, and other AWS services. This event history simplifies security analysis, resource change tracking, and troubleshooting. In addition, you can use CloudTrail to detect unusual activity in your AWS accounts. These capabilities help simplify operational analysis and troubleshooting.|
|CA Service Desk Manager|CA Service Desk Manager is designed to help IT service desk analysts make every moment count through a dynamic experience so they can deliver great customer service without the fear of overbearing processes or metrics. With the solution, teams can embrace teamwork rather than working from siloed knowledge stashes and disjointed communications.|
|Connectors|A set of custom connectors created for Google SecOps Community to power up automation capabilities.|
|Exchange|Integration provides support for Microsoft Exchange 2010 - 2019 and Microsoft Office365 mail servers. Integration uses Exchange Web Services (EWS) for communication. Integration includes a series of actions to send out emails and work with received emails, along with a connector to monitor specific mailboxes and ingest emails from that mailboxes as alerts to Google SecOps for further analysis.|
|Microsoft Azure Sentinel|Microsoft Azure Sentinel is a scalable, cloud-native, security information event management (SIEM) and security orchestration automated response (SOAR) solution. Azure Sentinel delivers intelligent security analytics and threat intelligence across the enterprise, providing a single solution for alert detection, threat visibility, proactive hunting, and threat response.|
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
|Generated PB for Akamai - add_items_to_client_list - 1ab0fa|Auto-generated playbook invoking Akamai > add_items_to_client_list|
|Generated PB for Akamai - add_items_to_network_list - d85216|Auto-generated playbook invoking Akamai > add_items_to_network_list|
|Generated PB for AnomaliStaxx - Ping - 09c374|Auto-generated playbook invoking AnomaliStaxx > Ping|
|Generated PB for AnomaliStaxx - Ping - 853ea8|Auto-generated playbook invoking AnomaliStaxx > Ping|
|Generated PB for Area1 - SearchIndicator - 5cb2bd|Auto-generated playbook invoking Area1 > SearchIndicator|
|Generated PB for Automox - EnrichEntities - 228788|Auto-generated playbook invoking Automox > EnrichEntities|
|Generated PB for Automox - ListPolicies - 9998c7|Auto-generated playbook invoking Automox > ListPolicies|
|Generated PB for CiscoVulnerabilityManagement - EnrichEntities - a2e1f3|Auto-generated playbook invoking CiscoVulnerabilityManagement > EnrichEntities|
|Generated PB for CiscoVulnerabilityManagement - ListAssetVulnerabilities - 10dbb4|Auto-generated playbook invoking CiscoVulnerabilityManagement > ListAssetVulnerabilities|
|Generated PB for CyberArkCredentialProvider - get_application_password_value - 685a80|Auto-generated playbook invoking CyberArkCredentialProvider > get_application_password_value|
|Generated PB for CyberArkCredentialProvider - run_cli_application_password_sdk_command - 20605d|Auto-generated playbook invoking CyberArkCredentialProvider > run_cli_application_password_sdk_command|
|Generated PB for ElasticSearch - AdvancedESSearch - 88084d|Auto-generated playbook invoking ElasticSearch > AdvancedESSearch|
|Generated PB for ElasticSearch - SimpleESSearch - 82ef4d|Auto-generated playbook invoking ElasticSearch > SimpleESSearch|
|Generated PB for FireEyeEX - DeleteQuarantinedEmail - ac878a|Auto-generated playbook invoking FireEyeEX > DeleteQuarantinedEmail|
|Generated PB for FireEyeEX - DownloadAlertArtifacts - 840e27|Auto-generated playbook invoking FireEyeEX > DownloadAlertArtifacts|
|Generated PB for GoogleAlertCenter - DeleteAlert - 1228bd|Auto-generated playbook invoking GoogleAlertCenter > DeleteAlert|
|Generated PB for GoogleAlertCenter - Ping - 0ff8b9|Auto-generated playbook invoking GoogleAlertCenter > Ping|
|Generated PB for GoogleChronicle - AddEntryToWatchlist - 27cbea|Auto-generated playbook invoking GoogleChronicle > AddEntryToWatchlist|
|Generated PB for GoogleChronicle - EnrichEntities - 38cf04|Auto-generated playbook invoking GoogleChronicle > EnrichEntities|
|Generated PB for GoogleCloudApi - ExecuteHTTPRequest - 550421|Auto-generated playbook invoking GoogleCloudApi > ExecuteHTTPRequest|
|Generated PB for GoogleCloudApi - Ping - 37e64f|Auto-generated playbook invoking GoogleCloudApi > Ping|
|Generated PB for HTTPV2 - ExecuteHTTPRequest - 84f6ab|Auto-generated playbook invoking HTTPV2 > ExecuteHTTPRequest|
|Generated PB for HTTPV2 - Ping - b88859|Auto-generated playbook invoking HTTPV2 > Ping|
|Generated PB for MISP - PublishEvent - 02d5d1|Auto-generated playbook invoking MISP > PublishEvent|
|Generated PB for MISP - UnpublishEvent - c21c22|Auto-generated playbook invoking MISP > UnpublishEvent|
|Generated PB for McAfeeEPO - AddTag - 632c88|Auto-generated playbook invoking McAfeeEPO > AddTag|
|Generated PB for McAfeeEPO - GetVirusEngineAgentVersion - 671abb|Auto-generated playbook invoking McAfeeEPO > GetVirusEngineAgentVersion|
|Generated PB for McAfeeMvisionEDRV2 - CreateInvestigation - 2e4a79|Auto-generated playbook invoking McAfeeMvisionEDRV2 > CreateInvestigation|
|Generated PB for McAfeeMvisionEDRV2 - Ping - 37a331|Auto-generated playbook invoking McAfeeMvisionEDRV2 > Ping|
|Generated PB for McAfeeTIEDXL - GetFileReferences - 3c592b|Auto-generated playbook invoking McAfeeTIEDXL > GetFileReferences|
|Generated PB for McAfeeTIEDXL - GetFileReputation - 39db96|Auto-generated playbook invoking McAfeeTIEDXL > GetFileReputation|
|Generated PB for MicroFocusITSMA - CreateIncident - d7a464|Auto-generated playbook invoking MicroFocusITSMA > CreateIncident|
|Generated PB for MicroFocusITSMA - UpdateIncidentExternalStatus - 5be583|Auto-generated playbook invoking MicroFocusITSMA > UpdateIncidentExternalStatus|
|Generated PB for Phishrod - MarkIncident - 1f141a|Auto-generated playbook invoking Phishrod > MarkIncident|
|Generated PB for Phishrod - Ping - 673ecd|Auto-generated playbook invoking Phishrod > Ping|
|Generated PB for ProofPointPS - EnrichEntities - 683d0e|Auto-generated playbook invoking ProofPointPS > EnrichEntities|
|Generated PB for ProofPointPS - Ping - 900ced|Auto-generated playbook invoking ProofPointPS > Ping|
|Generated PB for Protectwise - GetPcap - 249e58|Auto-generated playbook invoking Protectwise > GetPcap|
|Generated PB for Protectwise - Ping - 094e45|Auto-generated playbook invoking Protectwise > Ping|
|Generated PB for ReversinglabsTitanium - GetMalwareDetails - 9ceb4a|Auto-generated playbook invoking ReversinglabsTitanium > GetMalwareDetails|
|Generated PB for ReversinglabsTitanium - Ping - 8df57c|Auto-generated playbook invoking ReversinglabsTitanium > Ping|
|Generated PB for SCCM - EnrichEntities - ff015f|Auto-generated playbook invoking SCCM > EnrichEntities|
|Generated PB for SCCM - Ping - 23e6dc|Auto-generated playbook invoking SCCM > Ping|
|Generated PB for Salesforce - CloseCase - f6ca1f|Auto-generated playbook invoking Salesforce > CloseCase|
|Generated PB for Salesforce - ListCases - 194f2b|Auto-generated playbook invoking Salesforce > ListCases|
|Generated PB for SonicWall-Beta - AddURIListToURIGroup - cf1f3e|Auto-generated playbook invoking SonicWall-Beta > AddURIListToURIGroup|
|Generated PB for SonicWall-Beta - ListURILists - ec3a78|Auto-generated playbook invoking SonicWall-Beta > ListURILists|
|Generated PB for SymantecContentAnalysis - Ping - 431f1b|Auto-generated playbook invoking SymantecContentAnalysis > Ping|
|Generated PB for SymantecContentAnalysis - SubmitFile - c594a3|Auto-generated playbook invoking SymantecContentAnalysis > SubmitFile|
|Generated PB for Talos - GetReputation - fc5fb9|Auto-generated playbook invoking Talos > GetReputation|
|Generated PB for Talos - WhoIs - 51fe83|Auto-generated playbook invoking Talos > WhoIs|
|Generated PB for TrendMicroApexCentral - CreateEntityUDSO - 82bf9f|Auto-generated playbook invoking TrendMicroApexCentral > CreateEntityUDSO|
|Generated PB for TrendMicroApexCentral - EnrichEntities - 65c43a|Auto-generated playbook invoking TrendMicroApexCentral > EnrichEntities|
|Generated PB for TrendMicroDDAN - SubmitFile - d9edf1|Auto-generated playbook invoking TrendMicroDDAN > SubmitFile|
|Generated PB for TrendMicroDDAN - SubmitFileURL - 4ca3f7|Auto-generated playbook invoking TrendMicroDDAN > SubmitFileURL|
|Generated PB for Twilio - Ping - ae0991|Auto-generated playbook invoking Twilio > Ping|
|Generated PB for Twilio - SendSMSAndWait - 0290d5|Auto-generated playbook invoking Twilio > SendSMSAndWait|
|Generated PB for Vectra - AddTags - 309dcf|Auto-generated playbook invoking Vectra > AddTags|
|Generated PB for Vectra - UpdateNote - e76982|Auto-generated playbook invoking Vectra > UpdateNote|
|Generated PB for Wildfire - GetFile - 8cb44d|Auto-generated playbook invoking Wildfire > GetFile|
|Generated PB for Wildfire - GetPcap - e83b0f|Auto-generated playbook invoking Wildfire > GetPcap|
|New Block|An embedded workflow that can receive inputs and return an output.|
|Widget Playbook|Auto-generated playbook invoking Area1 > GetRecentIndicators|


## Jobs
|Name|Description|
|----|-----------|
|CA Close Ticket In CA For Closed Case|Sync closure of the tickets at the CA Desk Manager with Siemplify cases closure.|
|Sync Incidents|Deprecated. This job synchronizes Google SecOps Alerts and Microsoft Sentinel Incidents. It ensures that comments, status, and tags are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the “Microsoft Sentinel Incident” tag. If the alert didn’t originate from “Microsoft Azure Sentinel Incident Connector v2”,  you will need to add an “Incident_ID” context value to the case for the job to be able to find the correct information.|

