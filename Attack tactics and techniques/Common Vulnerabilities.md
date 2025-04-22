# Common Vulnerabilities
## Description
This section is devoted to studying the most common vulnerabilities that attackers use to attack IT infrastructure, web applications, network services, and operating systems. Understanding the nature of these vulnerabilities allows research analysts to develop well-founded recommendations for eliminating them and preventing attacks.

Typical vulnerabilities include:
- Injection (SQL code injection, Command Injection, etc.) — injection of malicious commands into queries to databases or other systems.
- XSS (Cross-Site Scripting) — execution of malicious JavaScript code in the user's browser.
- CSRF (Cross-Site Request Forgery) — an attack on the trust of a web application to an authorized user.
- Insecure Direct Object Reference (IDOR) — incorrect access control to objects or data.
- RCE (Remote Code Execution) — code execution on a remote system through exploitation of a vulnerability.
- Path Traversal (Directory Traversal) — access to the server file system by manipulating file paths.
- Privilege Escalation — obtaining higher rights in the system due to operational errors or vulnerabilities.
- Brute Force and Credential Stuffing — attacks on credentials with the aim of guessing passwords or reusing compromised data.
- Misconfiguration — vulnerabilities that arise due to improper configuration of services or systems.
- Outdated Components — using old versions of software with known vulnerabilities.

## Practice
A research analyst applies knowledge of typical vulnerabilities to:
- Threat identification — understanding common mistakes allows one to predict attack vectors on a specific infrastructure.
- Formation of protection recommendations — an analyst can suggest measures to eliminate vulnerabilities or their safe exploitation.
- Analysis of incidents — understanding typical vulnerabilities helps to correctly interpret the actions of an attacker.
- Analysis of data from a monitoring system — signs of exploitation of popular vulnerabilities allow analysts to more quickly identify a potential threat.
- Preparation of analytical materials — articles and reports on attacks describing specific techniques and vulnerabilities help to highlight their risks and methods of protection.

## Connection with other knowledge
Typical vulnerabilities are closely related to:
- MITRE ATT&CK — many techniques from this framework include exploitation of typical vulnerabilities.
- Threat Intelligence — the analyst uses knowledge of new and popular vulnerabilities to identify threats.
- Threat Hunting — knowledge of signs of exploitation of typical vulnerabilities helps to build hypotheses about hidden threats.
- Incident analysis — understanding the mechanism of vulnerability exploitation helps to reconstruct the attack and develop protective measures.
- Working with Red and Blue Teams — the analyst must be able to correctly describe typical vulnerabilities and ways to neutralize them.

## How to improve
- Learn the OWASP Top 10: This list is regularly updated and reflects current threats to web applications.
- Analyze the CWE database: Studying the classification of weaknesses will allow you to better understand the nature of typical vulnerabilities.
- Learn the CVSS vulnerability assessment methodology: Understanding the assessment criteria will allow you to correctly analyze risks.
- Practice analyzing real incidents: Analysis of known cases of attacks on web applications, infrastructure, and services allows you to study the practical application of vulnerabilities.
- Get acquainted with vulnerability search systems: Learn to work with Shodan, Censys, Exploit-DB platforms, as well as automated vulnerability scanners.
- Analyze pentest reports: Studying real examples of found vulnerabilities will allow you to better understand their nature and methods of exploitation.
- Monitor new vulnerabilities: Regularly study reports on new CVE records, publications of Positive Technologies, Microsoft Security Response Center, and other authoritative sources.
- Practice identifying vulnerabilities on testbeds: This will help develop practical skills in recognizing and analyzing common security errors.
