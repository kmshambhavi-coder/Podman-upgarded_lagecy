# Widget Playbook
Auto-generated playbook invoking Area1 > GetRecentIndicators



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



### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|Nested_Block_b45d|Invokes the shared enhancement block||Block|
|GetRecentIndicators_1|This step invokes GetRecentIndicators|Area1|GetRecentIndicators|
|Siemplify_Case Tag_1|Add given tag to the case the current alert is grouped to|Siemplify|Case Tag|
|CaseTag_21ff|Appends a dynamic tag to the case.|Siemplify|CaseTag|

