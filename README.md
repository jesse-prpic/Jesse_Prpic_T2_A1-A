# T2A1-A: Workbook Part A

## Question One
### Describe the architecture of a typical API project, such as Flask application
Within the software industry architecture can be referred to as "the highest-level framework, the skeleton of the software syste. It's one of the very first choices made for the bedrock of the system" (Pitaliya, 2021). Before anything is created the architecture of the system should be the forefront of the project and one of these architecure types is Application Program Interface (API) Architecture.

API Architecure is an ecosystem that is created through utilising the developement of software interfaces that utilise the backend data allowing applications functional for use in applications, this is done through four layers; Information Management, Application, Integration, Interaction (What Is API Architecture? | Akana by Perforce, n.d.).
When it comes to an API project, Flask application is the industry standard which is a lightweight Python web framework which allows the user to utilise the application by splitting the major parts into specific directories and files for a more organised application (www.digitalocean.com, n.d.).

Lets take a typical architecture of a HR portal for example; you will need to have main routes for employees that use the portal, this file could be called "routes.py" and inside this file a directory would be made "employees". Within this framework it would be appropriate to create a module called "employees.py" when you would collate the database and have other directories such as; payroll, leave requests, employee information etc and it would start to look something like;

.
└── flask_app
    ├── app
    │   ├── extensions.py
    │   ├── __init__.py
    │   ├── main
    │   │   ├── __init__.py
    │   │   └── routes.py
    │   ├── employees
    │   │   ├── payroll.py
    │   │   └── leave_request.py
    │   ├── payroll
    │   │   ├── __init__.py
    │   │   └── routes.py
    │   ├── leave_request
    │   │   ├── __init__.py
    │   │   └── routes.py
    │  
    ├── app.db
    ├── requirements.txt
    │── config.py
    └── run.py

This would be a fairly simple starting point of the blueprint for a structure of utilising flask and allowing API's to migrate between systems.

## Question Two
### Identify a database commonly used in an API project (such as a Flask application) and discuss the pros and cons of this database.
API's and databases are commonly used together to facilitate retrieval, manage and manipulation of stored data by various applications, throughout this application we will be speaking about PostgreSQL

PostgreSQL is described by Richard Peterson (2024) as "an enterpise-class open source database management system. It supports both SQL and JSON for relational and non-relational queries for extensibility and SQL compliance", it is one of the most advanced open source database management systems, which is impressive as it is also one of the oldest.
Each database management system will have advantages and disadvantages; for example with Microsoft SQL Server, they may have Scalability and security as an advantage, but with that the cost and compatibility as a disadvantage. When it comes to PostgreSQL they demonstrate their advantages through being reliable, flexibile and scalable(Vojak, 2022).
PostgreSQL demonstrates these advantages respectfully by, being able to handle a large amount of data and being highly stable, supporting a plethora of data types (numerial, text and spacial) as well as being able to support custom data types; and thirdly, by being able to run on a server or even multiple servers through distribution, it is an ideal choice due to it being able to handle a large number of users and process a lot of data (Vojak, 2022).

However it is rare to see something that only has advantages without disadvantages; with PostgreSQL these disadvantages come in the form of complexity and being not so performant. Due to PostgreSQL being highly configurable, it leaves it to be challenging for set up and to maintain as well as it can become slower than some other databases due to its dealing with all the types of data (Vojak, 2022).

Overall among other open-source management system, PostgreSQL is a powerful database to be used in an API project, with 50,734 companies utilising it; Netflix, Instagram, Uber and Skype to name a few (Companies That Use PostgreSQL - PostgreSQL Clients, n.d.).


## Question Three
### Discuss an implementation of an Agile project management methodology for an API project.
The methodology of Agile Project Management is based off managing and develivering projects in an interative and incremental way which has the benefits of acheiving customer and stakholder alignment, continuous improvement and rapid progress. Agile project is an umbrella term that includes a range of methodologies; Scrum, Kanban, Extreme Programming (XP), and the Adaptive Project Framework (APF) (Wrike, n.d.). 

Each one of these methologies have something different to offer, whether it being the practices, processes or tools. Scrum relates to the fixed length spring ] reference ], Kanban is the visual aspect of management with continous devlivery - this would be your trello or dashboards to project stages. Extreme Programming (XP) relates to the technical practices throughout the testing, development and integrations and finally Adaptive Software Development emphasises the adaption of collaboration, planning and learning from experiennce ] reference ].

