# Description
A contained process was executed with a suspicious GitHub url in the command line. This may be a legitimate use, but this technique is frequently used by attackers to download malicious payloads.
# Attacker's Goals
Download a second stage payload for execution.
# Investigative Actions
Check if the initiator process is malicious.
Check the user activity on the same container in that time.
Check if the container is a development container.
Check if this installation was related to more installations in the same time.
Check for additional file/network operations by the same process instance.
