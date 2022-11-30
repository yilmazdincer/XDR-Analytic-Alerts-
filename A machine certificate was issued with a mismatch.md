# Description
A machine certificate was issued with a mismatch between the requester and the subject
# Attacker's Goals
An attacker may attempt to exploit the Active Directory Certificate Services to escalate privileges to a domain controller machine account.
# Investigative Actions
Check who owns the certificate requester account.
Check if the requester DNS name attribute was changed recently.
Investigate actions done by the requester, and its owner.
Check for possible DCSync alerts.
