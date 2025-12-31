### Identity Governance and Access Management Policy

#### Purpose

This policy establishes how identities and access are governed across the organization. Its purpose is to ensure that access to systems, applications, and data supports business productivity while preserving user trust, privacy, and accountability.

The company operates a B2C personal analytics platform that processes sensitive user provided data and derived insights. Misuse, overexposure, or unmanaged access presents direct risk to user trust and brand credibility. This policy defines the governance foundations that guide all identity and access decisions as the organization scales.

#### Scope

This policy applies to:

* All human identities, including employees, contractors, and partners  
* All non human identities, including applications, service accounts, and APIs  
* All systems, environments, and data owned or operated by the company

This policy applies across production and non production environments, with stricter controls applied to sensitive and privileged access.

#### Identity ownership and accountability

* Business leadership owns access intent for their respective functions  
* Managers are accountable for approving and reviewing access for identities under their supervision  
* Security owns policy maintenance and oversight  
* System owners are responsible for defining access boundaries and supporting reviews

Access without a clear owner is not permitted.

#### Joiner, Mover, Leaver and identity lifecycle

Access is governed across the full identity lifecycle.

* **Joiners** receive baseline access aligned to their role and function  
* **Movers** have access reviewed and adjusted when responsibilities change  
* **Leavers** have all access removed in a timely manner upon departure

Lifecycle events must trigger access changes automatically or through defined review workflows. Standing access that no longer reflects job function is not acceptable.

#### Role based access control

Access is assigned primarily through business roles.

* Roles reflect job function, not individual preference  
* Each role has a defined owner and documented access scope  
* Roles are reviewed periodically to ensure relevance and least privilege

Direct, ad hoc access outside of roles is discouraged and subject to review. See *Exceptions and Temporary Access.*

#### Access request and approval

* Access requests must state a clear business purpose  
* Approval is required from the appropriate access owner or manager  
* Access is granted for a defined scope and duration

Default access is time aware. Access does not persist indefinitely unless explicitly justified.

#### Segregation of duties

Access combinations that create risk must be avoided.

Examples include:

* Development and production administration  
* Data access and approval authority  
* Monitoring and system modification

Where segregation cannot be fully enforced, compensating controls and documented approval are required.

#### Exceptions and temporary access

Exceptions are allowed only when business need outweighs risk.

* Exceptions require documented justification and approval  
* All exceptions must be time bound  
* Exceptions are reviewed more frequently than standard access

Untracked or permanent exceptions are not permitted.

#### Access reviews

Access must be reviewed to ensure ongoing appropriateness. This is core to identity governance.

* Sensitive and privileged access is reviewed more frequently  
* Managers and system owners participate in reviews  
* Excess or unused access is removed promptly

#### Privileged access governance

Administrative and privileged access is tightly controlled.

* Privileged access is granted only when required for specific duties  
* Where possible, privileged access is temporary and just in time  
* Privileged access is reviewed regularly and logged

Service and application identities with elevated privileges are governed to the same standard as human administrators.

#### Enforcement and review

Violations of this policy may result in access removal or corrective action.  
This policy is reviewed periodically to ensure it continues to support business growth, security, and user trust.
