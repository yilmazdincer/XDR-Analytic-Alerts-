# Description
Sc.exe has the ability to start services on local and remote hosts. An attacker may abuse it to execute malicious services on a host.
# Attacker's Goals
Execute commands and run code on local or remote hosts.
# Investigative Actions
Check whether the service that was created via sc.exe is benign, and if this was a desired behavior as part of its normal execution flow.
