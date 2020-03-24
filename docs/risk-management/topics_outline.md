# Supporting Risk Management and IT Governance

## Risk Management

### Definition
Risk Management is typically defined as the cyclical process of identifying, assessing, analyzing, and responding to risks.

## The Importance of Risk Management

#### Risk Management Cycle
IDENTIFY -> ASSESS -> ANALYZE -> RESPOND

The risk management process is never intended to end.

#### Risk Management is an Active Process
Without risk management, your security practice is passive and subject to ever-changing technology and emerging standards.

### Enterprise Risk Management (ERM)

Risk management functions must be distributed amongst all levels of an organization.

#### Reasons to Implement ERM

- Protecting confidential customer information from unauthorized parties
- Keeping trade secrets private
- Avoiding financial losses wrought by damaged resources
- Avoiding legal liability and compliance breach
- Protecting brand integrity and public goodwill toward image
- Ensuring the continuity of ongoing business operations
- Framing business relationships by establishing trust and limiting liability
- Enabling stakeholder objectives to be achieved

### Risk Exposure
Risk exposure is the organization's susceptibility to loss. When quantified, the likelihood or probability of an incident is considered along with the anticipated impact or loss if it were to actually occur.

### The Pervasive and Persistent Nature of Risks
Elements of risk include threats, attacks, and vulnerabilities that have the potential to cause harm. Risk can nether be eliminated, nor terminated. Ongoing management of risk, including risk mitigation, is vital to an ERM strategy.

### Risk Analysis Methods 

- Qualitative: Involves the use of nomenclature for impact ratings such as severe, moderate, or low. 
- Quantitative: Attempts to calculate the probability of loss associated with any given risk.

##### Quantitative Formulas for Risk Determination

Monetary Loss Value

**AV x EF = SLE** : 
(Asset Value) * (Exposure Factor) = (Single Loss Expectancy)

Annual Loss Value

**SLE x ARO = ALE**
(Single Loss Expectancy) * (Annual Rate of Occurrence) = (Annual Loss Expectancy)

>Note: ALE may be a moving target due to business and technological change.

>Two additional Risk determinations are ROI (Return on Investment) and TCO (Total Cost of Ownership). Obviously if the cost of mitigating a risk exceeds the loss prevented, then mitigation may not be feasible based on monetary metrics only.


- Semi-Quantitative: A Hybrid method involving Qualitative and Quantitative approaches.

### Risk Types

- Legal: Compliance with laws and regulations involves close adherence to industry and jurisdictional laws. Forensics often involves the need for proof of wrongdoing, but also may include the proof of an organization's adherence to regulatory guidelines.
- Financial: The risk of theft, financial loss, and depletion of assets is a typical risk faced by enterprises.
- Physical Assets: Property theft, damage, loss, or misuse is a risk faced by enterprises that requires mitigation.  
- Intellectual Property: Media, software, trade secrets, product designs, and proprietary techniques are all examples of intellectual property that requires ongoing protection from theft or unauthorized disclosure to third-parties.
- Infrastructure: Plants and equipment rely on infrastructure to provide power and ongoing operation. Threats to the underlying infrastructure that enables operations are an area of focus for risk management.
- Operations: Disrupting day-to-day processes and the ability for the organization to function normally is a costly result of security breach. Ensuring business continuity is a key aim of effective risk management.
- Reputation: How existing and prospective customers perceive an entity's ability to protect themself from breach is a key aspect of brand integrity. When banks lose credit card data to outsiders, it impairs their reputation as a secure place to deposit money.
- Health: Harm may come to employees, customers, or others if infrastructure or ongoing operations of assets is impaired due to security threats. Hospitals are not the only institutions that rely heavily on equipment that can either help or harm individuals. The self-driving car is the most poignant example of how machines may affect human welfare.

## Risk Assessment

