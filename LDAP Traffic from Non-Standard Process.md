# Description
LDAP traffic is usually performed by a standard set of processes. The endpoint had a non-standard process communicating over ports normally used by LDAP. This may be indicative of Active Directory domain enumeration, which may be used during attacks against the organization.
# Attacker's Goals
An attacker is attempting to enumerate Active Directory.
# Investigative Actions
Make sure the process is not a scanner that implements its version of the protocol, and that the scanner use is for sanctioned purposes. For example, nmap enumerating LDAP.
Make sure the process is not a sanctioned security product that creates standalone binaries for its use. For example, Illusive Network honeypots.
Investigate the process to see if the high-level language used to implement the application is the source of the alert. Some high-level programming languages provide their protocol implementations.
Examine the endpoint to see if it is infected with malware. If the parent-child chain of initiating processes has been infiltrated with a malicious replacement, then that replacement could be known malware.
