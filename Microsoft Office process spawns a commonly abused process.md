# Description
Microsoft Office process spawns a commonly abused process with an uncommon command
# Attacker's Goals
An attacker attempts to gain code execution via a phishing document.
# Investigative Actions
Check the source of the document (received by mail or loaded locally).
Investigate the child processes for malicious activity and network connections to an external host.
