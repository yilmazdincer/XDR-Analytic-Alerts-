# Description
A possible abuse of Distributed File System Namespace Management (DFSNM)
# Attacker's Goals
An attacker can abuse the Distributed File System Namespace Management protocol to coerce an authentication from a DC.
This authentication can later be used for obtaining a DC certificate for DCSync.
# Investigative Actions
Check for a suspicious process on the initiator.
Check if the source host is a vulnerability scanner.
Look for unusual AD CS certificate requests.
Check for possible DCSync alerts.
