# Description
A single host tried to perform an unusual amount of login attempts using NTLM in a short period of time. This may be indicative of a NTLM password spray attack.
# Attacker's Goals
The attacker may attempt to guess user credential by password spray attack over multiple machines.
# Investigative Actions
Verify any successful authentication made by one of the user accounts referenced by the alert, as these may indicate the attacker managed to guess the credentials.
