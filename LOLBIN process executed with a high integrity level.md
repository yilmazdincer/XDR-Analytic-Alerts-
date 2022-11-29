# Description
A process spawned a suspicious LOLBIN process with a higher/system integrity level. The LOLBIN process spawned with an uncommon command line. This may be an indication of malicious code execution to gain privileges.
# Attacker's Goals
An attacker may attempt to gain higher privileges.
# Investigative Actions
Check whether the command line executed is benign or normal for the host and/or user performing it. Investigate the endpoint to determine if it's a legitimate process that is supposed to run with privileges.
