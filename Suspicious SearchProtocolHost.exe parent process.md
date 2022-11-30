# Description
SearchProtocolHost.exe has been launched from a process that is different from SearchIndexer.exe This may indicate malicious activity (such as malware later being injected to it, or it being used for phantom DLL hijacking).
# Attacker's Goals
Gain code execution on the host and evade security controls.
# Investigative Actions
Check whether the executing process is benign, and if this was a desired behavior as part of its normal execution flow.
