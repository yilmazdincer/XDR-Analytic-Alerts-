# Description
An attacker might leverage Microsoft signed processes loading modules from non-standard paths to load malicious code into trusted processes.
# Attacker's Goals
An attacker is attempting to load untrusted code into trusted contexts to avoid detection, persist or escalate privileges.
# Investigative Actions
Investigate the loaded module and verify if it is malicious.
