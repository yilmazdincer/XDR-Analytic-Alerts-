# Description
A docker contained executable from a mounted share was executed on a host. Running a contained executable is highly dangerous and atypical.
# Attacker's Goals
Gain high privileged command execution on host machine via one of its running containers.
# Investigative Actions
Check what actions were made after the suspicious file execution.
Investigate the contained process and its process tree.
