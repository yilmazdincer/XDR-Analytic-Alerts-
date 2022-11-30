# Description
A suspicious and unpopular LDAP search query was executed. This may be indicative of Active Directory domain enumeration, which may be used during attacks against the organization.
# Attacker's Goals
An attacker is attempting to enumerate Active Directory.
# Investigative Actions
Check if the process executes LDAP search queries as part of its normal behavior.
Investigate the LDAP search query for any suspicious indicators.
Determine whether the search query is generic. Wide search queries (often using wildcards) tend to be more suspicious. In our case, we are looking for targeted search queries.
