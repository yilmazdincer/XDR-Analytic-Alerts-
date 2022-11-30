# Description
The 'ipconfig' command is used to display TCP/IP network configuration information and refresh the Dynamic Host Configuration Protocol (DHCP) and Domain Name System (DNS) settings. Adversaries may use the command to discover network configuration details.
# Attacker's Goals
Attackers can use the ipconfig command to discover network configuration details.
# Investigative Actions
Check whether the initiator process is benign or normal for the host and/or user performing it.
Check whether additional discovery commands were executed from the same process.
