Reflections on Reflected XSS
============================

This repository tracks real-world incidents where **[reflected XSS](https://portswigger.net/web-security/cross-site-scripting/reflected)** was exploited. PR's welcome!

We don't track:

* [Stored XSS](https://portswigger.net/web-security/cross-site-scripting/stored) casued by server-side or frontend code.

While the primary focus is specifically on web applications, vulnerabilities affecting applications based on Electron and similar technologies can also provide interesting data points, so they will be tracked separately.

The List
--------

### Apache.org - April, 2010.

> Combining a cross-site scripting (XSS) vulnerability with a TinyURL redirect, hackers successfully broke into the infrastructure for the open-source Apache Foundation in what is being described as a "direct, targeted attack."

Reference: https://www.zdnet.com/article/apache-org-hit-by-targeted-xss-attack-passwords-compromised/ ([archived](https://web.archive.org/web/20170221223703/https://www.zdnet.com/article/apache-org-hit-by-targeted-xss-attack-passwords-compromised/))

This may be CVE-2010-1164 (only Jira XSS from 2010).

### Operation EmailThief: Active Exploitation of Zero-day XSS Vulnerability in Zimbra - February, 2022.

> Analysis of the emails from these spear phishing campaigns led to a discovery: the attacker was attempting to exploit a zero-day cross-site scripting (XSS) vulnerability in the Zimbra email platform.

Reference: https://www.volexity.com/blog/2022/02/03/operation-emailthief-active-exploitation-of-zero-day-xss-vulnerability-in-zimbra/ ([archived]())

This is CVE-2022-24682. Note that this XSS being _reflected_ is not explicitly stated, but the unauthenticated nature of the exploit and the fact that the advisory was not titled as "_Stored_ XSS" in the official [advisory](https://web.archive.org/web/20240112182055/https://wiki.zimbra.com/wiki/Zimbra_Security_Advisories) (like in other cases) points to this direction.

### Zimbra 0-day used to target international government organizations - November, 2023.

> TAG first discovered the 0-day, a reflected cross-site scripting (XSS) vulnerability, in June when it was actively exploited in targeted attacks against Zimbra’s email server.

Reference: https://blog.google/threat-analysis-group/zimbra-0-day-used-to-target-international-government-organizations/ ([archived](https://web.archive.org/web/20240112182056/https://blog.google/threat-analysis-group/zimbra-0-day-used-to-target-international-government-organizations/))

This is CVE-2023-37580.

Electron (and others)
---------------------

TODO

