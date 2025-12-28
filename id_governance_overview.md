## Identity Governance and Administration
### The Importance of IGA
Identity Governance and Administration (IGA) is our first priority for the identity perimeter because it ensures that the needs of the business are met. IGA steers the IAM approach by determining who can access which organizational resource, relating the "why" to business processes that require data and drives productivity and value - all the while maintaining confidentiality, integrity, and accountability. The importance of governance goes beyond operational and technical risk as IGA supports the organization in managing compliance as well.

As much as I'd like to dive straight into using tools, setting up Identity Governance helps us steer IAM, which means we won't be going in blind and aimless. Identity Governance and sets the tone for the identity perimater across the organization, especially in strengthening security culture as well. We'll be touching on MFA and I bet you (the reader) know at least 3 people in your life who aren't a fan of extra login challenges.

If an anecdote is all you need to take away today, consider this: Security Governance (by extension, IGA) is about navigating the business through risk. It's a tightrope, and you need to get to the other side - that's some sort of mission or strategic objective for your business. What keeps you balanced in the air and not toppling over is a long metal pole that anchors your centre of gravity, but on the ends of these poles are two sandbags - one is labelled 'What the business needs to be productive' and the other is 'What the business needs to be secure'.

#### Considerations for business
Anybody on the business side of cyber must consider the organization's unique risk environment. If you look on an industry basis, certain industries are predisposed to risks, which is a whole universe itself that I think simmers down to the sensitivity of data being worked with. Unauthorized exposure carries implications on contractual and regulatory compliance, trust, accountability, and privacy.

That said, industry should be treated as context, not a constraint. The core of IGA does not change just because a business is in health, finance, SaaS, or retail. What changes is the weight placed on certain decisions, or how things are prioritized. A company working with regulated personal data will naturally prioritize tighter approval workflows, clearer ownership, and stronger review cycles to strengthen accountability. A product-driven startup may tolerate more access flexibility early on, but still needs to know where its intellectual property lives and who can touch it.

From an IGA perspective, the first task is to understand how the business actually functions. This means identifying the types of users that exist:
- Internal (employees) vs External users (contractors, vendors, collaborators)
- Temporality: Interns and Guests vs. Full-time employees
- Human vs Workload (applications, services)
Each of these identities have a reason for being, and they each imply a set of access needs which introduces risk if overprovisioned, undergoverned, or left unchecked over time.

In parallel, the organization’s resources must be framed in business terms. Applications, data stores, admin consoles, and APIs are more than technical assets, as they are in some way tied to driving business value, continuity, or obligation. Some resources are low risk if misused. Others, such as financial systems, customer databases, or identity admin planes, carry disproportionate impact if accessed improperly. IGA forces the business to explicitly acknowledge these differences instead of treating all access as equal.

Identity Governance kicks in by asking questions before any technical control is applied. Who owns this resource. Who is accountable for approving access. How long should access last. What event should trigger a review. What happens when a role changes, or when someone leaves. These questions are not technical hurdles, they are decision points that reflect how mature the organization is in managing risk.

When these considerations are addressed early, IAM stops being a collection of settings and starts becoming an execution layer. IAM enforces what the business has already decided. Without IGA, IAM decisions are reactive, inconsistent, and often driven by convenience. With IGA, IAM becomes intentional. Access aligns with purpose, duration aligns with need, and identity becomes something the business actively governs rather than passively inherits.

This is ultimately why IGA belongs on the business side of cyber. It is not about slowing people down or adding friction for its own sake. It is about ensuring that access reflects reality, risk is acknowledged, and productivity is protected without eroding trust or accountability.

## Context
### Scenario: _Healthtech startup with regulated data_
CarePoint builds software for clinics to manage patient appointments and health records. It processes regulated personal and health data and operates under strict privacy expectations. The company is still small, but the impact of misuse is high.
### Key Considerations
- Clear distinction between clinical users and internal staff;
- Strong ownership and approval for access to sensitive data;
- Least privilege access enforced across roles;
- Short review cycles for privileged access;
- Immediate deprovisioning on role change or termination

## Information Governance Policies
| Policy | Definition |
|--------|------------|
| Access Request | * |
| Access Approval | * |
| Role Management | * |
| Segregation of Duties | * |
| Access Review | * |
| Lifecycle | * |
| Privileged Access Governance | * |
| Access Expiration Policy | |
| Policy Violation and Exception | * |
