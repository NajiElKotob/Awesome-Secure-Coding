# Awesome Secure Coding
~ Outlines are based on CertNexus CSC ([Cyber Secure Coder](https://certnexus.com/certification/cyber-secure-coder/))
`
Secure coding is a set of practices that applies security considerations 
to how software will be coded and encrypted to best defend against 
cyber attack or vulnerabilities. [NTT Security AppSec Solutions]
`
{Awesome Works in Progress}

-----
1. [Identifying the Need for Security in Your Software Projects](#identifying-the-need-for-security-in-your-software-projects)
1. [Handling Vulnerabilities](#handling-vulnerabilities)
1. [Designing for Security](#designing-for-security)
1. [Developing Secure Code](#developing-secure-code)
1. [Implementing Common Protections](#implementing-common-protections)
1. [Testing Software Security](#testing-software-security)
1. [Maintaining Security in Deployed Software](#maintaining-security-in-deployed-software)


-----
* [What is secure coding?](https://www.whitehatsec.com/glossary/content/secure-coding)


##  Identifying the Need for Security in Your Software Projects
### Identify Security Requirements and Expectations
* Security Throughout the Development Process
  * [What are the Microsoft SDL practices?](https://www.microsoft.com/en-us/securityengineering/sdl/practices) - microsoft.com
  * [Microsoft Security Development Lifecycle (SDL)](https://www.microsoft.com/en-us/securityengineering/sdl/) - microsoft.com
  * [Understand the information security lifecycle](https://www.protectivesecurity.govt.nz/information-security/lifecycle/) - protectivesecurity.govt.nz
* Business Requirements
  * All stakeholders should be involved 
  * [Engaging Stakeholders for Project Success](https://www.pmi.org/learning/library/engaging-stakeholders-project-success-11199) - pmi.org
* Standards and Compliance Requirements
  * Government Regulations e.g. 
    - HIPAA - Health Insurance Portability and Accountability Act
    - FISMA
    - SOX
    - GLBA
    - FFIEC
    - GDPR
    - CCPA
  * Insdustry Standards e.g.
    - COBIT
    - ITIL
    - [ISO/IEC 27000](https://www.iso.org/news/ref2266.html) - Information Security Management System Standards
    - GASSP/GAISP
    - [SABSA](https://sabsa.org/) - Sherwood Applied Business Security Architecture
    - [NIST](https://www.nist.gov/) - National Institute of Standards and Technology
    - PCI DSS 
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
  * [Ethical hacker](https://searchsecurity.techtarget.com/definition/ethical-hacker) :star: - techtarget.com
* Phases of an Attack
  * [The seven phases of a cyber attack](https://www.dnv.com/article/the-seven-phases-of-a-cyber-attack-118270) - dnv.com
* Common Attack Patterns
  * [The 5 Most Common Attack Patterns of 2014](https://www.tripwire.com/state-of-security/featured/the-5-most-common-attack-patterns-of-2014/) 
  * [Flood Attacks](https://www.watchguard.com/help/docs/help-center/en-US/Content/en-US/Fireware/intrusionprevention/flood_attacks_c.html) also known as Denial of Service (DoS) attacks. In a flood attack, attackers send a very high volume of traffic to a system so that it cannot examine and allow permitted network traffic.
  * Reconnaissance
  * Memory Manipulation
  * Reverse Engineering
  * Functionality misuse
  * [Sustained Client Engagement](https://capec.mitre.org/data/definitions/227.html)
  * [Action Spoofing](https://capec.mitre.org/data/definitions/173.html)
* Case Study: Protecting Against a Password Attack
  * [Case Studies in Poor Password Management](https://resources.infosecinstitute.com/topic/case-studies-in-poor-password-management/) - infosecinstitute.com (Dimitar Kostadinov)
* Guidelines for Identifying Software Security Vulnerabilities
* Identifying Vulnerabilities in an Application
* Cracking a Password Hash
  * [Password Hash Cracker](https://crackstation.net/) - crackstation.net
  * [Password Cracking with Hashcat](https://cryptokait.com/2020/02/24/password-cracking-with-hashcat/) - cryptokait.com
  * [How to crack passwords with Hashcat](https://cyberrunner.medium.com/how-to-crack-passwords-with-hashcat-a9fb2aa1a813)
* Fixing a Password Hash Vulnerability
### Gather Intelligence on Vulnerabilities and Exploits
* Vulnerability Intelligence
  * [Enabling Defenders With Vulnerability Intelligence](https://www.fireeye.com/blog/threat-research/2020/04/enabling-defenders-with-vulnerability-intelligence.html) - fireeye.com
* Exploits
* Guidelines for Researching Vulnerabilities and Exploits
  * [CAPEC - Common Attack Pattern Enumerations and Classifications](https://capec.mitre.org/) - mitre.org | MITRE 
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
* Threat Modeling
  * [Application Threat Modeling](https://owasp.org/www-community/Application_Threat_Modeling)
  * [12 Available Methods (Threat Modeling)](https://insights.sei.cmu.edu/blog/threat-modeling-12-available-methods/) - cmu.edu
  * [Threat Modeling](https://www.synopsys.com/glossary/what-is-threat-modeling.html) :star: - synopsys.com | 
* [Benefits of Threat Modeling](https://resources.infosecinstitute.com/topic/6-benefits-of-cyber-threat-modeling/)
* Define General Security Objectives and Scope
* Tooling and Documentation
  * [Microsoft Threat Modeling Tool](https://www.microsoft.com/en-us/securityengineering/sdl/threatmodeling)
  * [OWASP Threat Dragon](https://threatdragon.org/login)
  * [SecuriCAD by Foreseeti](https://foreseeti.com/)
  * [ThreatModeler](https://threatmodeler.com/)
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
  * [Python Dependency Security](https://pyup.io/) - pyup.io | Keep your Python dependencies secure, up-to-date & compliant
  * [GitHub-native Dependabot](https://docs.github.com/en/code-security/supply-chain-security/keeping-your-dependencies-updated-automatically/about-dependabot-version-updates) - You can use Dependabot to keep the packages you use updated to the latest versions.
* Common General Programming Errors
  * Inappropriate use of dangerous functions, APIs, and system calls 
  * Use of deprecated libraries 
  * Buffer overruns 
  * Race conditions 
  * Integer range issues 
  * Out of bounds array indexing 
  * Unhandled exceptions 
  * Memory leaks 
  * Dangling and null pointer references 
  * Unused code 
  * Uninitialized variables 
  * Injection vulnerabilities
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

### Prevent Platform Vulnerabilities



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
  * Test early and test often.
  * View software design and implementation from an attacker's perspective.
  * Think of threat modeling as a form of testing (Testing the design). 
* Phases of Software Testin
  * [OWASP Web Security Testing Guide](https://github.com/OWASP/wstg) 
* Development Testing
  * Separation of duties (SoD; also known as Segregation of Duties) is the concept of having more than one person required to complete a task. 
  * **Dynamic analysis** is the testing and evaluation of an application during runtime. **Static analysis** is the testing and evaluation of an application by examining the code without executing the application. [Learn more](https://www.intel.com/content/www/us/en/develop/documentation/inspector-user-guide-windows/top/getting-started/dynamic-analysis-vs-static-analysis.html)
* Unit Testing
  * Input Validation; Output Encoding; Session Management (A&A); Encryption; Error Handling; Logging 
* Integration Testing
  * White box testing (Source Code); Gray box testing; Black box testing 
* Documentation and Deliverables for Testing
  * Input: Business requirements; SRS; Threat Models; Data flow Diagram
  * Output: Vulnerability Reports; Quality Assurance Reports
* Manual Inspection and Code Review
  * Security Analysis | A detailed process to ensure that software operates at a level of security consistent with the potential harm that could result from the loss, inaccuracy, alteration, unavailability, or misuse of the data and resources that it uses, controls, and protects.
  * Looking at your code from a different perspective will find problems or ask questions that you haven't considered. 
* Code Review Strategies
  * Formal
    * Fagan Inspection |  A formal analysis process that includes a series of structured activities involving multiple participants and phases—such as planning, inspection, rework, and verification. The objective is to reveal defects in programming code.
  * Informal
    * Over the wall (aks Pass Around)
    * Over the shoulder
    * Pair Programming  
* Guidelines for Security Testing
  * Performing Manual Inspection and Review
    - Web Server e.g., dotnet new web
    - IP Address
    - Query String (Whitelist, Length, Data type)
    - Authentication e.g., Authorize, AllowAnonymous
    - Directory browsing
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
  * Bug Bounty Program
    - [Microsoft Bug Bounty Program](https://www.microsoft.com/en-us/msrc/bounty) 
* Security Monitoring
* Intrusion Detection and Prevention
  * [What is an intrusion prevention system?](https://www.vmware.com/topics/glossary/content/intrusion-prevention-system) - vmware.com
  * [Best Intrusion Detection and Prevention Systems for 2021 (Guide to IDPS)](https://www.esecurityplanet.com/products/intrusion-detection-and-prevention-systems/) - esecurityplanet.com
* Monitor Placement
* Logging
* Guidelines for Monitoring and Logging a Deployed Application
* Monitoring and Logging a Deployed Application 
### Maintain Security after Deployment
* Maintenance
  * [The 4 software maintenance categories and what they mean for your users](https://www.parkersoftware.com/blog/the-4-software-maintenance-categories-and-what-they-mean-for-your-users/)
* Patches and Updates
  * [What is Regression Testing?](https://smartbear.com/learn/automated-testing/what-is-regression-testing/) - smartbear.com
* Uninstallation and Deprovisioning
* Guidelines for Maintaining Security of Deployed Software
* Maintaining Security After Deployment 

-----

## YouTube :tv:
* [How to Analyze Code for Vulnerabilities](https://www.youtube.com/watch?v=A8CNysN-lOM) - OWASP DevSlop

## Articles
* [57 Cybersecurity Terms You Should Know in 2021](https://securityscorecard.com/blog/57-cybersecurity-terms-you-should-know-in-2021) - securityscorecard.com
* [The Story of Cryptography: History](https://ghostvolt.com/articles/cryptography_history.html) - ghostvolt.com
* [Difference between Defect, Error, Bug, Failure and Fault!](https://www.360logica.com/blog/difference-between-defect-error-bug-failure-and-fault/) - 360logica.com

## Acronyms and Definitions
* [Acronyms and Definitions](https://github.com/NajiElKotob/Awesome-Secure-Coding/blob/main/Acronyms-and-Definitions.md)
-----
## References
* [Microsoft compliance offerings](https://docs.microsoft.com/en-us/compliance/regulatory/offering-home?view=o365-worldwide) - microsoft.com
* [ISO/IEC 27001](https://www.iso.org/isoiec-27001-information-security.html) - iso.org
* [NIST](https://www.nist.gov/cybersecurity) - nist.gov
* [OWASP](https://owasp.org/) - owasp.org
* [OWASP SAMM](https://owaspsamm.org/model/) - owaspsamm.org
* [CAPEC](https://capec.mitre.org/) - mitre.org
* [PCI Security Standards](https://www.pcisecuritystandards.org/) - pcisecuritystandards.org
* [SANS](https://www.sans.org/) - sans.org
* [Information Security Database (English/Arabic)](https://labs.ece.uw.edu/nsl/students/alomair/LB-Arabic/arabic/is-dictionary/index.html) - uw.edu (University of Washington)

## Monitoring
* [National Cyber Awareness System (Current Activity)](https://us-cert.cisa.gov/ncas/current-activity) - cisa.gov
* [Threat Map](https://www.fireeye.com/cyber-map/threat-map.html) - fireeye.com

## Cases
* [OpenSSL Heartbeat (Heartbleed) :tv:](https://www.youtube.com/watch?v=hTK0pywfmDE) - Fierce Outlaws
