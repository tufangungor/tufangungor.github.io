---
title: 0day's
layout: page
permalink: /0days
---

# Dolibarr - Multiple XSS 
# Version : 10.0.6
# Date: 17.01.2020
# Vendor : [https://www.dolibarr.org/](https://www.dolibarr.org/)
# CVE : CVE-2020-7994

Description: Multiple cross-site scripting (XSS) vulnerabilities in Dolibarr ERP - CRM, allow remote attackers to inject arbitrary web script or HTML via the (1) label[libelle] parameter to /htdocs/admin/dict.php?id=3 page; the (2) name[constname] parameter on /htdocs/admin/const.php?mainmenu=home; (3) note[note] parameter on /htdocs/admin/dict.php?id=10; (4) zip[MAIN_INFO_SOCIETE_ZIP] parameter , email[mail] parameter on /htdocs/admin/company.php; (5) url[defaulturl] , field[defaultkey] , value[defaultvalue] parameters on /htdocs/admin/defaultvalues.php; (6) key[transkey], [transvalue] parameters on /htdocs/admin/translation.php; (7) [main_motd],[main_home] parameters on /htdocs/admin/ihm.php


# Payload : \<object data=data:text/html;base64,PHN2Zy9vbmxvYWQ9YWxlcnQoMik+>\</object>

![Payload](payload.png)
