# Description
Security Support Provider (SSP) exposes a number of callbacks to be invoked during certain authentication and authorization events. An attacker may register SSP to try and gain access to clear text passwords.
# Attacker's Goals
Gain clear text passwords and persistency in the network.
# Investigative Actions
Audit the specific key values to verify that the additional values are trusted.
