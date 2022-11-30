# Description
The schtasks.exe command enables creating, deleting, querying, changing, running, and ending scheduled tasks on a local or remote computer. Adversaries may attempt to use the command to gain persistence on this host using scheduled tasks.
# Attacker's Goals
Attackers may attempt to use the command to gain persistence on the endpoint using scheduled tasks.
# Investigative Actions
Review the process that creates the schedule task.
Investigate the specific scheduled task execution chain.
