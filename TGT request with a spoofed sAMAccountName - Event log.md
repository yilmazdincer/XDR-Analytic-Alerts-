# Description
A Kerberos authentication ticket (TGT) was requested for an account with a spoofed sAMAccountName
# Attacker's Goals
Elevate privileges from standard domain user to domain admin.
# Investigative Actions
Check if the domain controller is patched or vulnerable to the attack.
Look for associated sAMAccountName rename events.
Check if any associated service tickets were granted.
Follow actions by the account and if it performed a DCSync.
