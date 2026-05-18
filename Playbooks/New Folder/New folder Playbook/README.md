# New folder Playbook
Test description



**Enabled:** True

**Version:** 1

**Type:** Playbook

**Priority:** 2

**Playbook Simulator:** False


### Playbook Trigger
**Trigger Type:** All

**Conditions Operator:** And

##### Conditions
|Key|Operator|Value|
|---|--------|-----|
||Equals||


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|Siemplify_Add Entity Insight_1|Add an insight configurable message to each targeted entity|Siemplify|Add Entity Insight|
|GitSync_Ping_1|Test connectivity to GitSync|GitSync|Ping|
|Siemplify_Case Tag_1|Add given tag to the case the current alert is grouped to|Siemplify|Case Tag|
|Siemplify_Add to Custom List_1|Add an Entity Identifier to a categorized Custom List, in order to perform future comparisons in other actions.|Siemplify|Add to Custom List|
|Siemplify_Add Tags To Similar Cases_1|Add tags to similar cases and return their Ids|Siemplify|Add Tags To Similar Cases|
|Siemplify_Add General Insight_1|Add a general insight configurable message to the case|Siemplify|Add General Insight|

### Involved Blocks
|Name|Description|
|----|-----------|
|first folder block|update An embedded workflow that can receive inputs and return an output.|
