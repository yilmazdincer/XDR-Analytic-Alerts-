# Description
An administrator account attempted to authenticate using NTLM to a target an excessive number of times in a short period. * This may indicate an NTLM brute-force attack.
# Attacker's Goals
The attacker attempts to gain access to the administrator accounts.
# Investigative Actions
Verify any successful authentication by the user account referenced by the alert, as these can indicate the attacker managed to guess the credentials.
