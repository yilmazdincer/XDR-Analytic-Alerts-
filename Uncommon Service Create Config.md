# Description
The Service Control command (sc.exe) is used to create, start, stop, query, or delete Windows services. Adversaries may attempt to use the command to execute and persist a binary, command, or script.
# Attacker's Goals
Evading security controls and possibly persisting malware.
# Investigative Actions
Check whether the service created, or the configuration change to an existing service, is benign or normal for the host and/or user performing it.
