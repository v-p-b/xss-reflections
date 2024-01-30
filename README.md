Reflections on Reflected XSS
============================

This repository tracks real-world incidents where **[reflected XSS](https://portswigger.net/web-security/cross-site-scripting/reflected)** was exploited. PR's welcome!

We don't track:

* [Stored XSS](https://portswigger.net/web-security/cross-site-scripting/stored) casued by server-side or frontend code.


The List
--------

### Apache.org - April, 2010.

> Combining a cross-site scripting (XSS) vulnerability with a TinyURL redirect, hackers successfully broke into the infrastructure for the open-source Apache Foundation in what is being described as a "direct, targeted attack."

Reference: https://www.zdnet.com/article/apache-org-hit-by-targeted-xss-attack-passwords-compromised/ ([archived](https://web.archive.org/web/20170221223703/https://www.zdnet.com/article/apache-org-hit-by-targeted-xss-attack-passwords-compromised/))


### Zimbra 0-day used to target international government organizations - November, 2023.

> TAG first discovered the 0-day, a reflected cross-site scripting (XSS) vulnerability, in June when it was actively exploited in targeted attacks against Zimbra’s email server.

Reference: https://blog.google/threat-analysis-group/zimbra-0-day-used-to-target-international-government-organizations/ ([archived](https://web.archive.org/web/20240112182056/https://blog.google/threat-analysis-group/zimbra-0-day-used-to-target-international-government-organizations/))
