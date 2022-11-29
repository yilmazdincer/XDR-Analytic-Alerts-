# Description
A user added a new Windows Firewall rule. Adding a firewall rule may indicate an attempt to bypass controls limiting network usage or to disrupt network communications.
# Attacker's Goals
Firewall rules determine what traffic your firewall will block or allow. A malicious insider might want to change these rules in an attempt to bypass network limitations or disrupt network communication.
# Investigative Actions
Check for any other suspicious activity related to the host and the user involved in the alert.
Check Windows Defender Firewall with Advanced Security for a new rule that was added.
Check if the new rule was added to different machines as well.
