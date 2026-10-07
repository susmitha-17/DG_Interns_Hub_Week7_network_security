**Parameter Tampering**

Description:
Tested parameter manipulation in DVWA using Burp Suite Repeater by modifying request parameters such as security and ip. The server accepted the modified values, demonstrating insufficient server-side validation.

Impact:
Attackers may modify parameters to alter application behavior or bypass intended restrictions.

Recommendation:
Implement strict server-side input validation and authorization checks for all user-controlled parameters.
