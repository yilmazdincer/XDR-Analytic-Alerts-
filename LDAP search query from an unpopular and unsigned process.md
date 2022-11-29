# Description
An unpopular and unsigned process performed an LDAP search query. This may be indicative of LDAP enumeration.
# Attacker's Goals
An attacker is attempting to enumerate Active Directory.
# Investigative Actions
Check if the process executes LDAP search queries as part of its normal behavior.
Investigate the LDAP search query for any suspicious indicators.
Determine whether the search query is generic. Generic search queries (often using wildcards) tend to be more suspicious.
