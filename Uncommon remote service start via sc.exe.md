# Description
The Service Control command (sc.exe) is used to create, start, stop, query, or delete Windows services. Adversaries may attempt to use the command to execute and persist a binary, command, or script.
# Attacker's Goals
The Service Control command is used to create, start, stop, query, or delete Windows services. Attackers can use the command to attempt to execute and persist a binary, command, or script.
# Investigative Actions
Check whether the executed process is benign and if this was desired behavior as part of its normal execution flow.
Check the remote host for any evidence of the executed service and investigate it.
