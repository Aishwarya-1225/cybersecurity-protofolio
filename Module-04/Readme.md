Module 04 – Attacks

Social Engineering
Definition:
Social engineering is the art of manipulating people into revealing confidential or sensitive information.
Real-Life Examples
1. Phishing Email
You receive an email that appears to be from your bank stating there has been unusual activity on your account. The email contains a link that looks like the bank's login page and asks you to log in to verify your account details. The attacker steals your credentials when you enter them.
2. Fake Friend Request
You receive a friend request on a social media platform from someone who appears to be your coworker. However, the profile picture and account details look suspicious. The account is fake and is attempting to gather personal information.

Categories of Social Engineering Attacks
1. Phishing
Phishing is the most common form of social engineering attack. It uses emails, messages, or fake websites to trick users into revealing sensitive information.
2. Spear Phishing
A targeted phishing attack aimed at a specific individual, organization, or group using personalized information.
3. Whaling
A phishing attack specifically designed to target high-profile individuals such as CEOs, executives, or government officials.
4. Vishing
Voice phishing (Vishing) uses phone calls or voice messages to trick victims into revealing confidential information.

Other Cyber Attacks
1. Typosquatting
A cyberattack where attackers register domain names with common spelling mistakes of popular websites to deceive users.
2. Zero-Day Attack
An attack that exploits a software vulnerability before the software vendor releases a security patch.
3. Replay Attack
An attacker captures valid communication between two parties and retransmits it later to gain unauthorized access or perform malicious actions.
4. Password-Based Attack
An attack that attempts to gain unauthorized access by stealing or cracking user passwords.
5.Brute Force Attack
A trial-and-error method in which attackers try every possible password combination until the correct one is found.
6.Dictionary Attack
An attack that attempts to guess passwords using a predefined list of common words and phrases.

# Module 4 – Application and Network Attacks

## Overview
Application and network attacks target software applications and network services to steal data, disrupt operations, or gain unauthorized access. Understanding these attacks helps in building secure systems.

---

# OSI Model Layers

1. Application Layer
2. Presentation Layer
3. Session Layer
4. Transport Layer
5. Network Layer
6. Data Link Layer
7. Physical Layer

---

# 1. Buffer Overflow Attack

## Definition
A buffer overflow occurs when more data is written into a fixed-size memory buffer than it can store. The extra data overwrites nearby memory, which may cause the program to crash or allow attackers to execute malicious code.

## Example
Imagine pouring water into a small container. Once the container is full, the extra water overflows. Similarly, when too much data is stored in a buffer, it overflows into adjacent memory.

## Causes
- Poor programming practices
- Programming language weaknesses
- Lack of input validation

## Prevention
- Validate user input
- Perform bounds checking
- Use memory-safe programming languages
- Keep software updated

---

# 2. Injection Attack

## Definition
An injection attack occurs when an attacker sends untrusted input to an application, causing it to execute unintended commands or queries.

## Impact
- Data theft
- Data loss
- Unauthorized access
- System compromise

## Types of Injection Attacks
- SQL Injection
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)

---

# SQL Injection (SQLi)

## Definition
SQL Injection is a vulnerability where attackers insert malicious SQL queries into application inputs to manipulate the database.

## Impact
- Database damage
- Unauthorized access
- Data leakage
- Data modification or deletion

## Prevention
- Parameterized queries
- Prepared statements
- Input validation
- Least privilege access

---

# Cross-Site Scripting (XSS)

## Definition
Cross-Site Scripting (XSS) is a vulnerability where attackers inject malicious JavaScript into web pages viewed by other users.

## Types
1. Stored (Persistent) XSS
2. Reflected (Non-Persistent) XSS

## Impact
- Session hijacking
- Cookie theft
- Website defacement
- Credential theft

## Prevention
- Input validation
- Output encoding
- Content Security Policy (CSP)

---

# Cross-Site Request Forgery (CSRF)

## Definition
CSRF tricks an authenticated user into performing unwanted actions on a trusted website without their knowledge.

## Impact
- Unauthorized transactions
- Account changes
- Money fraud
- Session misuse

## Prevention
- CSRF tokens
- SameSite cookies
- Re-authentication for sensitive actions

---

# Denial of Service (DoS)

## Definition
A Denial of Service (DoS) attack attempts to make a server or application unavailable by overwhelming it with excessive traffic from a single source.

## Impact
- Service interruption
- Resource exhaustion
- Poor system performance

---

# SYN Flood Attack

## Definition
A SYN Flood is a type of DoS/DDoS attack that exploits the TCP three-way handshake by sending numerous SYN requests without completing the connection.

## TCP Three-Way Handshake
1. Client → SYN
2. Server → SYN-ACK
3. Client → ACK

During a SYN Flood attack, the final ACK is never sent, leaving many half-open connections that consume server resources.

## Impact
- Server slowdown
- Service unavailability

---

# Man-in-the-Middle (MITM) Attack

## Definition
A Man-in-the-Middle attack occurs when an attacker secretly intercepts communication between two parties.

## Impact
- Data interception
- Data modification
- Credential theft
- Session hijacking

## Prevention
- HTTPS
- VPN
- Strong encryption
- Multi-Factor Authentication (MFA)

---

# Spoofing Attack

## Definition
Spoofing is the act of pretending to be a trusted source to deceive users or systems.

## Types
- IP Spoofing
- Email Spoofing
- DNS Spoofing
- Website Spoofing

## Impact
- Phishing
- Identity theft
- Unauthorized access
- Malware distribution

## Prevention
- Email authentication (SPF, DKIM, DMARC)
- DNS Security Extensions (DNSSEC)
- Firewalls
- User awareness training

---

# Key Takeaways

- Buffer Overflow attacks exploit memory vulnerabilities.
- SQL Injection targets databases.
- XSS injects malicious scripts into web pages.
- CSRF tricks authenticated users into performing unwanted actions.
- DoS attacks make services unavailable.
- SYN Flood attacks exploit the TCP handshake.
- MITM attacks intercept communications.
- Spoofing impersonates trusted identities to deceive users.

---

## Learning Outcome

After completing this module, I gained knowledge about common application and network attacks, their working principles, impacts, and security best practices to prevent them.
