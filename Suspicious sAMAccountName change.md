# Description
The name of a machine account was changed to a sAMAccountName with a missing trailing dollar sign
# Attacker's Goals
Elevate privileges from standard domain user to domain admin.
# Investigative Actions
Check if the domain controller is patched or vulnerable to the attack.
Check if any associated TGTs or service tickets were granted.
Follow actions by the account and if it performed a DCSync.
