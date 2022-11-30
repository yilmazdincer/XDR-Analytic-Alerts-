# Description
A signed process that usually doesn't use DotNet loaded a common DotNet module
# Attacker's Goals
Adversaries may reflectively load DotNet code into a process to conceal the execution of malicious payloads.
# Investigative Actions
Investigate the actor processes for malicious activities.
Check for recent service installation that may load DotNet modules.
