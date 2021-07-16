# Awesome Secure Coding
- Outlines are based on CertNexus CSC - [Cyber Secure Coder](https://certnexus.com/certification/cyber-secure-coder/)

{Stay tuned, WIP}

##  Identifying the Need for Security in Your Software Projects
### Identify Security Requirements and Expectations
* Security Throughout the Development Process
  * [What are the Microsoft SDL practices?](https://www.microsoft.com/en-us/securityengineering/sdl/practices) - microsoft.com
  * [Microsoft Security Development Lifecycle (SDL)](https://www.microsoft.com/en-us/securityengineering/sdl/) - microsoft.com
  * [Understand the information security lifecycle](https://www.protectivesecurity.govt.nz/information-security/lifecycle/) - protectivesecurity.govt.nz
* Business Requirements
  * All stakeholders should be involved 
* Standards and Compliance Requirements
  * Government Regulations e.g., HIPAA, FISMA, SOX, GLBA, FFIEC, GDPR, etc.
  * Insdustry Standards e.g., COBIT, ITIL, ISO/IEC 27000, GASSP/GAISP, SABSA, NIST, PCI DSS, etc. 
* User Impact
  * [Colonial Hack Shows U.S. Must Diversify Its Oil Reserves](https://www.bloomberg.com/opinion/articles/2021-05-16/colonial-pipeline-hack-shows-u-s-must-diversify-its-oil-reserves) - bloomberg.com
  * Stuxnet
  * Zero-day  
* User Expectations
  * Users expect applications to operate in a secure manner and without any error.
* Platform Requirements
  * [Sample Terms of Use Template](https://www.termsfeed.com/blog/sample-terms-of-use-template/) 
* Consequences of Not Meeting Security Requirements
  * [5 Consequences That Result From Not Meeting Data Security Requirements](https://dzone.com/articles/5-consequences-that-result-from-not-meeting-data-s) - dzone.com
* Guidelines for Identifying Security Requirements and Expectations
  * Identify sources of security requirements
  * Elicit and prioritize security requirements 
  * Meet PCI DSS requirements
* Identifying Security Requirements and Expectations
  * [Examples of ISO 27001 interested parties and your compliance requirements](https://www.itgovernance.co.uk/blog/examples-of-iso-27001-interested-parties) 
### Identify Factors That Undermine Software Security
* Three Ps of Software Security
  * [The 3 Ps of Comprehensive Cybersecurity](https://blogs.cisco.com/customerexperience/the-3-ps-of-comprehensive-security) - cisco.com
  * [The 3 P’s of Cybersecurity](https://cmitsolutions.com/blog/3-ps-cybersecurity-put-basic-fundamentals-work-business/) - cmitsolutions.com
  * [What Is Phishing?](https://www.comptia.org/content/articles/what-is-phishing) - comptia.org
* Software Security Terminology
  * [The Dummies Guide to Cyber Security Terminology](https://www.metacompliance.com/cyber-security-terminology/) - metacompliance.com
* Identifying Factors That Undermine Security 
  * [The Human Factor in IT Security: How Employees are Making Businesses Vulnerable from Within](https://www.kaspersky.com/blog/the-human-factor-in-it-security/) - kaspersky.com

### Find Vulnerabilities in Your Software
* Builders and Breakers
  * [Builders vs Breakers: Bridging the gap Between Software Development and InfoSec](https://securitytrails.com/blog/interview-tanya-janca) - Tanya Janca
* Hacking
  * [Hacking](https://www.malwarebytes.com/hacker) - malwarebytes.com
* Phases of an Attack
  * [The seven phases of a cyber attack](https://www.dnv.com/article/the-seven-phases-of-a-cyber-attack-118270) - dnv.com
* Common Attack Patterns
  * [The 5 Most Common Attack Patterns of 2014](https://www.tripwire.com/state-of-security/featured/the-5-most-common-attack-patterns-of-2014/) 
* Case Study: Protecting Against a Password Attack
  * [Case Studies in Poor Password Management](https://resources.infosecinstitute.com/topic/case-studies-in-poor-password-management/) - infosecinstitute.com (Dimitar Kostadinov)
* Guidelines for Identifying Software Security Vulnerabilities
* Identifying Vulnerabilities in an Application
* Cracking a Password Hash
  * [crackstation](https://crackstation.net/) 
  * [password-cracking-with-hashcat](https://cryptokait.com/2020/02/24/password-cracking-with-hashcat/)
  * [How to crack passwords with Hashcat](https://cyberrunner.medium.com/how-to-crack-passwords-with-hashcat-a9fb2aa1a813)
* Fixing a Password Hash Vulnerability
### Gather Intelligence on Vulnerabilities and Exploits
* Vulnerability Intelligence
  * [Enabling Defenders With Vulnerability Intelligence](https://www.fireeye.com/blog/threat-research/2020/04/enabling-defenders-with-vulnerability-intelligence.html) - fireeye.com
* Exploits
* Guidelines for Researching Vulnerabilities and Exploits
* Identifying Sources for Vulnerability Intelligence 


-----

## Handling Vulnerabilities
### Handle Vulnerabilities Due to Software Defects and Misconfiguration
* Software Defects
* Causes of Software Defects
* Guidelines for Preventing Security Defects
* Preventing Security Defects
* Problems in Third*Party Code
* Problems in Standard Libraries
* Dependencies
* Encryption Validation
* Security of Host Systems and Service Providers
* Guidelines for Using Third*Party Code and Services
* Host Platform Configuration
* Hypervisor Vulnerabilities
  * [What is a hypervisor?](https://www.vmware.com/topics/glossary/content/hypervisor) - vmware.com
  * [The vulnerabilities of hypervisors](http://www.techadvisory.org/2019/04/the-vulnerabilities-of-hypervisors/) - techadvisory.org
* Guidelines for Managing Vulnerabilities in External Hosts and Services
* Identifying Vulnerabilities in a Software Project
* Examining the Project Files
* Error Messaging
* Error Handling
  * [Improper Error Handling](https://owasp.org/www-community/Improper_Error_Handling) - owasp.org
* Fail*Safe
* Failure Recovery
* Guidelines for Secure Error Handling
* Identifying Software Defects and Misconfiguration

### Handle Vulnerabilities Due to Human Factors
* The Human Element in Software Security
* Vulnerabilities Attributed to the Human Element
* Social Engineering Attacks
  * [5 Social Engineering Attacks to Watch Out For](https://www.tripwire.com/state-of-security/security-awareness/5-social-engineering-attacks-to-watch-out-for/) - David Bisson
* User Input
* Input Validation
  * [Input Validation Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Input_Validation_Cheat_Sheet.html) - owasp.org
  * Blacklist vs Whitelist
* Security Policy Enforcement
* Guidelines for Managing People Risks
* Managing People Risks

### Handle Vulnerabilities Due to Process Shortcomings
* Development Process Approaches
* Building Security In
* The CIA Triad
  * [CIA Triad](https://resources.infosecinstitute.com/topic/cia-triad/) 
* Requirements Phase
* Design Phase
* Development Phase
* Testing Phase
* Security Testing Tools
* Deployment Phase
* Maintenance Phase
* Development Process Security
* Guidelines for Software Development Processes
* Managing Software Development Process Risks 
-----
## Designing for Security
### Apply General Principles for Secure Design
* Security in the Design Phase
* Security by Obscurity vs. Security by Design
* OWASP Security Design Principles
  * [Secure Design Principles](https://github.com/OWASP/DevGuide/blob/master/02-Design/01-Principles%20of%20Security%20Engineering.md) - OWASP
* Minimize Attack Surface Area
* Establish Secure Defaults
* Least Privilege
* Least Common Mechanism
* Defense in Depth
* Fail Securely
* Don't Trust Services
* Separation of Duties
* Security by Obscurity
* Keep Security Simple
  * [Top 10 Secure Computing Tips](https://security.berkeley.edu/resources/best-practices-how-to-articles/top-10-secure-computing-tips) 
* Fix Security Issues Correctly
* Software Design Patterns
* Security Patterns
* Modular Design
* Benefits of Modular Design
* The Balance Between Defense in Depth and Simplicity
* Guidelines for Avoiding Common Design Mistakes
* Avoiding Common Security Design Flaws


### Design Software to Counter Specific Threats
* [The Risk Equation](http://www.icharter.org/articles/risk_equation.html)
* [Threat Modeling](https://owasp.org/www-community/Application_Threat_Modeling)
* Benefits of Threat Modeling
* Step 1: Define General Security Objectives and Scope
* Tooling and Documentation
* Assets
* Step 2: Decompose the Software
* Trust Levels
* Entry and Exit Points
* External Dependencies
* Data Flow Diagrams
* Diagramming Symbols
* Diagramming the Catalog Application
* Step 3: Identify and Rank Threats
* STRIDE
* PASTA
* Misuse Cases
* Security Zones
* Strategies for Ranking Threats
* DREAD
  * [Qualitative Risk Analysis with the DREAD Model](https://resources.infosecinstitute.com/topic/qualitative-risk-analysis-dread-model/) - infosecinstitute.com
* Risk Response Strategies
* Severity
* Risks Outside Your Control
* Guidelines for Identifying and Ranking Threats
* Step 4: Counter Each Threat
* Countermeasures
* Identifying Threats and Countermeasures
-----
## Developing Secure Code
### Follow Best Practices for Secure Coding
* Development Documentation and Deliverables
* Application and Data Integrity
* Common General Programming Errors
* Insecure Deserialization
* Guidelines for Secure Coding
* Researching Your Secure Coding Checklist
* Buffer Overrun Defects
* Buffer Overflows
* Guidelines to Prevent Buffer Overflow Defects
* Buffer Overreads
* Guidelines to Prevent Buffer Overread Defects
* Integer Overflows
* Guidelines to Prevent Integer Overflow Defects
* Uncontrolled Format Strings
* Insecure Output Encoding
* XXE Attacks
* Guidelines to Prevent Uncontrolled Format String Defects
* Race Condition
* Impact of Race Conditions on Threading/Multiprocessing
* Guidelines to Prevent Race Condition Defects
* Performing a Memory*Based Attack

### Prevent Platform Vulnerabilities
* OWASP Top Ten Platform Vulnerabilities
  * [OWASP Top 10](https://github.com/OWASP/Top10) - OWASP GitHub 
  * [OWASP Top 10 - Detectify](https://blog.detectify.com/?s=OWASP+TOP+10) - detectify.com
* Authentication
* Authorization
* Broken Authentication
* Guidelines to Prevent Web Vulnerability Defects
* Guidelines to Prevent Mobile App Vulnerability Defects
* Guidelines to Prevent Internet of Things Vulnerability Defects
* Desktop Application Vulnerabilities
* DLL Injection
* Shellcode Injection
* Debugger Security
* Differences Among Desktop Platforms
* Managed vs. Unmanaged
* Desktop Application Attack Vectors
* Development Tool and Project Configuration
* Guidelines to Prevent Desktop Application Vulnerabilities
* Finding Common Web Vulnerabilities 
Topic C: Prevent Privacy Vulnerabilities
* Privacy Vulnerability Defects
* Privacy by Design
* Data Anonymization
* Guidelines to Prevent Privacy Vulnerability Defects
* Handling Privacy Defects
-----
## Implementing Common Protections
### Limit Access Using Login and User Roles
* Web Sessions
* Secure Session Management
* Methods for Passing Session IDs
* Access Control
* Guidelines for Secure Session Management
* User Provisioning
* Password Recovery
* Account Lockouts
* Guidelines for Secure Password Management
* Handling Authentication and Authorization Defects
### Protect Data in Transit and At Rest
* Encryption
* Uses for Encryption
* Cryptographic Lifecycle
* Symmetric Encryption
* Asymmetric Encryption
* Hashing
* Digital Signatures
* Digital Signature Non*repudiation
* Digital Certificates
* PKI
* PKI Components
* The PKI Process
* Key Management
* Key Management Factors
* Certificate Revocation
* Guidelines for Protecting Data in Transit and at Rest
* Protecting Data in Transit and at Rest
### Implement Error Handling and Logging
* Error Handling
* Uses for Error Handling
* Error Messaging
* Logging
* Guidelines for Implementing Error Handling and Logging
* Reviewing Error Handling
* Improving Error Handling 
### Protect Sensitive Data and Functions
* Sensitive Data
* Output Restrictions
* Function Level Access Control
  * [Missing Function Level Access Control](https://blog.detectify.com/2016/07/13/owasp-top-10-missing-function-level-access-control-7/) - detectify.com
  * [What is Missing Function Level Access Control? :tv:](https://www.youtube.com/watch?v=oVV-lSB7ddc) - Detectify
* Case Study: Cross*Site Scripting Defect
* Guidelines for Protecting Sensitive Data and Functions
* Protecting Sensitive Data and Functions
* Staging a Persisted XSS Attack on an Administrator Function
### Protect Database Access
* Case Study: SQL Injection Defect
* Query Parameterization
* Database Connection Credential Protection
* Guidelines for Protecting Database Access
* Protecting Database Access
-----
## Testing Software Security
### Perform Security Testing
* The Role of Testing
* Phases of Software Testing
* Development Testing
* Unit Testing
* Integration Testing
* Documentation and Deliverables for Testing
* Manual Inspection and Code Review
* Code Review Strategies
* Guidelines for Security Testing
* Performing Manual Inspection and Review
### Analyze Code to find Security Problems
* Static Code Analysis
* Strategies for Using Static Analysis
* Dynamic Code Analysis
* Guidelines for Code Analysis
* Performing Code Analysis
### Use Automated Testing Tools to Find Security Problems
* Automated Testing
* Unit Testing
* Guidelines for Using Automated Testing Tools
* Using a Test Suite to Automate Unit Testing
-----
## Maintaining Security in Deployed Software
### Monitor and Log Applications to Support Security
* Emerging Security Problems
* Situational Awareness
* Security Monitoring
* Intrusion Detection and Prevention
* Monitor Placement
* Logging
* Guidelines for Monitoring and Logging a Deployed Application
* Monitoring and Logging a Deployed Application 
### Maintain Security after Deployment
* Maintenance
* Patches and Updates
* Uninstallation and Deprovisioning
* Guidelines for Maintaining Security of Deployed Software
* Maintaining Security After Deployment 

-----

## YouTube :tv:
* [How to Analyze Code for Vulnerabilities](https://www.youtube.com/watch?v=A8CNysN-lOM) - OWASP DevSlop

## Articles
* [57 Cybersecurity Terms You Should Know in 2021](https://securityscorecard.com/blog/57-cybersecurity-terms-you-should-know-in-2021) - securityscorecard.com

-----
## References
* [ISO/IEC 27001](https://www.iso.org/isoiec-27001-information-security.html) - iso.org
* [NIST](https://www.nist.gov/cybersecurity) - nist.gov
* [OWASP](https://owasp.org/) - owasp.org
* [PCI Security Standards](https://www.pcisecuritystandards.org/) - pcisecuritystandards.org
* [SANS](https://www.sans.org/) - sans.org
