# Description
A Kerberos service ticket (ST) was requested for an account with a spoofed sAMAccountName
# Attacker's Goals
Elevate privileges from standard domain user to domain admin.
# Investigative Actions
Check if the domain controller is patched or vulnerable to the attack.
Look for associated sAMAccountName rename events.
Follow actions by the account and if it performed a DCSync.
