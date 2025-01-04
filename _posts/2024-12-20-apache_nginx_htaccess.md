---
title: "kodekloud: install and configure apache and nginx (as reverse proxy on same host)
date: 2024-12-20
---
Installed apache then nginx on the same host. Then configured nginx as a reverse proxy for apache on the same host. proxy_pass keyword was needed to enter the apache url to forward traffic to. (nginx.org docs)
Also in another lab we tried to configure .htaccess basic auth for a protected directory. Passed the lab check but was still probably incorrect since the protected directory could still be as if without any protection.
