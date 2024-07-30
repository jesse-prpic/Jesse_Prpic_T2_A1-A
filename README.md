# T2A1-A: Workbook Part A

## Question One
### Describe the architecture of a typical API project, such as Flask application

## Question Two
### Identify a database commonly used in an API project (such as a Flask application) and discuss the pros and cons of this database.

## Question Three
### Discuss an implementation of an Agile project management methodology for an API project.

## Question Four
### Provide an overview and description of a standard source control process for an API project.

## Question Five
### Provide an overview and description of a standard testing process for an API project.

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

{ Summary {



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

securitymadesimple. (2020, December 24). What are the 3 principles of Information Security? SecurityMadeSimple.org. https://securitymadesimple.org/cybersecurity-blog/what-are-the-3-principles-of-information-security/

CIA triad: Confidentiality, integrity, and availability. (n.d.). SailPoint. https://www.sailpoint.com/identity-library/cia-triad/

Principle of Information System Security. (2020, January 15). GeeksforGeeks. https://www.geeksforgeeks.org/principle-of-information-system-security/

Geveye, M. O. (2023, November 2). Understanding the Core Principles of Information Security. Centraleyes. https://www.centraleyes.com/core-principles-of-information-security/

Cambridge Dictionary. (2024). INTEGRITY | Meaning in the Cambridge English Dictionary. Cambridge.org. https://dictionary.cambridge.org/dictionary/english/integrity

Barker, E., & Barker, W. (2019, May 23). Recommendation for Key Management: Part 2 – Best Practices for Key Management Organizations. Csrc.nist.gov. https://csrc.nist.gov/pubs/sp/800/57/pt2/r1/final

Stickney, J. (2021, July 18). Hashing & Integrity — The “I” in the CIA Triad. Medium. https://jacob-e-stickney.medium.com/hashing-integrity-the-i-in-the-cia-triad-98b722b6fe39

https://www.geeksforgeeks.org/how-to-hash-passwords-in-python/