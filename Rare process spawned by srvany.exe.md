# Description
Unusual process spawned by srvany.exe, which allow applications to run as services with system privileges, this might be an indication of malicious local or remote code execution
# Attacker's Goals
Execute malware on the host in a manner that doesn't leave event logs within the system.
# Investigative Actions
Validate if the binary that srvany.exe executed is malicious.
Track down the source of the srvany.exe binary and the executed process.
Validate if this is a legitimate software installed by IT.
