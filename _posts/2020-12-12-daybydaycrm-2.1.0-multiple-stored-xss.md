---
layout:     page
title:      FlarePoint DaybydayCRM - Multiple Stored XSS
date:       2020-12-12
author:     "Tufan Gungor"
permalink:  /0days
tags:       [xss, cross site scripting, exploit-db]
---
# FlarePoint DaybydayCRM - Multiple Stored XSS 
# Version : 2.1.0
# Date: 17.01.2020
# Vendor : [https://daybydaycrm.com](https://daybydaycrm.com)
# CVE : N-A

Description: Multiple stored cross-site scripting (XSS) vulnerabilities in FlarePoint DaybydayCRM, allow remote attackers to inject arbitrary web script or HTML. 
	1- New Lead - Title parameter,
	2- New User - Name parameter,
	3- New Project - Title parameter,
	4- New Client - Company Name parameter.

The user who can use these functions can steal other user cookies or redirect them to harmful sites.

# Payload : \<script>alert()\</script>

![Creating project](new_project.png)
![Trigger XSS](xss_trigger.png)
