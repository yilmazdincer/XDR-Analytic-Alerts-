# Description
Cmdkey is a built-in Windows tool that can cache domain user credentials for use on specific target machines, Attackers can access cached user credentials using cmdkey /list.
# Attacker's Goals
Access cached user credentials.
# Investigative Actions
Check the initiator process for additional suspicious activity.
Check if the host is a shared host that multiple users credentials can be extracted from.