The difference between an Agile and traditional methodologies is that traditional are more rigid with fixed and strict guidelines, this can be known as the waterfall approach where a stage needs to be completed before another stage can be started. Whereas, Agile is more fluid and adaptive as it breaks projects into phases and allows flexibility when it comes to changing requirements (Wrike, n.d.).

By understanding these methodologies first is important before you start the process of implementation amongst your API project. To implement the theoretical frameworks into practice you will need to choose the right Agile framework, assemble your Agile team, plan the project, manage stakeholder expectations and finally measure the success (Wrike, n.d).

## Question Four
### Provide an overview and description of a standard source control process for an API project.
Source control or otherwise known as version control is the way of being able to track and manage changes to ones code; systems such as source control management (SCM) have the abilitiy to provide this history whether it serves for the purpose of code developement, revision of code or even when there is a conflict between multiple sources (Amazon Web Services, 2019).

By developers being able to make tweaks, update and have it stored in a server allows a simplistic and straighforward method of managing changes. There are four types of source controls available; Distributed, Centralized, Lock-Based and Optiimistic - with the two more populars being Distributed and Centralized being able to store files among multiple repositories or a centralized one(GitLab, n.d.).

Source control processes can standardise an API project by structuring these version controls, and providing stability across developing projects; it can also provide many other advantages and benefits regarding quality, visbility and acceleration. 
These advantages can be summarised respectively by encouraging collaboration through frequent peer review leads to improvement in code quality, the ability to review previous source code is able to address issues and minimize downtime providing accelleration in projects and with transparency throughout with a source of truth this give the code visitbity and provides project oversight (GitLab, n.d.).

A system that can be used and is industry standard is Git which is open-sourced and is able to be used for any size of project. By having a system in place is one thing, but its another thing on how to manage it, a few things that are recommended is; committing files with a purpose, write good and meaningful messages in each commit and making sure every commit is traceable (Schiestl, 2020).

## Question Five
### Provide an overview and description of a standard testing process for an API project.

Testing is an integral part of any process, throughout software it is the practice of testing that validates the performance of a program and how it behaves.

## Question Six
### Explain the three principles of information system security.

