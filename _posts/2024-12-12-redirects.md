---
title: "kodekloud: http redirects"
date: 2024-12-12
---
today on kodekloud we looked at how to perform simple redirects on apache. We configured temporary(302) and permanent(301) redirects using the redirect keyword in additional *.conf file created in /etc/httpd/conf.d. We also eventually realized that the order the redirects are placed can affect whether or not the redirects work correctly. 

## Useful Links

## Apache Headers

https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers

https://www.iana.org/assignments/http-fields/http-fields.xhtml

https://html.spec.whatwg.org/multipage/document-lifecycle.html#x-frame-options

https://fetch.spec.whatwg.org/#x-content-type-options-header

https://linuxwizardry.com/how-to-enable-mod_headers-on-apache-in-ubuntu-22-04-a-step-by-step-guide/

https://techexpert.tips/apache/apache-add-header/ - short guide

https://blog.insiderattack.net/apache-security-configuring-secure-response-headers-e8a83b72ce5e - explanation


