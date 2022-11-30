# Description
Udev driver rule was modified with unusual pattern, might be used by adversaries to backdoor existing drivers.
# Attacker's Goals
Adversaries can use this technique to execute arbitrary commands once the machine boots.
# Investigative Actions
Check if the action was done using an automation service.
Check the rule modification content and look for any suspicious payloads.
Check if there are any other suspicious activities originated from the same machine/executing user.
