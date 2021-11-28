# Awesome Secure Coding
~ Outlines are based on CertNexus CSC ([Cyber Secure Coder](https://certnexus.com/certification/cyber-secure-coder/))
`
Secure coding is a set of practices that applies security considerations 
to how software will be coded and encrypted to best defend against 
cyber attack or vulnerabilities. [NTT Security AppSec Solutions]
`

* [What is secure coding?](https://www.whitehatsec.com/glossary/content/secure-coding)


{Awesome Works in Progress}

-----
1. [Identifying the Need for Security in Your Software Projects](#1-identifying-the-need-for-security-in-your-software-projects)
1. [Handling Vulnerabilities](#2-handling-vulnerabilities)
1. [Designing for Security](#3-designing-for-security)
1. [Developing Secure Code](#4-developing-secure-code)
1. [Implementing Common Protections](#5-implementing-common-protections)
1. [Testing Software Security](#6-testing-software-security)
1. [Maintaining Security in Deployed Software](#7-maintaining-security-in-deployed-software)


-----


##  1. Identifying the Need for Security in Your Software Projects
### 1.1. Identify Security Requirements and Expectations
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
    - FISMA - Federal Information Security Management Act 
    - SOX - Sarbanes-Oxley Act 
    - GLBA - Gramm-Leach-Bliley Act 
    - New York State Information Security Breach and Notification Act [learn more](https://its.ny.gov/breach-notification)
    - FFIEC - Federal Financial Institutions Examination Council 
    - GDPR - General Data Protection Regulation (EU)
    - CCPA - California Consumer Privacy Act 
  * Insdustry Standards e.g.
    - COBIT - Control Objectives for Information and Related Technology
    - ITIL - Information Technology Infrastructure Library 
    - [ISO/IEC 27000](https://www.iso.org/news/ref2266.html) - Information Security Management System Standards
    - GASSP/GAISP - Generally Accepted System Security Principles and Generally Accepted Information Security Principles
    - [SABSA](https://sabsa.org/) - Sherwood Applied Business Security Architecture
    - [NIST](https://www.nist.gov/) - National Institute of Standards and Technology
    - PCI DSS - Payment Card Industry Data Security Standard 
  * Cases
    - [Microsoft compliance offerings](https://docs.microsoft.com/en-us/compliance/regulatory/offering-home?view=o365-worldwide) - Learn how Microsoft products and services help your organization meet regulatory compliance standards.
* User Impact
  * [Colonial Hack Shows U.S. Must Diversify Its Oil Reserves](https://www.bloomberg.com/opinion/articles/2021-05-16/colonial-pipeline-hack-shows-u-s-must-diversify-its-oil-reserves) - bloomberg.com
  * [HAFNIUM targeting Exchange Servers with 0-day exploits](https://www.microsoft.com/security/blog/2021/03/02/hafnium-targeting-exchange-servers/)
    - [خطوة غير مسبوقة.. FBI يخترق مئات الحواسيب عن بُعد](https://www.alarabiya.net/technology/2021/04/15/%D8%AE%D8%B7%D9%88%D8%A9-%D8%BA%D9%8A%D8%B1-%D9%85%D8%B3%D8%A8%D9%88%D9%82%D8%A9-FBI-%D9%8A%D8%AE%D8%AA%D8%B1%D9%82-%D9%85%D8%A6%D8%A7%D8%AA-%D8%A7%D9%84%D8%AD%D9%88%D8%A7%D8%B3%D9%8A%D8%A8-%D8%B9%D9%86-%D8%A8%D9%8F%D8%B9%D8%AF) - alarabiya.net 
  * Stuxnet | [A Weapon We Can’t Control](https://www.nytimes.com/2012/06/25/opinion/stuxnet-will-come-back-to-haunt-us.html) - nytimes.com
  * Zero-day  
  * [World's Biggest Data Breaches & Hacks](https://www.informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/) - informationisbeautiful.net
* User Expectations
  * Users expect applications to operate in a secure manner and without any error.
  * [Sample Terms of Use Template](https://www.termsfeed.com/blog/sample-terms-of-use-template/) - termsfeed.com
* Platform Requirements
  * AWS
    * [AWS Service Terms](https://aws.amazon.com/service-terms/) 
    * [AWS Customer Agreement](https://aws.amazon.com/agreement/)
  * [Microsoft Azure Legal Information](https://azure.microsoft.com/en-us/support/legal/)
* Consequences of Not Meeting Security Requirements
  * [5 Consequences That Result From Not Meeting Data Security Requirements](https://dzone.com/articles/5-consequences-that-result-from-not-meeting-data-s) - dzone.com
* Guidelines for Identifying Security Requirements and Expectations
  * Identify sources of security requirements
  * Elicit and prioritize security requirements 
  * Meet Standards and Compliance Requirements
* Identifying Security Requirements and Expectations
  * [Examples of ISO 27001 interested parties and your compliance requirements](https://www.itgovernance.co.uk/blog/examples-of-iso-27001-interested-parties) 
### 1.2. Identify Factors That Undermine Software Security
* Three Ps of Software Security
  * [The 3 Ps of Comprehensive Cybersecurity](https://blogs.cisco.com/customerexperience/the-3-ps-of-comprehensive-security) - cisco.com
  * [The 3 P’s of Cybersecurity](https://cmitsolutions.com/blog/3-ps-cybersecurity-put-basic-fundamentals-work-business/) - cmitsolutions.com
* Software Security Terminology
  * [The Dummies Guide to Cyber Security Terminology](https://www.metacompliance.com/cyber-security-terminology/) - metacompliance.com
* Identifying Factors That Undermine Security 
  * [The Human Factor in IT Security: How Employees are Making Businesses Vulnerable from Within](https://www.kaspersky.com/blog/the-human-factor-in-it-security/) - kaspersky.com

### 1.3. Find Vulnerabilities in Your Software
* Builders and Breakers
  * [Builders vs Breakers: Bridging the gap Between Software Development and InfoSec](https://securitytrails.com/blog/interview-tanya-janca) - Tanya Janca
* Hacking
  * [Hacking](https://www.malwarebytes.com/hacker) - malwarebytes.com
  * [Ethical hacker](https://searchsecurity.techtarget.com/definition/ethical-hacker) :star: - techtarget.com
  * [Different Types of Hackers: The 6 Hats Explained](https://sectigostore.com/blog/different-types-of-hackers-hats-explained/) - sectigostore.com
* Phases of an Attack
  * [The seven phases of a cyber attack](https://www.dnv.com/article/the-seven-phases-of-a-cyber-attack-118270) - dnv.comsectigostore.com
* Common Attack Patterns
  * [The 5 Most Common Attack Patterns of 2014](https://www.tripwire.com/state-of-security/featured/the-5-most-common-attack-patterns-of-2014/) 
  * [Flood Attacks](https://www.watchguard.com/help/docs/help-center/en-US/Content/en-US/Fireware/intrusionprevention/flood_attacks_c.html) also known as Denial of Service (DoS) attacks. In a flood attack, attackers send a very high volume of traffic to a system so that it cannot examine and allow permitted network traffic.
  * Reconnaissance
  * Gain Access Privileges
    - Brute force attacks 
      - [How Secure is My Password](https://howsecureismypassword.net/) - howsecureismypassword.net
      - [Popular tools for brute-force attacks 📰](https://resources.infosecinstitute.com/topic/popular-tools-for-brute-force-attacks/) - infosecinstitute.com
    - Authentication abuse 
    - Authentication bypass
  * Memory Manipulation
  * Reverse Engineering
  * Functionality misuse
  * [What Is Phishing?](https://www.comptia.org/content/articles/what-is-phishing) - comptia.org
  * [Sustained Client Engagement](https://capec.mitre.org/data/definitions/227.html)
  * [Action Spoofing](https://capec.mitre.org/data/definitions/173.html)
* Case Study: Protecting Against a Password Attack
  * [Case Studies in Poor Password Management](https://resources.infosecinstitute.com/topic/case-studies-in-poor-password-management/) - infosecinstitute.com (Dimitar Kostadinov)
* Guidelines for Identifying Software Security Vulnerabilities
* Identifying Vulnerabilities in an Application
* Cracking a Password Hash
  * [MD5 Hash Generator](https://www.md5hashgenerator.com/) - md5hashgenerator
  * [Password Hash Cracker](https://crackstation.net/) - crackstation.net
  * [Password Cracking with Hashcat](https://cryptokait.com/2020/02/24/password-cracking-with-hashcat/) - cryptokait.com
  * [How to crack passwords with Hashcat](https://cyberrunner.medium.com/how-to-crack-passwords-with-hashcat-a9fb2aa1a813)
* Fixing a Password Hash Vulnerability
### 1.4. Gather Intelligence on Vulnerabilities and Exploits
* Vulnerability Intelligence
  * [Enabling Defenders With Vulnerability Intelligence](https://www.fireeye.com/blog/threat-research/2020/04/enabling-defenders-with-vulnerability-intelligence.html) - fireeye.com
* Exploits
* Guidelines for Researching Vulnerabilities and Exploits
  * [CAPEC - Common Attack Pattern Enumerations and Classifications](https://capec.mitre.org/) - mitre.org | MITRE 
* Identifying Sources for Vulnerability Intelligence 


-----
## 2. Handling Vulnerabilities
### 2.1. Handle Vulnerabilities Due to Software Defects and Misconfiguration
* Software Defects
  * [Difference between Defect, Error, Bug, Failure and Fault!](https://www.360logica.com/blog/difference-between-defect-error-bug-failure-and-fault/) - 360logica.com
* Causes of Software Defects
  * Flaw in the design; Bugs; 3rd party code; Change in the context; ... 
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
* Fail-Safe | A system or plan that comes into operation in the event of something going wrong or that is in place to prevent such an occurrence.
* Failure Recovery
* Guidelines for Secure Error Handling
* Identifying Software Defects and Misconfiguration

### 2.2. Handle Vulnerabilities Due to Human Factors
* The Human Element in Software Security
* Vulnerabilities Attributed to the Human Element
* Social Engineering Attacks
  * [5 Social Engineering Attacks to Watch Out For](https://www.tripwire.com/state-of-security/security-awareness/5-social-engineering-attacks-to-watch-out-for/) - David Bisson
* User Input
* Input Validation
  * [Input Validation Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Input_Validation_Cheat_Sheet.html) - owasp.org
    - **Syntactic** validation should enforce correct syntax of structured fields (e.g. SSN, date, currency symbol).
    - **Semantic** validation should enforce correctness of their values in the specific business context (e.g. start date is before end date, price is within expected range).
  * Blacklist vs Whitelist
* Security Policy Enforcement
* Guidelines for Managing People Risks
* Managing People Risks

### 2.3. Handle Vulnerabilities Due to Process Shortcomings
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
## 3. Designing for Security
### 3.1. Apply General Principles for Secure Design
* Security in the Design Phase
  * ~50% of software security issues are due to design flaws
  * The design phase refers to functions typically performed by a software architect (strategic design of the entire system)
  * Integrate security into every phase of your development process
* Security by Obscurity vs. Security by Design
  * [Open-source and the “security through obscurity” fallacy](https://www.efrontlearning.com/blog/2012/04/open-source-and-the-security-through-obscurity-fallacy.html) - efrontlearning.com
  * National Institute of Standards and Technology (NIST) specifically recommends against using closed source as a way to secure the software (i.e. “security through obscurity”)
  * Hiding source code is a bad way to assume you’ll achieve security, because even a powerful and highly proprietary company can’t guarantee that source code won’t leak out.
* OWASP Security Design Principles
  * [Secure Design Principles](https://github.com/OWASP/DevGuide/blob/master/02-Design/01-Principles%20of%20Security%20Engineering.md) - OWASP
    - Minimize attack surface area. 
    - Establish secure defaults. 
    - Least privilege. 
    - Defense in depth. 
    - Fail securely. 
    - Don't trust services. 
    - Separation of duties. 
    - Avoid Security by Obscurity. 
    - Keep security simple. 
    - Fix security issues correctly. 
* Software Design Patterns
* Security Patterns
* Modular Design
* Benefits of Modular Design
* The Balance Between Defense in Depth and Simplicity
* [Guidelines for Avoiding Common Design Mistakes](https://www.synopsys.com/blogs/software-security/avoid-software-security-flaws/) - synopsys.com
  * [Earn or give, but never assume, trust.](https://cybersecurity.ieee.org/blog/2015/11/13/avoiding-the-top-10-software-security-design-flaws-earn-or-give-but-never-assume-trust) - ieee.org
  * Use an authentication mechanism that cannot be bypassed or tampered with.
  * Authorize after you authenticate.
  * Strictly separate data and control instructions, and never process control instructions received from untrusted sources.
  * Define an approach that ensures that all data are explicitly validated.
  * Use cryptography correctly.
  * Identify sensitive data and how they should be handled.
  * Always consider the users.
  * Understand how integrating external components changes your attack surface.
  * Be flexible when considering future changes to objects and actors.
* Avoiding Common Security Design Flaws


### 3.2. Design Software to Counter Specific Threats
* [The Risk Equation](http://www.icharter.org/articles/risk_equation.html)
* Threat Modeling
  * Microsoft Threat Modeling
    - [Microsoft Threat Modeling](https://www.microsoft.com/en-us/securityengineering/sdl/threatmodeling) - microsoft.com
  * SeaSponge
    - [SeaSponge Threat Modeling Tool](https://mozilla.github.io/seasponge/)
    - [Example Threat Model developed with SeaSponge](https://github.com/mozilla/seasponge#example-threat-model-developed-with-seasponge)
  * [Application Threat Modeling](https://owasp.org/www-community/Application_Threat_Modeling) - owasp.org
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
  * [STRIDE chart](https://www.microsoft.com/security/blog/2007/09/11/stride-chart/) - microsoft.com
* PASTA
* Misuse Cases
  * Misuse cases (aka abuse cases or attack scenarios) are a form of use case that describes actions that should be prevented 
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
## 4. Developing Secure Code
### 4.1. Follow Best Practices for Secure Coding
* Development Documentation and Deliverables
  * [Functional vs Non-Functional Requirements: The Definitive Guide](https://qracorp.com/functional-vs-non-functional-requirements/) - qracorp.com
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

### 4.2. Prevent Platform Vulnerabilities
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

### 4.3. Prevent Platform Vulnerabilities



-----
## 5. Implementing Common Protections
### 5.1. Limit Access Using Login and User Roles
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
### 5.2. Protect Data in Transit and At Rest
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
### 5.3. Implement Error Handling and Logging
* Error Handling
* Uses for Error Handling
* Error Messaging
* Logging
* Guidelines for Implementing Error Handling and Logging
* Reviewing Error Handling
* Improving Error Handling 
### 5.4. Protect Sensitive Data and Functions
* Sensitive Data
* Output Restrictions
* Function Level Access Control
  * [Missing Function Level Access Control](https://blog.detectify.com/2016/07/13/owasp-top-10-missing-function-level-access-control-7/) - detectify.com
  * [What is Missing Function Level Access Control? :tv:](https://www.youtube.com/watch?v=oVV-lSB7ddc) - Detectify
* Case Study: Cross*Site Scripting Defect
* Guidelines for Protecting Sensitive Data and Functions
* Protecting Sensitive Data and Functions
* Staging a Persisted XSS Attack on an Administrator Function
### 5.5. Protect Database Access
* Case Study: SQL Injection Defect
* Query Parameterization
* Database Connection Credential Protection
* Guidelines for Protecting Database Access
* Protecting Database Access


-----
## 6. Testing Software Security
### 6.1. Perform Security Testing
* The Role of Testing
  * Test early and test often.
  * View software design and implementation from an attacker's perspective.
  * Think of threat modeling as a form of testing (Testing the design). 
  * Mindsets; penetrate and patch, penetrate and improve, building security in
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
    - Web Server e.g., dotnet new web; dotnet watch
    - IP Address e.g., [MVC - Block IP Address Using Action Filter](https://www.c-sharpcorner.com/article/mvc-block-ip-address-using-action-filter/)
    - Query String (Whitelist, Length, Data type)
    - Authentication e.g., Authorize, AllowAnonymous
    - Directory browsing
### 6.2. Analyze Code to find Security Problems
* Static Code Analysis
  * Static Code Analysis | The process of using a computer program to find problems in code, without actually executing the code. 
* Strategies for Using Static Analysis
* Dynamic Code Analysis
* Guidelines for Code Analysis
* Performing Code Analysis
### 6.3. Use Automated Testing Tools to Find Security Problems
* Automated Testing
* Unit Testing
* Guidelines for Using Automated Testing Tools
* Using a Test Suite to Automate Unit Testing


-----
## 7. Maintaining Security in Deployed Software
### 7.1. Monitor and Log Applications to Support Security
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
### 7.2. Maintain Security after Deployment
* Maintenance
  * [The 4 software maintenance categories and what they mean for your users](https://www.parkersoftware.com/blog/the-4-software-maintenance-categories-and-what-they-mean-for-your-users/)
* Patches and Updates
  * [What is Regression Testing?](https://smartbear.com/learn/automated-testing/what-is-regression-testing/) - smartbear.com
* Uninstallation and Deprovisioning
* Guidelines for Maintaining Security of Deployed Software
* Maintaining Security After Deployment 
  * Corrective Maintenance
  * Adaptive Maintenance
  * Perfective Maintenance
  * Preventive Maintenance

-----

## YouTube :tv:
* [How to Analyze Code for Vulnerabilities](https://www.youtube.com/watch?v=A8CNysN-lOM) - OWASP DevSlop

## Tools
* [Secure Password Generator](https://passwordsgenerator.net/) - passwordsgenerator.net


## Articles
* [The Top 8 Cybersecurity Predictions for 2021-2022](https://www.gartner.com/en/articles/the-top-8-cybersecurity-predictions-for-2021-2022) - gartner.com
* [57 Cybersecurity Terms You Should Know in 2021](https://securityscorecard.com/blog/57-cybersecurity-terms-you-should-know-in-2021) - securityscorecard.com
* [The Story of Cryptography: History](https://ghostvolt.com/articles/cryptography_history.html) - ghostvolt.com
* [All About CWE: Common Weakness Enumeration](https://www.parasoft.com/blog/what-is-cwe/) - parasoft.com
* [13 tools for checking the security risk of open-source dependencies](https://techbeacon.com/app-dev-testing/13-tools-checking-security-risk-open-source-dependencies) - techbeacon.com

## Magazines
* [LHN](https://latesthackingnews.com/category/cyber-security-news/) - latesthackingnews.com


## Acronyms and Definitions
* [Acronyms and Definitions](https://github.com/NajiElKotob/Awesome-Secure-Coding/blob/main/Acronyms-and-Definitions.md)
-----
## References
* Microsoft
  * [Microsoft compliance offerings](https://docs.microsoft.com/en-us/compliance/regulatory/offering-home?view=o365-worldwide) - microsoft.com
* [ISO/IEC 27001](https://www.iso.org/isoiec-27001-information-security.html) - iso.org
* [NIST](https://www.nist.gov/cybersecurity) - nist.gov | The National Institute of Standards and Technology
  * [Search Vulnerability Database](https://nvd.nist.gov/vuln/search) 
* [OWASP](https://owasp.org/) - owasp.org | The Open Web Application Security Project is an online community that produces freely-available articles, methodologies, documentation, tools, and technologies in the field of web application security.
* OWASP
  * [OWASP SAMM](https://owaspsamm.org/model/) - owaspsamm.org
  * [Web Security Testing Guide (WSTG)](https://owasp.org/www-project-web-security-testing-guide/stable/)
  * [OWASP Proactive Controls](https://owasp.org/www-project-proactive-controls/) - The OWASP Top Ten Proactive Controls describes the most important control and control categories that every architect and developer should absolutely, 100% include in every project.
  * [OWASP Secure Coding Practices-Quick Reference Guide](https://owasp.org/www-project-secure-coding-practices-quick-reference-guide/migrated_content)
  * [Secure Design Principles](https://github.com/OWASP/DevGuide/blob/master/02-Design/01-Principles%20of%20Security%20Engineering.md)
* MITRE
  * [CAPEC](https://capec.mitre.org/) - mitre.org | Common Attack Pattern Enumeration and Classification
  * [CWE](https://cwe.mitre.org/) - mitre.org | Common Weakness Enumeration
  * [ATT&CK](https://attack.mitre.org/) - mitre.org | MITRE ATT&CK is a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations.
* [PCI Security Standards](https://www.pcisecuritystandards.org/) - pcisecuritystandards.org
* [Exploit Database](https://www.exploit-db.com/) - exploit-db.com | Exploits for Penetration Testers, Researchers, and Ethical Hackers
* [SANS](https://www.sans.org/) - sans.org | SANS Institute is the most trusted resource for cybersecurity training, certifications and research.
  * [CWE/SANS TOP 25 Most Dangerous Software Errors](https://www.sans.org/top25-software-errors/) 
* [CVE Details](https://www.cvedetails.com/) - cvedetails.com | The ultimate security vulnerability datasource
* [Information Security Database (English/Arabic)](https://labs.ece.uw.edu/nsl/students/alomair/LB-Arabic/arabic/is-dictionary/index.html) - uw.edu (University of Washington)
* [The Signals Intelligence Agency (SIA), fka the National Electronic Security Authority (NESA)](https://en.wikipedia.org/wiki/Signals_Intelligence_Agency)


## Monitoring
* [National Cyber Awareness System (Current Activity)](https://us-cert.cisa.gov/ncas/current-activity) - cisa.gov
* [Threat Map](https://www.fireeye.com/cyber-map/threat-map.html) - fireeye.com

## Cases
* [OpenSSL Heartbeat (Heartbleed) :tv:](https://www.youtube.com/watch?v=hTK0pywfmDE) - Fierce Outlaws
* [Cracking Stuxnet, a 21st-century cyber weapon](https://www.youtube.com/watch?v=CS01Hmjv1pQ) - Ralph Langner
* [How the US East Coast Lost Half It's Oil to 1 Hacker](https://www.youtube.com/watch?v=rBPud5PyySk) - RealLifeLore

