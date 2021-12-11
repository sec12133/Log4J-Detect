# Log4J-Detect
This custom Snort IDS security monitoring rule can be used for detection of Log4J RCE attack detection.

Though originally written in snort rule format this can be ingested or used in all common content inspection systems with slight modifications.

This rule  basically looks for access attempts with user-controlled strings like “jndi from all known attacker IPs recorded till now by GreyNoise.

Do not forget to periodically review the new additions to the Attacker IPs here https://gist.github.com/gnremy/c546c7911d5f876f263309d7161a7217 and make necessary changes needed.
