# Description
An unpopular process accessed clipboard content by calling the GetClipboardData API function. This behavior may indicate potential threats such as a keylogger or a RAT.
# Attacker's Goals
Attackers can monitor clipboard as another way for credential gathering or to collect more user data over time for espionage purposes.
# Investigative Actions
Check if the process has a user interface (a visible window).
Check if the process is a known user application that was updated recently.
