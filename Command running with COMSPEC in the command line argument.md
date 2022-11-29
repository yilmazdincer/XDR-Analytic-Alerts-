# Description
COMSPEC is an environmental variable that points to cmd.exe. Attackers may use this command to obfuscate their command and avoid detection
# Attacker's Goals
Attackers might use environment variables to try and avoid being detected and obfuscate their commands.
# Investigative Actions
Investigate the actor and the command line that executed with COMSPEC Verify that the command executed from a trusted source.
