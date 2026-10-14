Version: NAFATH-V4
Track: Networking

## Overview
First of all, a national service provider's main concern should be security and data integrity across every part of its systems. Starting with mobile applications, if an app is not secure, attackers might trick customers with fake payment links and steal their money. Software must also be developed and updated carefully because one weak part can affect the entire service. Imagine someone stealing sensitive government data. It could create serious problems at a national level.

When it comes to AI, it is very important how it is trained and what data is given to it. If attackers manipulate that data, AI might fail to detect unusual network activity. Networks should connect devices securely and have backup systems. Cybersecurity protects these systems from attacks, while data security ensures only authorized people can access sensitive information.
## Software

Software configuration means the settings an application needs to work, such as database addresses, passwords and API keys. According to the Twelve-Factor App, configuration should be stored in environment variables instead of directly inside source code. Imagine a developer uploads code to public GitHub while a password is written there. Attackers could find it and access company systems. Separating them reduces this risk and lets settings change between testing and production without changing the code.

Resource: The Twelve-Factor App - Config - https://12factor.net/config

## AI

When it comes to AI, attackers can try to confuse the system in different ways. An evasion attack changes the input while AI is being used, so it might make the wrong decision. A poisoning attack changes its training data, so the AI learns from misleading information. Privacy attacks are different because they try to discover sensitive details from the model or its training data. This is why checking data and testing AI security is important.

Resource: NIST - Adversarial Machine Learning: A Taxonomy and Terminology of Attacks and Mitigations - https://doi.org/10.6028/NIST.AI.100-2e2025

## Mobile

Mobile applications need to be tested before people trust them with payments or personal information. OWASP MASVS stands for Mobile Application Security Verification Standard. It gives developers and security testers a set of security requirements to check whether a mobile app is safe. These checks cover things like secure data storage, login protection, encryption and network communication. For example, if a payment app sends data without proper protection, attackers could try to steal customers' information.

Resource: OWASP Mobile Application Security Verification Standard - https://mas.owasp.org/MASVS/

## Networking

## Cybersecurity

## Data

## Misconception in My Track

## Open Question

