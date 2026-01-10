# Identity and Access Management with Microsoft Entra
_The rising frontier of insider threats and privilege escalation-based attacks are amplified by the lack of effective identity lifecycle management and authentication/authorization measures. At the same time, employees, collaboators, and workloads (APIs, apps, services) must be able to access the right resources at the right time to do their jobs._

## Overview
This project documents the design and implementation of Identity Governance and Access Management for a small to mid-sized B2C SaaS organization providing personal analytics to end users. IAM needs to be grounded in facilitating the processes and people underlying the business, just as much as it needs to be grounded in risk. 

This project defines roles, identity populations, and governance rules before implementing IAM controls using Microsoft Entra. The focus is on establishing repeatable, mature identity processes such as joiner-mover-leaver lifecycle management, role-based access, privileged access governance, and access reviews. The outcome demonstrates how identity governance decisions are operationalized in Entra to support growth, protect user trust, and reduce identity-related risk.

Every deliverable is centred on a fictional business scenario that involves sensitive data and various roles.

## Scope
| In | Out |
| -- | -- |
|Organizational/governance artifacts; Documented processes; Entra implementation artifacts|Full Entra IaC; Complex multitenant or hybrid identity scenarios; Deep regulatory compliance mapping|

## Deliverables
### <a href="https://github.com/a-khang/microsoft_iam/blob/main/part1.md/">1. Organizational and governance artifacts</a>
- Organizational context and business scenario description  
- Identity populations and role definitions  
- Risk-based access tier model  
- IAM and IGA policy document covering lifecycle, RBAC, access reviews, and privileged access  

### <a href="https://github.com/a-khang/microsoft_iam/blob/main/part2.md/">2. Process documentation</a>
- Joiner, mover, leaver lifecycle flows  
- Access request and approval logic  
- Privileged access request and activation flow  
- Exception handling and temporary access process  
- Access review cadence and remediation steps  

### <a href="https://github.com/a-khang/microsoft_iam/blob/main/part3.md/">3. Entra implementation artifacts</a>
- Entra tenant structure overview  
- Group-based RBAC model aligned to risk tiers  
- Application access assignments using groups  
- Privileged Identity Management configuration  
- Access Review configuration by role and risk level  
- Non-human identity governance approach.

### <a href="https://github.com/a-khang/microsoft_iam/blob/main/part4.md/">4. Evidence of repeatability</a> 
- Examples of group-based access enforcement  
- Sample access review outputs and decisions  
- Before and after access states for lifecycle events  
- Clear mapping from governance rule to Entra control 

<img width="2073" height="1896" alt="IAM_ENTRA_WBS_300dpi" src="https://github.com/user-attachments/assets/82e70806-46ee-44f8-bd3e-bf392fca11f8" />
