# Technical Analysis of Log4Shell (CVE-2021-44228)

#### Video Presentation
- **YouTube Link:** https://youtu.be/8KvswqvtuBY

## Overview
This project delivers a comprehensive technical analysis of **Log4Shell (CVE-2021-44228)**, a critical Remote Code Execution (RCE) vulnerability in the Apache Log4j2 logging framework (CVSS 10.0 Critical).

## Key Topics Covered
1. **Vulnerability Overview**: Analysis of Log4j2 and the CVSS 10.0 rating.
2. **Exploitation Mechanism**: JNDI lookup handling and LDAP vector parsing (`${jndi:ldap://...}`).
3. **Attack Flow**: Step-by-step progression from payload injection to remote code execution.
4. **Supply Chain Impact**: Enterprise software exposure and widespread automation threats.
5. **Mitigation & Defense**: Log4j 2.17.0+ patching, JVM flag restrictions, and WAF rules.

## Author
- **Name:** Oussama Hajji
- **GitHub:** Developer-Dynamo
- **edX Username:** oussama1152001
