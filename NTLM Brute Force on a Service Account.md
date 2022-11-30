# Description
A service account attempted to authenticate to a target using NTLM an excessive number of times in a short period. * This may indicate a NTLM brute-force attack.
# Attacker's Goals
The attacker attempts to gain access to the service accounts.
# Investigative Actions
Verify any successful authentication by the user account referenced by the alert, as these can indicate the attacker managed to guess the credentials.
