# Vulnerabilities

## Systematic

### IRIS Standards Management (ISM) v2.1 SP1 89

#### Reflected Cross Site Scripting (XSS) in dialog information
The ISM application is vulnerable to unauthenticated reflected Cross Site Scripting (XSS). A user input is reflected directly in the web page, allowing a malicious user to conduct a Cross Site Scripting attacks against users of the application.

### IRIS WebForms

#### Lack of authentication to IRIS WebForms
The IRIS WebForms application and its functionalities can be accessed and used without any form of authentication.

#### Directory traversal
The IRIS WebForms application is vulnerable to directory path traversal attacks. By manipulating variables that reference files with "dot-dot-slash (../)" sequences and its variations, it is possible to list all the directories and check if a particular files exist.
