# Description
Kerberos traffic is usually performed by a standard set of privileged processes through designated ports. The endpoint had a non-standard process communicating over ports normally used by Kerberos. An attacker might be moving laterally by using tools that implement a custom version of the Kerberos protocol.
# Attacker's Goals
This might be symptomatic of an attacker's lateral movements. The attacker could be:
using a custom protocol implementation that offers malicious functionality
Using the well-known Kerberos port with a different protocol to evade detection. Either way, the attacker's goal is to gain access to another endpoint on your network. The attacker could also be surveying your network by performing service scans over the well-known SMB or Kerberos ports.
# Investigative Actions
Make sure the process is not a scanner that implements its version of the protocol, and that the scanner use is for sanctioned purposes. For example, nmap enumerating SMB.
Make sure the process is not a sanctioned security product that creates standalone binaries for its use. For example, Illusive Network honeypots.
Investigate the process to see if the high-level language used to implement the application is the source of the alert. Some high-level programming languages provide their protocol implementations. For example, Java uses its Kerberos implementation.
Examine the endpoint to see if it is infected with malware. If the parent-child chain of initiating processes has been infiltrated with a malicious replacement, then that replacement could be known malware.
