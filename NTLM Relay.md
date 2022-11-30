# Description
An NTLM NTProofStr was seen from more than one source. This indicates that NTLM authentication data has been relayed.
# Attacker's Goals
The attacker is attempting a man-in-the-middle NTLM relay attack to intercept authentication attempts and move laterally within an environment.
# Investigative Actions
Check that the alerted host is not a NAT or a proxy that duplicates traffic as part of its normal behavior.
Check if the protocols used are vulnerable to an NTLM relay attack (e.g. LDAP, SMB).
Ensure that SMB signing is enabled in the case of a possible SMB relay attack.
