# Description
Attackers may mount a WebDAV drive over HTTPS to upload files to and download files from a compromised machine.
# Attacker's Goals
Attackers might use WebDAV as a C&C or exfiltration channel to evade detection and firewall rules.
# Investigative Actions
Check whether the initiator process is benign or normal for the host and/or user performing it.
Check whether additional malicious commands were executed from the same process.
