# FUTURE_CS_Task01 — DVWA Web App Security Testing

## Summary 🎯
Performing security testing on a sample web application(DVWA) to identify vulnerabilities like SQL injection, XSS, and authentication flaws.

Target: DVWA (local lab via XAMPP)  
Tools: OWASP ZAP, Browser (proxy), DVWA modules  
Date: September 2025  
Author: Sasi Kumar Medabalimi

## Findings (Short) 🔍
1. SQL Injection — High  
2. Reflected XSS — Medium-High  
3. Stored XSS — High  
4. CSRF — Medium  
5. Command Injection — High  

## Deliverables 📚📑
- report.pdf (final export)
- screenshots
- logs/ (raw request/response text files)
- owasp-checklist.pdf (compliance checklist)

## Repo Structure 📏
```
FUTURE_CS_Task01/
├── README.md
├── Security report.pdf
├── owasp-checklist.pdf
|--   ZAP dvwa_report
├── screenshots/
│   ├── sqli_input_payload & result.png
│   ├── xss(r)_input_payload & result.png
│   ├── xss(s)_input_payload & result.png
│   ├── csrf_input_payload & result.png
│   └── cmd_injection_input_payload & result.png
|___    .......
└── logs/
    ├── sqli_Raw Request - Response.txt
    ├── Xss(r)_Raw Request - Response.txt
    ├── Xss(s)_Raw Request - Response.txt
    ├── csrf_Raw Request - Response.txt
    └── cmd_RAW Request - Response.txt
```

## Notes
- Tests were performed only on a local DVWA lab, never on production targets.  
- Each finding includes screenshots + raw requests as evidence.  
- The full report maps vulnerabilities to OWASP Top 10 and provides remediation advice.
