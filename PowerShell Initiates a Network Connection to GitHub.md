# Description
PowerShell initiates a Network Connection to GitHub with an uncommon command line. This may have legitimate uses, but this technique is frequently used by attackers to serve malicious payloads.
# Attacker's Goals
Download a second stage payload for execution.
# Investigative Actions
Check if the initiator process is malicious.
Check for additional file/network operations by the same PowerShell instance.
