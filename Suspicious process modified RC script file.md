# Description
A suspicious process modified an RC script file. These files allow system administrators to map and start custom services at startup for different run levels. This may be done to establish persistence.
# Attacker's Goals
Adversaries may establish persistence by modifying RC scripts, which are executed during a Unix-like system’s startup.
# Investigative Actions
Check the modified RC script file and try to understand the impact of the file modification.
