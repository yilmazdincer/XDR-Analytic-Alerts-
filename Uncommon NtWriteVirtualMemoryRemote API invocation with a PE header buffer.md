# Description
A process wrote a PE header to another process by calling the NtWriteVirtualMemoryRemote API function.
# Attacker's Goals
Gain code execution on the host in the context of another process.
# Investigative Actions
Investigate the acting process for other malicious activities.
Check if the target process was injected and for anomalies in its behavior after this event.
