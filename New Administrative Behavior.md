# Description
The endpoint performed new administrative actions, relative to its previously profiled behavior. It is possible that an endpoint will infrequently be used for administrative activities, so analytics is performed using logs collected over a long period of time, also comparing the activity to that of other endpoints. That is, if many endpoints are contacting the same destination with the same administrative activity, then this network activity is less likely to result in this alert.
An attacker may be operating on the host, probing other computers and moving laterally inside the network using a trusted computer and credentials. Attackers typically exhibit administrative behaviors when performing reconnaissance and lateral movement.
# Attacker's Goals
An attacker is using administrative functions to move from one endpoint to another, or to scan the network for new endpoints to attack.
# Investigative Actions
Investigate the endpoint to determine if it is legitimately being used for administrative functions.
