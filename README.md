# Web Application Security Assessment

### About the Project

This repository contains the documentation and results of a web application security assessment performed against an intentionally vulnerable website. The objective of this project was to evaluate the application's security posture, identify common vulnerabilities, determine their risk levels, and recommend practical mitigation measures.

The assessment was carried out using industry-standard security tools and follows a structured vulnerability assessment methodology.

### Target Website

Website: http://testaspnet.vulnweb.com

Assessment Type: External Web Application Vulnerability Assessment


### Assessment Scope

The security review focused on examining the publicly accessible web application without performing any destructive or unauthorized exploitation.

Activities performed during the assessment include:

- Discovering exposed network services
- Identifying open ports
- Analyzing HTTP response headers
- Reviewing cookie security settings
- Evaluating transport layer security configuration
- Detecting common web security misconfigurations
- Classifying identified vulnerabilities based on severity
- Providing remediation recommendations for each finding

### Security Tools Used

Nmap

Used to perform network reconnaissance, discover open ports, identify running services, and collect server information.

OWASP ZAP

Used to conduct passive web application scanning, inspect HTTP responses, identify missing security headers, analyze cookie configurations, and detect common web security issues.

### Assessment Highlights

The assessment revealed several security weaknesses that could increase the application's exposure to common attacks.

Some of the major findings include:

- HTTP communication without HTTPS enforcement
- Missing browser security headers
- Server and framework information disclosure
- Insecure cookie configuration
- Missing CSRF protection
- Cross-Origin Resource Sharing (CORS) issues
- Mixed content detection
- Missing HTTP Strict Transport Security (HSTS)

No Critical or High severity vulnerabilities were identified during the assessment.

### Risk Distribution

Critical : 0

High : 0

Medium : 10

Low : 7

Informational : 1

### Repository Contents

- Vulnerability Assessment Report
- Nmap Scan Results
- OWASP ZAP Scan Results
- Supporting Screenshots
- Security Findings Report
- README File

### Skills Demonstrated

This project demonstrates practical knowledge in:

- Web Application Security
- Vulnerability Assessment
- Network Scanning
- Security Misconfiguration Analysis
- Risk Assessment
- Technical Documentation
- Security Reporting


