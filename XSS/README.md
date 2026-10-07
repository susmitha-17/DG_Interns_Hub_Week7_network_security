**Reflected XSS**

Description:
Tested Reflected Cross-Site Scripting (XSS) in DVWA at Low security level using Burp Suite.

Payload:

<script>alert(1)</script>

Result:
The JavaScript payload executed successfully and displayed an alert, confirming reflected XSS.

Remediation:
Apply proper input validation and output encoding. Use secure security headers such as Content-Security-Policy (CSP).