### Enterprise Security Architecture (ESA)
ESA is a framework used to define the methods used to secure an entity. Baselines and goals are determined to evaluate ongoing thresholds of performance and practice ongoing improvement. ESA involves the quantifying of ongoing internal and external threats and how they might manifest themselves in any given scenario. After identifying and quantifying any given risk, the ESA process involves the determination of potential mitigation.

------------

# IT Governance Frameworks

### ESA Frameworks

- NIST SP 800-37 (National Institute of Standards and Technology Special Publication)
- COBIT (Control Objectives for Information and Related Technology)
- ITAF(tm) (Information Technology Assurance Framework)
- ITIL(r) (Information Technology Infrastructure Library)
- ISO 27001/ISO 27002 (International Standards Organization)
- SABSA(r) (Sherwood Applied Business Security Architecture)
- TOGAF(r) (The Open Group Architecture Framework

### Steps of an ESA Framework

1. Use internal resources and assessment software to establish a baseline of ongoing 'normal' or 'expected' metrics.
2. Review existing security policies.
3. Assess the physical plant and environmental aspects of the enterprise and its infrastructure.
4. Examine the internal network for vulnerabilities and potential attack vectors.
5. Determine access points and connectivity to external resources and assess these third-party endpoints for vulnerabilities and potential breach.
6. Analyze information sharing with third-parties including but not limited to supply chain partners, managed service providers, cloud service providers, and third-party information services.
7. Identify wireless access points and assess security methods.
8. Review policies that govern resource access and information sharing.
9. Inventory host systems and evaluate their configurations and level of hardening as well as any documentation available related to their configuration and use.
10. Identify the underlying infrastructure components that support host systems and connectivity assets.
11. Evaluate human usage and behavior and review policies that establish access guidelines and ongoing use.
12. Examine security training and awareness programs in place.

### Emerging Business Practices

Crowdsourcing

Partnering

Outsourcing

Cloud Computing

Mergers and Acquisitions

Divestiture and Discontinuing Operations

### Security Concerns Regarding Integration

Integrating third-parties into an enterprise security practice involves careful evaluation of the risks associated with the elements of the third-party infrastructure and practice.

Rules and Policies

Legal Requirements and Regulations

Geography

Foreign Laws and Customs - Data Sovereignty

### The challenge of De-perimeterization

Shifting, reducing, or removing established enterprise boundaries is often required to accommodate third-party integrations.

Mobility

Cloud

BYOD

Outsourcing

### System Specific Risk Analysis

- How can an attack be performed?
- Are the attack vectors internal only?
- Will user authentication systems prevent the internal vulnerability?
- What is the data impact in terms of confidentiality, integrity, and availability?
- How is the vulnerability exploited and does the vulnerability exist at present?
- Are there patches or workarounds that would remediate the vulnerability?
- What is the confidence level of the vulnerability detection method? (false positives?)
- What is the potential loss or damage the exposure caused?
- How pervasive are the vulnerability targets?
- What are the business and compliance requirements for the affected systems?
- How likely is the exploit or breach?
- What mitigation is in place now and what is the timeframe and cost of implementing additional protections?
- How can the risk be articulated in business terms that stakeholders can comprehend, as opposed to technical terms meaningful only to IT professionals?

### Risk Determinations
Since risks are pervasive, it is often necessary to prioritize risks even for assessment activities. Things to consider when evaluating risks are:

- Threat actor motivation
- Threat actor demographics
- Annual rate of occurrence (ARO)
- Threat vectors and prior occurrences

## Risk Mitigation

### Classifying Types of Information

When determining whether information warrants protections, it is important to classify the information that might be at risk.

Public

Private

Restricted

Confidential

#### CIA Levels (Confidentiality, Integrity, Availability)

>Note: Also known as AIC and CAI in some domains to avoid confusion with the Central Intelligence Agency of the United States.

Stakeholder Input

### Select Controls Based on CIA Requirements

User Permissions

Load Balancers

Message Authentication Codes

#### Establishing and Aggregate CIA Score

Example: DoS Attack

[Evaluate chart and scoring]

Example: Database Intrusion


### Common Vulnerability Scoring System (CVSS)

### Common Vulnerabilities and Exposures (CVE)

MITRE Corporation

### Extreme Scenario and Worst-Case Scenarios

### Enterprise Resilience

### Risk Response Techniques

- Risk Avoidance
- Risk Transference
- Risk Mitigation
- Risk Acceptance

Identity Exemptions

Use Deterrence

Inherent Risk

Residual Risk

### Continuous Monitoring and Improvement

### Integrating Documentation into Risk Management

[Pyramid]
Procedures
Guidelines
Standards
Policies

#### Policy and Procedure Lifecycle

NIST and CIS (Center for Internet Security) pre-defined procedures or standards documents

#### Best Practices to Incorporate Security Policies and Procedures

Separation of Duties
Job Rotation
Mandatory Vacation
Least Privilege
Incident Response
Forensic Tasks
Employment Onboarding and Termination
Continuous Monitoring
Training and Awareness for Users
Auditing Requirements and Frequency
Information Classification

### Legal Compliance and Advocacy


--------------

# Privacy and Governance

### General Privacy Principles

(PII) Personally Identifiable Information

#### Privacy Requirements

Standards and Laws

**SOX**

Sarbanes Oxley (SOX) is a US law that set new or expanded requirements for all US publicly traded companies' boards, management, and public accounting firms. A number of provisions of the Act also apply to privately held companies, such as the willful destruction of evidence to impede a federal investigation.

**GLBA**

The Gramm-Leach-Bliley Act (GLB Act or GLBA) is also known as the Financial Modernization Act of 1999. It is a United States federal law that requires financial institutions to explain how they share and protect their customers’ private information. To be GLBA compliant, financial institutions must communicate to their customers how they share the customers’ sensitive data, inform customers of their right to opt-out if they prefer that their personal data not be shared with third parties, and apply specific protections to customers’ private data in accordance with a written information security plan created by the institution.

**FISMA**

The Federal Information Security Management Act (FISMA) is United States legislation that defines a comprehensive framework to protect government information, operations, and assets against natural or man-made threats. FISMA was signed into law as part of the Electronic Government Act of 2002.

**COSO**

The Committee of Sponsoring Organizations’ (COSO) mission is to provide thought leadership through the development of comprehensive frameworks and guidance on enterprise risk management, internal control, and fraud deterrence designed to improve organizational performance and governance and to reduce the extent of fraud in organizations

COSO was organized in 1985 to sponsor the National Commission on Fraudulent Financial Reporting, an independent private-sector initiative that studied the causal factors that can lead to fraudulent financial reporting. It also developed recommendations for public companies and their independent auditors, for the SEC and other regulators, and for educational institutions.

**HIPAA**

The Health Insurance Portability and Accountability Act (HIPAA) was enacted by the 104th United States Congress and signed by President Bill Clinton in 1996. It was created primarily to modernize the flow of healthcare information, stipulate how Personally Identifiable Information maintained by the healthcare and healthcare insurance industries should be protected from fraud and theft, and address limitations on healthcare insurance coverage.

**GDPR**

The General Data Protection Regulation (EU) 2016/679 (GDPR) is an EU law on data protection and privacy. The GDPR aims primarily to give control to individuals over their personal data and to simplify the regulatory environment for international business by unifying the regulations. It contains provisions and requirements related to the processing of personal data of individuals.

The PCI Security Standards Council’s mission is to enhance global payment account data security by developing standards and supporting services that drive education, awareness, and effective implementation by stakeholders.


---------

# Privacy and Mobile Devices

### (MDM) Mobile Device Management

- Establish a process for tracking, controlling, and securing an organization's mobile infrastructure.
- Security policies must be enforced on all connected devices, or devices that carry company information and data.

#### Common Features of an MDM Solution

- Pushing out OS, app, and firmware updates
- Enrolling in authentication systems
- Enforcing security policy for mobile applications
- Using GPS to locate devices
- Configuring devices with specific profiles to govern access control
- Enabling push notifications to groups of devices
- Enabling remote access
- Enabling remote lock and wipe capabilities
- Encrypting company data on devices

### Mobile Deployment Models

Corporate Owned
BYOD - Bring your own device
CYOD - Choose your own device
COPE - Corporate owned, personally enabled
VMI - Virtual Mobile Infrastructure

### Mobile Device Storage

Non-Removable
Removable
Cloud
Uncontrolled Storage

### Mobile Device Authentication

Swipe Pattern
Gesture
PIN
Biometrics

### Rooting and Jailbreaking

Enabling root permissions, rooting on Android and Jailbreaking on IOS

### Prevent Unauthorized Apps

Sideloading is installing an app through download rather than through the app store

### Hardware Anti-Tampering

eFuse - Prevents downgrading of a devices firmware

### Mobile TPM

Trusted Platform Module

### Tethering

Sharing wireless Internet with multiple devices

### Mobile Payments

NFC (Near Field Communication)

Tokenization
SMS (Short Message Service)

Mobile MAlware

### Security Concerns

Android Fragmentation
Application Permissions
GEO Tagging
Unauthorized Network Bridging
Baseband Processor
Augmented Reality


### Mobile Containerization

The practice of segmenting corporate-owned resources from personally owned resources.

### Application Wrapping

Adding a layer of control over one or more applications

### OTAP

Over-the-air Provisioning/Programming

### SCEP

Simple Certificate Enrollment Protocol



### Business Continuity Planning

#### BCP Metrics

MTD: Maximum tolerable downtime is the longest period of time that a business outage may occur without causing irrecoverable business failure.

RPO: Recovery point objective is the longest period of time that an organization can tolerate lost data being unrecoverable. The RPO determines how the organization schedules its backups.

RTO: Recovery time objective is the length of time within which normal business operations and activities can be restored following an event.

MTTF: Mean time to failure is the average time that a device or component is expected to be in operation. This assumes that the device cannot be repaired if it fails.

MTTR: Mean time to repair is the average time taken for a device or component to recover from an incident or failure.

MTBF: Mean time between failures is the rating on a device or component that predicts the expected time it is in operation before needing to be repaired or replaced.

### Business Documents that Support Security Initiatives

#### Master Services Agreement (MSA)
This document lays the groundwork for any future business documents that two parties may agree to. The purpose of an MSA is to expedite the agreement process as the relationship between each business partner grows. Organizations may use an MSA to eliminate redundancies that arise when the partner organizations form multiple agreements, like those listed in the rest of the table.

#### Statement of Applicability (SOA)
This document identifies the controls in place in an organization and explains their purpose. As SOAs identify why a particular control is being used, they are often directly influenced by the conclusions reached in a risk assessment. The SOA should reference the policies and procedures that will take advantage of the identified controls. It may be beneficial to not only explain why a certain control was included, but to also explain why certain controls were excluded.

#### Business Impact Analysis (BIA)
This document identifies present organizational risks and determines the impact to ongoing, business-critical operations and processes if such risks actually occur. BIAs contain vulnerability assessments and evaluations to determine risks and their impact. BIAs should include all phases of the business to ensure a strong business continuation strategy.

#### Interoperability Agreement (IA)
This is the general term for any document that outlines a business partnership or collaboration in which all entities exchange some resources while working together.

#### Interconnection Security Agreement (ISA)
This type of agreement is geared toward the information systems of partnered entities to ensure that the use of inter-organizational technology meets a certain security standard for CIA. Because they focus heavily on security, ISAs are often written to be legally binding. ISAs can also support MOUs (see next entry) to increase their security viability.
NIST provides a security guide for developing an interconnection plan, titled Security Guide for Interconnecting Information Technology Systems Special Publication 800-47.

#### Memorandum of Understanding (MOU)
This type of agreement is usually not legally binding and typically does not involve the exchange of money. MOUs are less formal than traditional contracts, but still have a certain degree of significance to all parties involved. They are typically enacted as a way to express a desire for all parties to achieve the same goal in the agreed-upon manner. An MOU document might contain background information on each organization; the history of the relationship between the two organizations and circumstances that led to the partnership; and a general or specific timeline for collaborative business activities. Because they typically have no legal foundation, an MOU is not the most secure agreement for a partnership.

#### Service-Level Agreement (SLA)
This agreement clearly defines what services are to be provided to the client, and what support, if any, will be provided. Services may include everything from hardware and software to human resources. A strong SLA will outline basic service expectations for liability purposes. The document may include timeframes within which failures will be repaired or serviced; guarantees of uptime; or, in the case of a network provider, guarantees of data upload and download rates.

#### Operating Level Agreement (OLA)
This agreement identifies and defines the working relationships between groups or divisions of an organization as they share responsibilities toward fulfilling one or more SLAs with their internal or external customers.

#### Non-Disclosure Agreement (NDA)
This is an agreement between entities stipulating that they will not share confidential information, knowledge, or materials with unauthorized third parties. NDAs also commonly state in which cases, if any, data may be used or processed by the receiving entity. For data acquired through public sources, an NDA is not enforceable.

#### Business Partnership Agreement (BPA)
This agreement defines how a partnership between business entities will be conducted, and what exactly is expected of each entity in terms of services, finances, and security. For security purposes, BPAs should describe exactly what the partners are willing to share with each other, and how any inter-organizational access will be handled.


### Guidelines for Integrating Documentation into Risk Management

Follow these guidelines to integrate documentation into your ERM strategies.

#### Integrate Documentation into ERM

When integrating documentation into your ERM strategies:

- Download free policy templates to make crafting a policy easier.
- Consider hiring a consultant if your organization can't support the internal development of policies.
- Use direct, concise language and dispense with legal jargon in policies.
- Include business leaders in policy development and make sure executive management approves of the policy before it is enforced.
- Support policies with clearly defined processes and procedures.
- Make processes and procedures easy to follow and tailor them toward your audience's technical aptitude.
- Compare and contrast policies, processes, and procedures with those of other organizations.
- Consider policies, processes, and procedures to be living documents; that is, subject to change as businesses and technology evolve.
- Incorporate best practices like job rotation, mandatory vacations, and user training, into your policies based on your specific enterprise requirements.
- Involve HR, legal counsel, management, and other entities in the policy development process to get unique perspectives.
- Ensure that policies have provisions for legal and regulatory compliance.
- Identify any sensitive PII that your organization handles.
- Be up front with your clients as to how their PII will be used and for what purpose it will be used.
- Advise your clients on best practices to maintain privacy.
- Draft a business continuity plan (BCP) to maintain day-to-day operations in the event of an incident.
- Define in the BCP what components are at risk and how they should be preserved.
- Review your BCP and test it on a regular basis.
- Identify the various business documents and agreements that are applicable to your enterprise needs.
- Use an agreement like an SLA in any partnership that requires strong security and legal and financial liability.


### Secure Software Onboarding

Virtually all developer organizations utilize third-party applications and install them from cloud based repositories. In addition to applications, developers within an enterprise utilize third-party vendor provided toolkits, frameworks, and libraries that speed the task of software development. Last but not least is the increased use of third-party open source tooling and libraries that are downloaded from repositories maintained by the open source project maintainer.

In all cases when software in binary or source code form is brought inside a corporate network, or developer sandbox environment, that code is then fused and deployed with internal applications and systems. The following are key parts of an ESA and ERM.

Prohibit internal systems from downloading from un-trusted sources
Utilize certified registries and repositories
Use repos that require authentication or certificates for access
Scan downloaded content for vulnerabilities and malware
Quarantine questionable content
Maintain manifests for deployed applications so 3rd party libraries are evident
Segment potentially vulnerable systems via sandboxing
Utilize containers to isolate applications from their platforms and other applications
Use Cloud and Virtual host hardening to prevent privilege escalation and breakouts



