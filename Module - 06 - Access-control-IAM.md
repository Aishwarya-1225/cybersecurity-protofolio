# Module 6: Access Control (IAM)

📖 Overview
Access Control ensures that only authorized users can access specific resources. Identity and Access Management (IAM) is a security framework that manages user identities and controls access to systems, applications, files, and devices. It follows the IAAA model: Identification, Authentication, Authorization, and Accountability. �

🎯 Learning Objective
*Understand IAM terminology.
*Learn the IAAA security model.
*Understand Identification, Authentication, Authorization, Auditing, and Accountability.
*Learn how access control protects information and systems.

📝 IAM Terminology
Subject
A person or process requesting access.
Example: Alex
Object
The resource being accessed.
Example: Password-protected Excel file

## Access Control
A security mechanism that determines how a subject can access an object.
Example: Alex enters the correct password to open the Excel file.

📂 Where is Access Control Applied?
*Information
*Systems
*Applications
*Facilities
*Devices (Mobile, Laptop, Servers)

**IAAA Model**
1️⃣ Identification
Identification is the process where a user claims an identity using a username, email ID, or employee ID.
Guidelines
User ID should be unique.
User ID should not expose sensitive information.
ID issuing process should be documented.
2️⃣ Authentication
Authentication verifies whether the claimed identity is genuine.
Authentication Factors
Something you know: Password, PIN
Something you have: OTP, Security Token, Smart Card
Something you are: Fingerprint, Face Recognition
Something you do: Typing pattern, Signature, Walking style
3️⃣ Authorization
Authorization determines what actions a user is permitted to perform after successful authentication.
Example
Admin → Create, Read, Update, Delete files
Normal User → Read-only access
4️⃣ Auditing
Auditing is the process of monitoring and recording user activities within a system. Audit logs help detect suspicious behavior and maintain security.
5️⃣ Accountability
Accountability ensures that every user is responsible for their actions performed within the system.
Example Scenario
Alex wants to open a password-protected Excel file.
Subject: Alex
Object: Excel File
Access Control: Password
Identification: Username
Authentication: Password Verification
Authorization: Permission to open/edit the file
Auditing: Login activity is recorded
Accountability: Alex is responsible for actions performed on the file.

✅ Key Takeaways
IAM controls user identities and resource access.
IAAA consists of Identification, Authentication, Authorization, Auditing, and Accountability.
Access control protects information, applications, systems, and devices from unauthorized access.
Strong authentication and proper authorization improve organizational security. �
GitHub Docs +1
