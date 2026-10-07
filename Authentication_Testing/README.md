Authentication Testing

Objective: Test login authentication using Burp Suite on the local DVWA lab.

Tested invalid credentials: admin / wrongpassword → Login failed.
Tested default credentials: admin / password → Login successful.
Observed successful authentication response with HTTP/1.1 302 Found.
Identified the use of a PHP session cookie after successful login.

Finding: Default/weak credentials can allow unauthorized access.
