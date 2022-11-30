# Description
The net.exe command is used to add, delete, and otherwise manage the users on a computer. Adversaries may attempt to use the command to discover or add local and domain user accounts.
# Attacker's Goals
Attackers may attempt to use the command to discover or add local and domain user accounts. The created accounts are to gain additional access to endpoints within your network.
# Investigative Actions
Check whether the command line executed is benign or normal for the host and/or user performing it.
Check whether the user in the command line is an administrator or other sensitive account.
