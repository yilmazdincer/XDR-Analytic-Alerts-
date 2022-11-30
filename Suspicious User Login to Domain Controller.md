# Description
A normal user account has successfully logged on to a Domain Controller (DC), generating a Windows Event Log. This may be a sign of DC and Active Directory (AD) compromise.
# Attacker's Goals
A malicious user may attempt to access a domain controller to access and control Active Directory.
# Investigative Actions
Ensure that the user is not a Domain Admin account. By default, Administrator groups have permission to access the domain controller.
Check if the user is a service account that accesses a domain controller as part of its normal behavior.
Verify that the user is not authenticating to group policy.
