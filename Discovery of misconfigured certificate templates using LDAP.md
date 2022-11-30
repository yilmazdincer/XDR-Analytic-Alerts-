# Description
An LDAP query searching for misconfigured certificate templates was executed.
# Attacker's Goals
An attacker can use misconfigured certificate templates for escalation and authentication.
# Investigative Actions
Check if the LDAP search query was allowed for the user (logged on at event time) or process.
Investigate the LDAP search query for any suspicious indicators.
