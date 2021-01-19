---
layout:     post
title:      FlarePoint DaybydayCRM - Multiple Stored XSS
date:       2020-12-12
author:     "Tufan Gungor"
category:   exploit
tags:       [xss, cross site scripting, exploit-db]
---
# FlarePoint DaybydayCRM - Multiple Stored XSS 
# Version : 2.1.0
# Date: 12.12.2020
# Vendor : [https://daybydaycrm.com](https://daybydaycrm.com)
# CVE : CVE-2020-35704, CVE-2020-35705, CVE-2020-35706, CVE-2020-35707

Description: Multiple stored cross-site scripting (XSS) vulnerabilities in FlarePoint DaybydayCRM, allow remote attackers to inject arbitrary web script or HTML. 
	1- New Lead - Title parameter,
	2- New User - Name parameter,
	3- New Project - Title parameter,
	4- New Client - Company Name parameter.

The user who can use these functions can steal other user cookies or redirect them to harmful sites.

# Payload : \<script>alert("project")\</script>

![Creating project](/images/new_project.png)
![Trigger XSS](/images/xss_trigger.png)
