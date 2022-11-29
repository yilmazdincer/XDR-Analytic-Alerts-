# Description
A Microsoft Office process spawned a commonly abused process with a full command (not a script), this is a typically malicious behavior
# Attacker's Goals
An attacker is trying to gain code execution on the host.
# Investigative Actions
Check whether the command line executed is benign or normal for the host and/or user performing it. For example, employees working in finance may have legitimate use cases for complex Excel commands.
