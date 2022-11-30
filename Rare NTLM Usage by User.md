# Description
Rare authentication by user account to host via NTLM. The user has not authenticated with NTLM in the past 30 days. This may be indicative of downgrade attacks from Kerberos to NTLM.
# Attacker's Goals
The attacker is attempting to move laterally within a compromised network.
# Investigative Actions
Verify any successful authentication for the user account referenced by the alert, as these can indicate the attacker managed to use the stolen credentials.
