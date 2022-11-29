# Description
A suspicious process queried AD CS objects via LDAP.
# Attacker's Goals
An attacker might look for AD CS servers, certificate templates or request certificates.
With the wrong setting or loose vulnerable templates or enabled enrollment, the attacker will be able to authenticate as users on the network.
# Investigative Actions
Check if the LDAP search query was allowed for the user (logged on at event time) or process.
Investigate the LDAP search query for any suspicious indicators.
