# Description
BITSAdmin.exe was used with a command-line that may indicate a malware trying to gain persistence on the machine.
# Attacker's Goals
Gain persistence using the legitimate bitsadmin 'setnotifycmdline' mechanism, which triggers process executions once a Bits job is done or fails.
# Investigative Actions
Check if the command line contains any malicious indicators.
Check if the parent process is suspicious.
Check if the command-line used to persist is malicious or references a malicious binary.
