# Description
Attackers may register a compromised host as a new DC to get other DCs to replicate data to it, and then push their malicious AD changes to all DCs.
# Attacker's Goals
Retrieve Active Directory data, to later be able to push out malicious Active Directory changes.
# Investigative Actions
Check whether the destination is a new domain controller or a host that syncs with ADFS or Azure AD.
