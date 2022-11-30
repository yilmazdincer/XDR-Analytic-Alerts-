# Description
The PowerShell host wsmprovhost.exe is a proxy process executed remotely through PowerShell when using Windows Remote Management (WinRM). It has executed a rare child process, which may indicate remote code execution abuse by an attacker.
# Attacker's Goals
Gain code execution on a remote host.
# Investigative Actions
Investigate the processes being spawned from Wsmprovhost.exe on the host for malicious indicators.
Correlate the initiator process (most likely PowerShell) to the source host and investigate it.
