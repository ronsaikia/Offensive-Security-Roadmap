# Penetration Testing
Penetration testing is an authorised, simulated cyberattack designed to evaluate the security posture of an information technology infrastructure. This process involves security professionals systematically assessing networks, applications, and systems to identify vulnerabilities that malicious actors could exploit. The primary objective is to proactively uncover weaknesses, evaluate the potential impact of a breach, and provide actionable remediation strategies to strengthen organisational defenses.

Think of it like hiring a security expert to try and break into your home. They will test the window latches, check for hidden spare keys, and pick the front lock—and then hand you a full list of how they got in and how to fix those entry points.

Also refer to the [Official OffSec Page](https://www.offsec.com/cyberversity/penetration-testing/) for a better understanding.

## Key Phrases of the process:
- **Reconnaissance (Information Gathering)**: Before we hack a machine, its important to know about it. This foundational phase defines the engagement scope, legal boundaries, and operational objectives. Security professionals systematically gather open-source intelligence (OSINT) regarding the target architecture, including domain details, mail servers, and network topology, to map the potential attack surface.

- **Scanning and Enumeration (Vulnerability Analysis)**: This phase utilizes automated tools and manual techniques to inspect the target infrastructure for active hosts, open ports, and running services. Security analysts examine how the target applications respond to various intrusion attempts to identify known vulnerabilities, misconfigurations, and outdated software versions.

- **Gaining Access (Exploitation)**: During this stage, testers actively exploit the identified vulnerabilities to bypass security controls and enter the target system. This phase mimics a real-world breach by leveraging software flaws, weak credentials, or configuration errors to demonstrate the technical feasibility of an unauthorized intrusion.

- **Maintaining Access (Persistence)**: Once an initial foothold is secured, testers attempt to establish a persistent presence within the environment to evaluate the system's long-term vulnerability. The goal is to determine if an attacker could remain undetected inside the infrastructure long enough to compromise sensitive data or deepen their access.

- **Covering Tracks and Clearing Evidence (Post-Exploitation)**: To mimic sophisticated threat actors, testers identify and temporarily alter system logs or artifacts generated during the assessment. This phase assesses the detection capabilities of the organization's security operations center (SOC) and ensures that the testing footprint does not leave the system exposed to actual malicious actors.

- **Analysis and Reporting (Remediation Documentation)**: The final phase consolidates all technical findings into a comprehensive, actionable report for stakeholders. This documentation categorizes discovered vulnerabilities by severity risk, outlines the exploitation methodologies used, and provides concrete remediation steps to fix the underlying security gaps.

## Types of Penetration Testing:
- **Black Box Testing**: The tester acts as an external attacker with no prior knowledge of the target's internal infrastructure.
- **White Box Testing**: The tester is provided with full knowledge of the target system, including network diagrams, source code, and credentials, simulating a comprehensive internal audit.
- **Gray Box Testing**: The tester is given partial knowledge or limited access to the network, simulating an insider threat or an attacker who has breached the initial perimeter.

## Few terms:
- **White hat hacker**: Also known as an ethical hacker, a white hat hacker employs the same methodologies and tools as malicious actors but operates with explicit legal consent. Their primary objective is to discover, document, and remediate security weaknesses before unauthorized adversaries can exploit them.
- **Black hat hacker**: Unlike ethical professionals, black hat hackers break into networks, applications, and digital infrastructures without legal consent. They leverage technical expertise to steal sensitive data, destroy information, deploy ransomware, or hold critical infrastructure hostage.
- **Grey hat hacker**: Grey hat hackers occupy a legal and ethical middle ground between white hat and black hat hackers. They regularly violate computer trespass laws by probing systems without the owner's explicit permission, yet they do not execute attacks to steal data, deploy ransomware, or cause intentional disruption.
- **Red Team**: A Red Team is an independent group that challenges an organization to improve its effectiveness by assuming an adversarial role or point of view. It is particularly effective in organizations with strong cultures and fixed ways of approaching problems. In infosec exercises, Red teamers are playing the role of attackers.
- **Blue Team**: A blue team is a group of individuals who perform an analysis of information systems to ensure security, identify security flaws, verify the effectiveness of each security measure, and to make certain all security measures will continue to be effective after implementation. As a result, blue teams were developed to design defensive measures against red team activities. In infosec exercises, Blue teamers are playing the role of defenders.
- **Infosec**:  Information security, which is the practice of preventing unauthorized access, use, disclosure, disruption, modification, inspection, recording or destruction of information. The information or data may take any form, e.g. electronic or physical. Infosec can also be a person who practices ethical security. [Learn more](https://en.wikipedia.org/wiki/Information_security)
- **Reverse Engineering**: It is the process of deconstructing a compiled software binary, hardware component, or system to analyze its internal structure, logic, and functionality without access to the original source code or design blueprints. [Learn more](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://www.geeksforgeeks.org/cybersecurity/what-is-reverse-engineering-technique-in-cybersecurity/&ved=2ahUKEwjf7evt-uCVAxW3keEIHfl3BTMQFnoECCgQAQ&usg=AOvVaw21qQG0jvL7srC5aKEoPVWg)
- **Social Engineering**: Social engineering is the psychological manipulation of individuals into performing actions or divulging confidential information.
