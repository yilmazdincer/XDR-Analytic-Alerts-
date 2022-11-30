# Description
The mofcomp.exe WMI MOF compiled is used to compile code into the WMI repository that in turn may enable attackers to run scheduled or triggered code from the context of a Microsoft signed binary.
# Attacker's Goals
Run code via triggers from the context of the WMI executor.
# Investigative Actions
Verify if the executing process is suspicious.
Check if the MOF file being compiled has any malicious indicators within it.
