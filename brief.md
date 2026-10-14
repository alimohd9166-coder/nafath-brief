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

On the internet, BGP helps networks choose routes. In a BGP hijack, someone falsely announces IP addresses that belong to another network. Other networks may trust the announcement and send traffic the wrong way. RPKI uses signed Route Origin Authorizations (ROAs) to check which Autonomous System (AS) is allowed to announce an IP prefix. Networks can reject invalid routes to reduce hijacks. However, RPKI origin validation does not check the full AS path, so it cannot stop every attack.

Resource: RFC 6811 - BGP Prefix Origin Validation - https://www.rfc-editor.org/rfc/rfc6811

## Cybersecurity

Log4Shell (CVE-2021-44228) was a serious weakness in Apache Log4j, a Java logging library used by many applications. In affected versions, attackers could put special text into information that gets logged. The JNDI lookup feature could then load and run malicious code from an attacker-controlled server. It was rated critical, with a 10.0 CVSS score, because remote code execution could happen without a login. Apache released fixed versions, and organizations needed to update their vulnerable Log4j software.

Resource: Apache Logging Services - Security - https://logging.apache.org/security.html

## Data

An SBOM, or Software Bill of Materials, is like an ingredient list for software. It tells a company which components are inside an application, so vulnerable libraries can be found more quickly. The NTIA's 2021 minimum elements include seven data fields: supplier name, component name, component version, other unique identifiers, dependency relationship, author of the SBOM data, and timestamp. This helps companies understand software supply chain risks and identify which components might need security updates.

Resource: NTIA - The Minimum Elements for an SBOM - https://www.ntia.doc.gov/files/ntia/publications/sbom_minimum_elements_report.pdf

## Misconception in My Track

## Open Question

