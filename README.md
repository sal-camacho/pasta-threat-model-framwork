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






## USB Attack Vector Investigation

This investigation documents a cybersecurity scenario involving a suspicious USB drive found in the parking lot of Rhetorical Hospital. It applies attacker mindset analysis and risk mitigation strategies to assess how personal and professional data stored on the device could be exploited. The activity emphasizes the importance of technical controls, employee awareness, and secure handling of removable media.

## My Contributions

- Identified sensitive contents including PII and internal HR documents  
- Applied attacker mindset to assess impersonation and phishing risks  
- Proposed layered controls: technical, operational, and managerial  
- Synthesized findings into a structured format aligned with AAA principles  

## USB Attack Vector Table

| **Category**         | **Details**                                                                                                                                                     |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Contents**         | - USB contained personal photos and HR files (e.g., new hire letter, shift schedule)  <br> - Included PII such as names, emails, and internal documents  <br> - Mixing personal and work files increases exposure risk |
| **Attacker Mindset** | - Files could be used to impersonate Jorge or target coworkers  <br> - Timesheets and HR data could enable phishing <br> - USB may have been staged to lure internal access |
| **Risk Analysis**    | - Malware like ransomware or remote access trojans could be hidden in .exe files  <br> - Plugging into a networked system could trigger compromise  <br> - Mitigations include disabling AutoPlay, enforcing MFA, RBAC, and employee training |

## Reflection

This activity reinforced the importance of treating unknown USB devices as potential threats. By analyzing attacker motivations and applying layered controls, I strengthened my understanding of physical attack vectors and internal security posture. The exercise also underscored how curiosity and careless handling of sensitive data can leave organizations vulnerable to significant security threats.

---

## Screenshot of Exercise Investigation & Contents of the USB Stick
![USB Attack Vector](images/image/usb-baiting-investigation.png)
> This image captures the full response submitted as part of the Google Cybersecurity Certificate Parking Lot USB activity.

<img width="632" height="816" alt="40" src="https://github.com/user-attachments/assets/be567192-330f-4368-aa2a-8ae135494600" />
<img width="638" height="551" alt="41" src="https://github.com/user-attachments/assets/2ad71da8-af60-4330-9560-4c0fc4a2dc2f" />
<img width="998" height="644" alt="42" src="https://github.com/user-attachments/assets/ca593559-0f7f-40a1-9f12-a8d281835691" />
