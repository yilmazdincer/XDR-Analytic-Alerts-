# Description
A domain controller has initiated an SMB connection to another host. The domain controllers usually communicate over SMB only with other domain controllers. An attacker can abuse such sessions for relay attacks.
# Attacker's Goals
An attacker is attempting to steal credentials and move laterally within a network.
# Investigative Actions
Check if the destination is domain controller, if it is, exclude it.
Look for earlier connections to the DC which may cause it to initiate the session.
