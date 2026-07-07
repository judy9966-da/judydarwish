# Metasploitable 2 – Assessment

## Overview
This assessment focuses on working with the intentionally vulnerable Metasploitable 2 machine to practice core penetration‑testing concepts in a controlled cybersecurity environment. The project includes preparing the virtual machine, identifying exposed services, analyzing weaknesses, and exploiting known vulnerabilities to demonstrate practical offensive security skills.

## Objectives
- Install and configure the Metasploitable 2 virtual machine  
- Discover active services and open ports  
- Identify outdated or insecure components  
- Exploit vulnerabilities that allow unauthorized access  
- Validate successful compromise through post‑exploitation steps  

## Assessment Summary
The Metasploitable 2 machine was successfully installed and configured inside a virtualized environment. After performing service enumeration, several weak and outdated services were identified. These weaknesses were leveraged to gain unauthorized access to the system.

Two major vulnerabilities were exploited:

### Telnet Default Credentials
The Telnet service was accessible and configured with default login credentials, allowing immediate user‑level access.

### VSFTPD 2.3.4 Backdoor
A known backdoor in the VSFTPD 2.3.4 FTP service enabled remote root access, resulting in full system compromise and the ability to perform post‑exploitation actions.

## Outcome
The assessment resulted in complete control over the Metasploitable 2 machine, demonstrating the risks associated with outdated services, weak configurations, and insecure protocols. The project highlights essential penetration‑testing skills and reinforces the importance of secure system configuration.
