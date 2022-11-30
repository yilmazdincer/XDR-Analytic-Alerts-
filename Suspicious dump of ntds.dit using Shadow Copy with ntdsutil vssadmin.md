# Description
Attackers may attempt to dump the ntds.dit file, which stores all Active Directory account information, to later extract passwords and hashes from it.
# Attacker's Goals
Retrieve Active Directory data, to perform malicious activities such as lateral movement.
# Investigative Actions
Check the initiator process for additional suspicious activity.
