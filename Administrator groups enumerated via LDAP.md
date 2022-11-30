# Description
An LDAP search query that collects information about administrators was executed. This may be indicative of Active Directory domain enumeration, which can be used to perform attacks against the organization.
# Attacker's Goals
An attacker is attempting to enumerate Active Directory.
# Investigative Actions
Check if the process executes LDAP search queries as part of its normal behavior.
Investigate the LDAP search query for any suspicious indicators.
