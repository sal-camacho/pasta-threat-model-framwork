# Activity Overview 

In this activity, you will practice using the Process of Attack Simulation and Threat Analysis (PASTA) threat model framework. You will determine whether a new shopping app is safe to launch.

Threat modeling is an important part of secure software development. Security teams typically perform threat models to identify vulnerabilities before malicious actors do. PASTA is a commonly used framework for assessing the risk profile of new applications.

## Scenario 

You’re part of the growing security team at a company for sneaker enthusiasts and collectors. The business is preparing to launch a mobile app that makes it easy for their customers to buy and sell shoes. 

You are performing a threat model of the application using the PASTA framework. You will go through each of the seven stages of the framework to identify security requirements for the new sneaker company app.

## Sneaker App Description

Our application should seamlessly connect sellers and shoppers. It should be easy for users to sign-up, log in, and manage their accounts. Data privacy is a big concern for us. We want users to feel confident that we’re being responsible with their information.

Buyers should be able to directly message sellers with questions. They should also have the ability to rate sellers to encourage good service. Sales should be clear and quick to process. Users should have several payment options for a smooth checkout process. Proper payment handling is really important because we want to avoid legal issues.

## App Components

The app will be exchanging and storing a lot of user data. These are some of the technologies that it uses:

- Application programming interface (API): An API is a set of rules that define how software components interact with each other. In application development, third-party APIs are commonly used to add functionality without having to program it from scratch.
- Public key infrastructure (PKI): PKI is an encryption framework that secures the exchange of online information. The mobile app uses a combination of symmetric and asymmetric encryption algorithms: AES and RSA. AES encryption is used to encrypt sensitive data, such as credit card information. RSA encryption is used to exchange keys between the app and a user's device.
- SHA-256: SHA-256 is a commonly used hash function that takes an input of any length and produces a digest of 256 bits. The sneaker app will use SHA-256 to protect sensitive user data, like passwords and credit card numbers.
- Structured query language (SQL): SQL is a programming language used to create, interact with, and request information from a database. For example, the mobile app uses SQL to store information about the sneakers that are for sale, as well as the sellers who are selling them. It also  uses SQL to access that data during a purchase.

---

## PASTA Threat Model Investigation – Sneaker App

This investigation applies the Process for Attack Simulation and Threat Analysis (PASTA) framework to assess the security posture of a mobile app developed by a sneaker company. The app facilitates buying and selling shoes, handles sensitive user data, and processes financial transactions. The activity emphasizes threat modeling as a proactive strategy to identify vulnerabilities and implement effective security controls before launch.

## My Contributions

- Defined business objectives including secure transactions and regulatory compliance (PCI-DSS, GLBA)
- Prioritized SQL as a high-risk technology due to its role in data handling and injection exposure
- Identified threats such as SQL injection and session hijacking based on app architecture
- Analyzed vulnerabilities including lack of prepared statements and broken API tokens
- Proposed layered security controls: SHA-256, incident response, password policy, least privilege
- Synthesized findings across all seven PASTA stages into a structured, rubric-aligned format

## Reflection

This activity deepened my understanding of how threat modeling frameworks like PASTA guide security analysis from business goals to technical safeguards. By evaluating technologies, mapping threats, and proposing controls, I strengthened my ability to think like an attacker while defending like an analyst. The exercise also reinforced the importance of secure coding, input validation, and access control in protecting user data and maintaining trust.

---

## Screenshot of Completed Pasta Worksheet, Sample of Data Flow Diagram & Attack Tree
![PASTA FRAMEWORK](images/image/pasta-threat-model-framework.png)
> This image captures the full response submitted as part of the Google Cybersecurity Certificate PASTA Framework Activity on the Sneaker App.


<img width="596" height="784" alt="43" src="https://github.com/user-attachments/assets/ee822633-9ff5-4149-8a4b-713f58f65af0" />
<img width="604" height="776" alt="44" src="https://github.com/user-attachments/assets/0f75e8b1-edfc-4f0d-9d11-925996760663" />
<img width="1032" height="566" alt="45" src="https://github.com/user-attachments/assets/0606de9b-1a10-493c-9ef1-4e3e3f25c491" />
<img width="1021" height="563" alt="46" src="https://github.com/user-attachments/assets/9c1cccad-8310-42f3-b87d-a9a78f00dc04" />
