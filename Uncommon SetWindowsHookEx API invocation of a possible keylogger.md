# Description
A process installed a Windows desktop hook by calling the SetWindowsHookEx API function with an unpopular module. This behavior is commonly seen in keyloggers.
# Attacker's Goals
Attackers can monitor keyboard events as another way for credential gathering or to collect more user data over time for espionage purposes.
# Investigative Actions
Check if the process has a user interface (a visible window).
Check if the process has an option to set or modify keyboard hot-keys.
Check if the process is part of a remote control tool.
Check if the process is a known user application that was updated recently.
Check if the process is built with AutoHotkey and is known to the user.
If the process is a scripting engine or a hosting executable, check the actor process command line.
Investigate the endpoint if the process writes files to disk.
