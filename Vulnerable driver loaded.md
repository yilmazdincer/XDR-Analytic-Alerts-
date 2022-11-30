# Description
A new and uncommon driver that is vulnerable was loaded. Attackers may install a legitimate kernel driver and exploit its vulnerability to gain kernel access.
# Attacker's Goals
Gain code execution on the host kernel.
# Investigative Actions
Check whether the driver was installed by IT / User.
Check if the host has the device of the driver - driver for Lenovo and the PC host brand is Asus.
Check driver file creation time and if in that time legitimate operations occur.
