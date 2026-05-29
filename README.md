# GitSync

## Integrations
|Name|Description|
|----|-----------|
|AlienVault USM Anywhere|AlienVault USM Anywhere delivers powerful threat detection, incident response, and compliance management for cloud, on-premises, and hybrid environments.|
|Azure Active Directory|Azure Active Directory (Azure AD) is Microsoft's cloud-based identity and access management service, which helps your employees sign in and access  both internal and external resources.|
|CrowdStrike Falcon|CrowdStrike Falcon is the leader in next-generation endpoint protection, threat intelligence and incident response through cloud-based endpoint protection.|
|Cybersixgill Actionable Alerts|By integrating Cybersixgill actionable alerts, Google SecOps customers gain a premium,automated threat intelligence solution based on the most comprehensive data sources from the deep, dark and surface web. It is customizable, enabling users to define key assets relevant to their brand, industry, and geolocation. Users can covertly monitor critical assets such as IP addresses, domains, vulnerabilities, and VIPs for activity on the underground and closed sources - and prioritize, as well as respond to threats directly from the Google SecOps dashboard.|
|EmailUtilities|A set of utility actions to assist with working with emails.  Includes actions to parse EMLs and analyze email headers.|
|Enrichment|A set of entity enrichment actions to assist in the managing of entity attributes.|
|FileUtilities|A set of file utility actions created for Google SecOps Community to power up playbook capabilities.|
|Functions|A set of math and data manipulation actions created for Google SecOps Community to power up playbook capabilities.|
|Google Chronicle|Google SecOps enables you to examine the aggregated security information for your enterprise going back for months or longer. Use Google SecOps to search across all of the domains accessed from within your enterprise. To enable the Google API client to communicate with the Backstory API you will need Google Developer Service Account Credential, https://developers.google.com/identity/protocols/OAuth2#serviceaccount.|
|Microsoft Graph Mail|Microsoft 365 and Office 365 deliver the power of cloud productivity to businesses of all sizes, helping save time, money, and free up valued resources. The Microsoft 365 and Office 365 plans combine the familiar Microsoft Office desktop suite with cloud-based versions of Microsoft's next-generation communications and collaboration services (including Office for the web, Microsoft Exchange Online, Microsoft Teams, and Microsoft SharePoint Online) to help users be productive from virtually anywhere through the Internet. This integration uses Microsoft Graph Mail API to communicate with Microsoft 365 and Office 365 services.|
|ProofPoint TAP|Proofpoint Targeted Attack Protection™ is the industry's first comprehensive solution for combatting targeted threats using a full lifecycle approach, monitoring suspicious messages containing malicious URLs or malicious attachments, and observing user clicks as they attempt to reach out.|
|TemplateEngine|Template Engine integration provides the ability to render templates using Jinja2. Jinja2 provide fast and flexible ways to create rich templates. These templates can be used in entity insights, emails, ticketing systems, or any action that can take in a text string.Jinja2 documentation can be found at https://jinja.palletsprojects.com/en/2.11.x/|
|Tools|A set of utility actions for data manipulation and common platform tasks to power up playbook capabilities.|


## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|29AWS Cloud Trail - Insights Connector|Pull insights from AWS Cloud Trail.|False|
|30AWS Cloud Trail - Insights Connector|Pull insights from AWS Cloud Trail.|False|
|37AWS Cloud Trail - Insights Connector|Pull insights from AWS Cloud Trail.|False|
|49AWS Cloud Trail - Insights Connector|Pull insights from AWS Cloud Trail.|False|
|28AWS GuardDuty - Findings Connector|Pull findings from AWS GuardDuty. Note: Whitelist works with Finding types, for example, UnauthorizedAccess:EC2/RDPBruteForce.|False|
|38AWS GuardDuty - Findings Connector|Pull findings from AWS GuardDuty. Note: Whitelist works with Finding types, for example, UnauthorizedAccess:EC2/RDPBruteForce.|False|
|52AWS GuardDuty - Findings Connector|Pull findings from AWS GuardDuty. Note: Whitelist works with Finding types, for example, UnauthorizedAccess:EC2/RDPBruteForce.|False|
|53AWS GuardDuty - Findings Connector|Pull findings from AWS GuardDuty. Note: Whitelist works with Finding types, for example, UnauthorizedAccess:EC2/RDPBruteForce.|False|
|27AWS IAM Access Analyzer - Findings Connector|Pull findings from AWS IAM Access Analyzer. Note: Whitelist works on resource types.Example: AWS::S3::Bucket.|False|
|31AWS IAM Access Analyzer - Findings Connector|Pull findings from AWS IAM Access Analyzer. Note: Whitelist works on resource types.Example: AWS::S3::Bucket.|False|
|39AWS IAM Access Analyzer - Findings Connector|Pull findings from AWS IAM Access Analyzer. Note: Whitelist works on resource types.Example: AWS::S3::Bucket.|False|
|40AWS Security Hub - Findings Connector|Pull findings from AWS Security Hub.|False|
|25AirTable Connector|The Connector ingests records from a given table in Airtable|False|
|28AirTable Connector|The Connector ingests records from a given table in Airtable|False|
|32AirTable Connector|The Connector ingests records from a given table in Airtable|False|
|26AlienVault USM Anywhere Connector|AlienVault USM Anywhere Connector|True|
|27AlienVault USM Anywhere Connector|AlienVault USM Anywhere Connector|True|
|33AlienVault USM Anywhere Connector|AlienVault USM Anywhere Connector|True|
|16Amazon Macie - Findings Connector|Pull findings from Amazon Macie. Note: Whitelist works with Finding types, for example, SensitiveData:S3Object/Personal.|False|
|34Amazon Macie - Findings Connector|Pull findings from Amazon Macie. Note: Whitelist works with Finding types, for example, SensitiveData:S3Object/Personal.|False|
|1ArcSight - Security Events Connector|Pull correlations from ArcSight. Note: dynamic list works with "name" parameter. Please refer to the doc portal for the configuration setup. This connector is suitable for Saas deployment of Chronicle SOAR and is the recommended one for production use.|True|
|35ArcSight - Security Events Connector|Pull correlations from ArcSight. Note: dynamic list works with "name" parameter. Please refer to the doc portal for the configuration setup. This connector is suitable for Saas deployment of Chronicle SOAR and is the recommended one for production use.|True|
|36Arcsight ESM Connector|Arcsight ESM Connector|True|
|50ArcSight - Security Events Connector|Pull correlations from ArcSight. Note: dynamic list works with "name" parameter. Please refer to the doc portal for the configuration setup. This connector is suitable for Saas deployment of Chronicle SOAR and is the recommended one for production use.|True|
|51Arcsight ESM Connector|Arcsight ESM Connector|True|
|58ArcSight - Security Events Connector|Pull correlations from ArcSight. Note: dynamic list works with "name" parameter. Please refer to the doc portal for the configuration setup. This connector is suitable for Saas deployment of Chronicle SOAR and is the recommended one for production use.|True|
|5Arcsight ESM Connector|Arcsight ESM Connector|True|
|9ArcSight - Security Events Connector|Pull correlations from ArcSight. Note: dynamic list works with "name" parameter. Please refer to the doc portal for the configuration setup. This connector is suitable for Saas deployment of Chronicle SOAR and is the recommended one for production use.|True|
|41Azure Security Center - Security Alerts Connector|Pull security alerts from Azure Security Center. Note: whitelist works with alertType field.|False|
|45Azure Security Center - Security Alerts Connector|Pull security alerts from Azure Security Center. Note: whitelist works with alertType field.|False|
|48VMware Carbon Black Cloud Alerts and Events Tracking Connector|Fetch Carbon Black Cloud Alerts and Events as Events are added to Carbon Black Cloud Alerts. Connector can create multiple Siemplify alerts for single Carbon Black Cloud Alert, if Cloud Alert was updated with new events after initial ingestion by Siemplify.|False|
|55VMware Carbon Black Cloud Alerts Connector|Siemplify VMware Carbon Black Cloud Alerts Connector should be used to ingest alerts from Carbon Black Cloud (Platform) instances. Note that this connector is deprecated and not recommended to use. Consider switching to "VMware Carbon Black Cloud Alerts and Events Baseline Connector" or "VMware Carbon Black Cloud Alerts and Events Tracking Connector"|False|
|55VMware Carbon Black Cloud Alerts and Events Tracking Connector|Fetch Carbon Black Cloud Alerts and Events as Events are added to Carbon Black Cloud Alerts. Connector can create multiple Siemplify alerts for single Carbon Black Cloud Alert, if Cloud Alert was updated with new events after initial ingestion by Siemplify.|False|
|56VMware Carbon Black Cloud Alerts and Events Tracking Connector|Fetch Carbon Black Cloud Alerts and Events as Events are added to Carbon Black Cloud Alerts. Connector can create multiple Siemplify alerts for single Carbon Black Cloud Alert, if Cloud Alert was updated with new events after initial ingestion by Siemplify.|False|
|57VMware Carbon Black Cloud Alerts and Events Tracking Connector|Fetch Carbon Black Cloud Alerts and Events as Events are added to Carbon Black Cloud Alerts. Connector can create multiple Siemplify alerts for single Carbon Black Cloud Alert, if Cloud Alert was updated with new events after initial ingestion by Siemplify.|False|
|59VMware Carbon Black Cloud Alerts and Events Baseline Connector|Fetch Carbon Black Cloud Alerts and Events that reached specific baseline (were classified by default as Threat in Carbon Black Cloud)|False|
|60VMware Carbon Black Cloud Alerts and Events Tracking Connector|Fetch Carbon Black Cloud Alerts and Events as Events are added to Carbon Black Cloud Alerts. Connector can create multiple Siemplify alerts for single Carbon Black Cloud Alert, if Cloud Alert was updated with new events after initial ingestion by Siemplify.|False|
|61VMware Carbon Black Cloud Alerts Connector|Siemplify VMware Carbon Black Cloud Alerts Connector should be used to ingest alerts from Carbon Black Cloud (Platform) instances. Note that this connector is deprecated and not recommended to use. Consider switching to "VMware Carbon Black Cloud Alerts and Events Baseline Connector" or "VMware Carbon Black Cloud Alerts and Events Tracking Connector"|False|
|62VMware Carbon Black Cloud Alerts Connector|Siemplify VMware Carbon Black Cloud Alerts Connector should be used to ingest alerts from Carbon Black Cloud (Platform) instances. Note that this connector is deprecated and not recommended to use. Consider switching to "VMware Carbon Black Cloud Alerts and Events Baseline Connector" or "VMware Carbon Black Cloud Alerts and Events Tracking Connector"|False|
|10Crowdstrike Falcon Streaming Events Connector|Crowdstrike Falcon Streaming Events Connector|True|
|11Crowdstrike - Incidents Connector|Deprecated. Pull incident and related behaviors from Crowdstrike. Dynamic List works with the “incident_type” parameter.|True|
|12Crowdstrike Falcon Streaming Events Connector|Crowdstrike Falcon Streaming Events Connector|True|
|2Crowdstrike - Alerts Connector|Pull alerts from Crowdstrike. Dynamic List works with the "display_name" parameter. Note: To fetch identity protection detections use "Identity Protection Detections Connector".|True|
|43Crowdstrike - Alerts Connector|Pull alerts from Crowdstrike. Dynamic List works with the "display_name" parameter. Note: To fetch identity protection detections use "Identity Protection Detections Connector".|True|
|44Crowdstrike - Detections Connector|Deprecated. Pull detections from Crowdstrike. Whitelist works with filters that are supported by the API of Crowdstrike. For the details, please refer to the documentation portal.|True|
|47Crowdstrike - Incidents Connector|Deprecated. Pull incident and related behaviors from Crowdstrike. Dynamic List works with the “incident_type” parameter.|True|
|54Crowdstrike - Detections Connector|Deprecated. Pull detections from Crowdstrike. Whitelist works with filters that are supported by the API of Crowdstrike. For the details, please refer to the documentation portal.|True|
|6Crowdstrike - Detections Connector|Deprecated. Pull detections from Crowdstrike. Whitelist works with filters that are supported by the API of Crowdstrike. For the details, please refer to the documentation portal.|True|
|7Crowdstrike - Detections Connector|Deprecated. Pull detections from Crowdstrike. Whitelist works with filters that are supported by the API of Crowdstrike. For the details, please refer to the documentation portal.|True|
|8Crowdstrike - Identity Protection Detections Connector|Pull Identity Protection detections from Crowdstrike. Note: this connector requires an Identity Protection license. Dynamic List works with the “display_name” parameter.|True|
|13Google Chronicle - Chronicle Alerts Connector|Pull information about Rule based alerts from Google Chronicle. Note: dynamic list is used for filtering purposes. For all of the details please visit the documentation portal.|True|
|Google Chronicle - Chronicle Alerts Connector|Pull information about Rule based alerts from Google Chronicle. Note: dynamic list is used for filtering purposes. For all of the details please visit the documentation portal.|True|
|17Microsoft Azure Sentinel Incident Connector|DEPRECATED! Fetches Incidents from Azure Sentinel.|False|
|18Microsoft Azure Sentinel Incident Connector v2|Connector works with Microsoft Azure Sentinel incidents. Connector's Dynamic List can be used to specify the incidents names that needs to be fetched. See connector documentation for more information.|False|
|19Microsoft Azure Sentinel Incident Connector v2|Connector works with Microsoft Azure Sentinel incidents. Connector's Dynamic List can be used to specify the incidents names that needs to be fetched. See connector documentation for more information.|False|
|22Microsoft Sentinel Incident Tracking Connector|Connector works with Microsoft Azure Sentinel incidents and fetches updates to the Sentinel incidents as the new SecOps alerts. Connector's Dynamic List can be used to specify the incidents names that needs to be fetched. It is recommended to configure SecOps Alerts grouping based on SourceGroupIdentifier for this connector. See connector documentation for more information.|False|
|20Microsoft Graph Mail Connector|Connector can be used to fetch emails from the Microsoft Graph Mail service. Connector dynamic list can be used to filter specific values from the email body and subject parts using regexes. By default, regex is used to filter out the urls from the email.|True|
|21Microsoft Graph Mail Delegated Connector|Connector can be used to fetch emails from the Microsoft Graph Mail service. Connector dynamic list can be used to filter specific values from the email body and subject parts using regexes. By default, regex is used to filter out the urls from the email. This connector uses Delegated Authentication in Microsoft 365 and requires interactive login of the user on behalf of which integration should communicate with Microsoft 365. To configure the connector, make sure that the integration configuration is already finished, and the refresh token needed to communicate with Office 365 is generated.|False|
|14Palo Alto Cortex XDR Connector|Pull incidents from Palo Alto XDR. Dynamic List works with the “source” parameter.|False|
|3Palo Alto Cortex XDR Connector|Pull incidents from Palo Alto XDR. Dynamic List works with the “source” parameter.|False|
|23SentinelOne - Alerts Connector|Pull alerts from SentinelOne. Dynamic List works with the “ruleInfo.name” parameter.|False|
|24SentinelOne - Threats Connector|Pull threats from SentinelOne.|False|
|15VirusTotal - Livehunt Notifications Connector|Pull information about Livehunt notifications and related files from VirusTotal. Note: this connector requires a premium API token. Dynamic list works with "rule_name" parameter.|False|
|46VirusTotal - Livehunt Notifications Connector|Pull information about Livehunt notifications and related files from VirusTotal. Note: this connector requires a premium API token. Dynamic list works with "rule_name" parameter.|False|
|4VirusTotal - Livehunt Notifications Connector|Pull information about Livehunt notifications and related files from VirusTotal. Note: this connector requires a premium API token. Dynamic list works with "rule_name" parameter.|False|


## Playbooks
|Name|Description|
|----|-----------|
|Bug palybook||
|Cybersixgill Actionable Alerts|Creates Insights for Each Alert|


## Jobs
|Name|Description|
|----|-----------|
|projects/project/locations/location/instances/instance/integrations/MicrosoftTeams/jobs/34/jobInstances/4|Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.|

