# Description
A remote WMI command executed a binary proxy, the Windows Management Instrumentation (WMI) Provider Host wmiprvse.exe, which executed a rare child command line. Executing a rare child process can be an indication of remote code execution abuse by an attacker.
# Attacker's Goals
Gain code execution on a remote host.
# Investigative Actions
Investigate the processes being spawned from WmiPrvse.exe on the host for malicious indicators.
Correlate the RPC call from the source host and understand what initiated it.
