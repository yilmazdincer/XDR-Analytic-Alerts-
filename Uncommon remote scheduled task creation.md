# Description
The schtasks.exe command enables creating, deleting, querying, changing, running, and ending scheduled tasks on a local or remote computer. Adversaries may attempt to use the command to execute programs or persist malware on remote machines.
# Attacker's Goals
Attackers can attempt to use the command to execute programs or persist malware on remote endpoints.
# Investigative Actions
Investigate the initiator process and whether it should create remote tasks.
Investigate the scheduled task execution on the remote machine.