Information system security, or otherwise referred to as InfoSec is the processes and proceedural tools designed to protect individual, businesses and organisations information - whether that information being modified, destroyed, distrupted, recored or inspected. 
Information security is becoming increasingly more important than ever due to the vast development of technology in the 21st century, it is critical that certain data such as financial data, customer account details, intellectual property etc are protected as this could lead to consequences of this data being stolen, data tampering or deletion. [ insert reference [
Amongst a business standpoint, this can disrupt and damage a reputation of the business causing tangible costs amongst the owners and investors, on an individual standpoint this data could be used against them with the incidents of identify theft or even blackmail.

Confidentiality, Integrity and Availability are the three structures of what is also known as the CIA Triad (Geveye, 2023). These structures have an ultimate goal in place as a whole, however they have their own individual goals; 


{ Insert triad image here {


- confidentiality has the main goal of encryption of information as well as utlization of strong password constraints in the means of using different letters, numbers and character. Two Factor Authentication (2FA) is also a practice that is becoming more and more prevelant these days, where security measures have been put in place where you are needing to sign in and confirm a link or code that has been sent to your mobile or email (Principle of Information System Security, 2020).

- integrity has the main goal of making sure that information is accurate and consistent as well as having the ability to recover any data that was lost due to the violation of the informations integrity. 
An example that securitymadesimple, 2020 has provided is; "if the CFO sends a document to be examined or reviewed by the director of finance. The director of finance may try to manipulate the information without the CFO knowing in order to make his/her department look better, launder money etc". This reiterates the importance of the controls that businesses and individuals need to have on their information; having secure backups where you are confident you will be able to recover all if not most items; these backups should be routinely done and ongoing. 
In addition; user access should also be updated and checked routinely; especially if there has been an attempt at a violation.

- availability; although the last structure in the CIA Triad; it may be one of the first signs of understanding if there is an attempt of an InfoSec risk as this relates to the reliability and accessbility of information - such as a website. In 2024 a SaiPoint blog post echoed this through a quote; "The availability of element of the CIA triad is often the proverbial canary in the coal mine; if systems have been compromised, availability is usually one of the first indicators of trouble".
Although confidentiality and integrity may seem like the more important concepts of the CIA Triad - what use is it to anyone if its not accessible.

( Summary



## Question Seven
### Provide an overview of what would need to be done within an API project to implement at least one of the principles explained in Question 6.

Previously we had touched upon the principles of information security systems or InfoSec, throughout this we learned that this is made up on Confidentiality, Integrity and Availability - CIA Triad.
Although we did have an overview of what these are, we did not explain how these may be implemented - each of them having different best practices.
Imagine working for a bank or even your own e-commerce store, with the main purpose being able to process financial transactions - your job is to ensure that these systems have the right practices in place so that transaction are accurate and consistent, this is the main goal of the integrity principle.

In 2024, Cambridge Dictionary defined integrity as, "the quality of being honest and having strong moral principles that you refuse to change", however in this context a more appropriate definition would be; "the property that sensitive data has not been modified or deleted in an unauthorized and undetected manner since it was created, transmitted or stored" (Barker & Barker, 2019).

There are many ways for a business to implement this principle into their systems, one being utilising secure backup systems as we have already mentioned - another being "Hashing" and Secure Passowrd Hashing.
This concept of hashing is a fixed-length alphanumeric value - it is a fingerprint for your data essentially, with each change with the data the value will change. This can be very useful when applying this to stored passwords as it adds random data which makes is more difficult for an attacker to crack a password's hash (Stickney, 2021).

To implement this code into your system; first use a strong hashing algorithm that is designed for password storage (e.ge., bcrypt, Argon2, haslib etc). In addition, you can also add in something called "Salt", by salting your password before hasing as this will ensure that passwords that are identical have a unique hash (Stickney, 2021).

In this example we will use bcrypt as our import to initialise the hashing:

An example by geeksforgeeks(2022) provided a simple code to get us started.

______________________

import bcrypt
 
##### Declaring our password
password = b'GeekPassword'
 
##### Adding the salt to password
salt = bcrypt.gensalt()
##### Hashing the password
hashed = bcrypt.hashpw(password, salt)
 
##### printing the salt
print("Salt :")
print(salt)
 
##### printing the hashed
print("Hashed")
print(hashed)

______________________


## Question Eight
### Explain the legal obligations that developers of a social media website or social media application would have in regards to handling user data, with reference to any applicable laws or acts.

In every industry there is a legal obligation and being a developer of a social media website or media application is no exemption. These legal obligations are influenced by a variety of needs to protect user privacy and ensure data security - both on a national and an international scale.

In Australia specifically, we have many acts and legal obligations that need to be abided by - these primarily are based from the Privacy Act 1988. It is the Office of the Australian Information Commissioner (OAIC) that defines the act; "The Privacy Act 1988 was introduced to promote and protect the privacy of individuals and to regulate how Australian Government agencies and organisations with an annual turnover of more than $3 million, and some other organisations, handle personal information" (n.d.).

This legislative act is to set out right's for people in regards to the collection, use and sharing of personal information and is done so through 13 Australian Privacy Principles (APPS). APPS are to govern the rights, obligations and standards pertaining to an organisation or agency's governance and accountability through to the rights of individuals to access their own personal information.

The 13 Australian Principles are;
- 1. Open and transparent management of personal information
- 2. Anonymity and pseudonymity
- 3. Collection of solicited personal information
- 4. Dealing with unsolicited personal information
- 5. Notification of the collection of personal information
- 6. Use or disclosure of personal information
- 7. Direct marketing
- 8. Cross-border disclosure of personal information
- 9. Adoption, use or disclosure of government related identifiers
- 10. Quality of personal information
- 11. Security of personal information
- 12. Access to personal information
- 13. Correction of personal information
Provided by Office of the Australian Information Commissioner (OAIC, 2023)

Within the software developer industry the Privacy Act 1988 is heighly relevant when it comes to handling user data, specifically for developers of social media websites. When it comes to APP 1, this reflects the kinds of information that is collected, held and used - whether that being names, emails and location data(OAIC, 2023) and as a social media platform this must have a comprehensive privacy policy in place, generally this will be accessed easily through a link on a website, or app settings.

Another critical APP to mention for software media platforms is APP 11, this relates to the requirement of personal information to be protected from being misused or interferred with (OAIC, 2019). It is important that the software media platforms create strong and well rounded encryption protocols for data.

These are only the legal obligations that pertain to Australia, with a plethora of other legal obligations throughout as well as international laws.


## Question Nine
### Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.

## Question Ten
### Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.

## Question Eleven
### Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.

## Question Twelve
### Conduct research into a web application (app) and answer each of the following sub-questions:

#### List and describe the software (tech stack) used by the app. 
#### Describe or make educated guesses about the hardware used to host the app.
#### Describe the interaction of technologies within the app.
#### Describe the way data is structured within the app’s database(s).
#### Identify the entities/tables that are tracked within the app’s database(s).
#### Identify the relationships and associations between the entities/tables identified in sub-question E.
#### Design an entity relationship diagram (ERD) based on the answers provided to sub-questions E and F. This must represent a relational database model, even if the app itself uses something other than a relational database model.

## Bibliography / References

Pitaliya, S. (2021, May 27). Understanding Software Architecture: A Complete Guide. Medium. https://sarrahpitaliya.medium.com/understanding-software-architecture-a-complete-guide-cb8f05900603

What Is API Architecture? | Akana by Perforce. (n.d.). Akana. https://www.akana.com/blog/api-architecture

www.digitalocean.com. (n.d.). How To Structure a Large Flask Application with Flask Blueprints and Flask-SQLAlchemy | DigitalOcean. [online] Available at: https://www.digitalocean.com/community/tutorials/how-to-structure-a-large-flask-application-with-flask-blueprints-and-flask-sqlalchemy.

Peterson, R. (2024, March 24). What is PostgreSQL? Introduction, History, Features, Advantages. Guru99.com. https://www.guru99.com/introduction-postgresql.html

Vojak, J. (2022, December 22). Exploring the pros and cons of SQL databases — MySQL, Postgres, Oracle, Microsoft SQL, and Amazon…. Medium. https://josipvojak.com/exploring-the-pros-and-cons-of-sql-databases-mysql-postgres-oracle-microsoft-sql-and-amazon-3c8de880b8d4

Wrike. (n.d.). What is Agile Methodology in Project Management? Wrike. https://www.wrike.com/project-management-guide/faq/what-is-agile-methodology-in-project-management/

Companies That Use PostgreSQL - PostgreSQL Clients. (n.d.). Thomson Data. Retrieved August 2, 2024, from https://www.thomsondata.com/customer-base/companies-that-use-postgresql.php#:~:text=Companies%20using%20PostgreSQL%20mostly%20do

What is Source Control? - Amazon Web Services. (2019). Amazon Web Services, Inc. https://aws.amazon.com/devops/source-control/

GitLab. (n.d.). What is version control? GitLab. https://about.gitlab.com/topics/version-control/

Schiestl, B. (2020, May 21). 8 Version Control Best Practices. Perforce Software. https://www.perforce.com/blog/vcs/8-version-control-best-practices

securitymadesimple. (2020, December 24). What are the 3 principles of Information Security? SecurityMadeSimple.org. https://securitymadesimple.org/cybersecurity-blog/what-are-the-3-principles-of-information-security/

CIA triad: Confidentiality, integrity, and availability. (n.d.). SailPoint. https://www.sailpoint.com/identity-library/cia-triad/

Principle of Information System Security. (2020, January 15). GeeksforGeeks. https://www.geeksforgeeks.org/principle-of-information-system-security/

Geveye, M. O. (2023, November 2). Understanding the Core Principles of Information Security. Centraleyes. https://www.centraleyes.com/core-principles-of-information-security/

Cambridge Dictionary. (2024). INTEGRITY | Meaning in the Cambridge English Dictionary. Cambridge.org. https://dictionary.cambridge.org/dictionary/english/integrity

Barker, E., & Barker, W. (2019, May 23). Recommendation for Key Management: Part 2 – Best Practices for Key Management Organizations. Csrc.nist.gov. https://csrc.nist.gov/pubs/sp/800/57/pt2/r1/final

Stickney, J. (2021, July 18). Hashing & Integrity — The “I” in the CIA Triad. Medium. https://jacob-e-stickney.medium.com/hashing-integrity-the-i-in-the-cia-triad-98b722b6fe39

https://www.geeksforgeeks.org/how-to-hash-passwords-in-python/

Office of the Australian Information Commissioner. (n.d.). The Privacy Act. OAIC; Australian Government. https://www.oaic.gov.au/privacy/privacy-legislation/the-privacy-act

Office of the Australian Information Commissioner. (2023, March 10). Rights and responsibilities. OAIC. https://www.oaic.gov.au/privacy/privacy-legislation/the-privacy-act/rights-and-responsibilities

OAIC. (2023, March 10). Chapter 1: APP 1 Open and transparent management of personal information. OAIC. https://www.oaic.gov.au/privacy/australian-privacy-principles/australian-privacy-principles-guidelines/chapter-1-app-1-open-and-transparent-management-of-personal-information

https://www.oaic.gov.au/privacy/privacy-legislation/the-privacy-act/rights-and-responsibilities