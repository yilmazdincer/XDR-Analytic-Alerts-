# Description
Suspicious systemd timer activity, which may indicate an attempt to establish persistence.
# Attacker's Goals
An adversary may use systemd timers to execute malicious code at system startup or on a scheduled basis for persistence.
# Investigative Actions
Check the systemd timer file change and try to understand the impact of the systemd timers change.
