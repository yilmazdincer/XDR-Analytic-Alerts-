# Description
A compiled HTML help file wrote a script file to the disk. Compiled HTLM help files usually don't write script files to the disk. This behavior is often employed by malwares that leverage malicious CHM files to deliver a 2nd stage payload.
# Attacker's Goals
Deliver a 2nd stage payload or to avoid detection.
# Investigative Actions
Check whether the initiator process is benign or normal for the host and/or user performing it.
Check the file that was written to the disk for malicious activities.
