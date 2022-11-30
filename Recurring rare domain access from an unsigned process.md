# Description
An unsigned process is periodically connecting to an external domain that it and its peers rarely use. Access to this domain has occurred repeatedly over multiple days. This connection pattern is consistent with malware connecting to its command and control server for updates and operating instructions.
# Attacker's Goals
Communicate with malware running on your network to control malware activities, perform software updates on the malware, or to take inventory of infected machines.
# Investigative Actions
Identify the process contacting the remote domain and determine whether the traffic is malicious.
Look for other endpoints on your network that are also periodically contacting the suspicious domain.
