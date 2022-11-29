# Description
A contained executable from a mounted share initiated a suspicious outbound network connection. Running binaries from a mounted share is highly dangerous and not typical.
# Attacker's Goals
Gain high privileged command execution on host machine via one of its running containers.
# Investigative Actions
Check if the requested IP address is known or malicious.
Investigate the contained process and its process tree.
