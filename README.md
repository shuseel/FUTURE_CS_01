# FUTURE_CS_01
Cyber Security Internship – Future Interns (2026)

This report details the findings of a comprehensive security assessment conducted on the target web application. Multiple critical vulnerabilities were identified, primarily SQL injection flaws, Cross-Site Scripting (XSS), and Cross-Site Request Forgery (CSRF) vulnerabilities on a low security level.

# Target Information
*	Application: DVWA (Damn Vulnerable Web Application) 
*	IP Address: 127.0.0.1/dvwa/
*	Web Server: Apache/2.4.65 (Debian)
*	Open Port: 80 (HTTP)

# Scope of Testing
*	Testing Scope: Passive scanning only, no exploitation or attacks should be performed, SQL Injection vulnerabilities across the LOW security level.
*	Methodology: Manual penetration testing following OWASP Testing Guide v4.2 and automated scanning using OWASP ZAP.
*	Testing Period: March 2026

# Tools Used
* Nmap (Service & Exposure Scan)
* OWASP ZAP (Passive Vulnerability Scan)
* Browser DevTools (Header & Client-Side Analysis)

# Key Findings
* No input sanitization allows direct SQL query manipulation.
* No input validation or output encoding implemented
* No protection against forged requests.
* Content Security Policy (CSP) Header Not Set
* Possible to view the directory listing
* SSL is not activated
* Hidden file found
* Missing Anti-clickjacking Header
* Cookie without SameSite Attribute
* In Page Banner Information Leak
* Server Leaks Version Information
* X-Content-Type-Options Header Missing

# Author
Shuseel Baral

Cyber Security Intern – Future Interns (2026)
  
  

  
