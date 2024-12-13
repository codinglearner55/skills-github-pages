---
title: "http redirects"
date: 2024-12-12
---
today on kodekloud we looked at how to perform simple redirects on apache. We configured temporary(302) and permanent(301) redirects using the redirect keyword in additional *.conf file created in /etc/httpd/conf.d. We also eventually realized that the order the redirects are placed can affect whether or not the redirects work correctly. 

