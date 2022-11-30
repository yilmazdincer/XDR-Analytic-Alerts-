# Description
The endpoint registered a new active setup, which may be used to gain persistence on the host by loading libraries into the time management service.
# Attacker's Goals
Gain persistence using the legitimate windows active setup mechanism, which executes binary on system startup.
# Investigative Actions
Verify if the registered binary is malicious.
Check if the installing software is a malicious binary.
