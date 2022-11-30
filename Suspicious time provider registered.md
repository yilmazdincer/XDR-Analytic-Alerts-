# Description
The endpoint time provider has been tampered, this change may be used to gain persistence on the host by loading libraries into the time management service.
# Attacker's Goals
Gain persistence using the legitimate windows time provider mechanism, which loads libraries into Windows services.
# Investigative Actions
Verify if the registered library is malicious.
Check if the installing software is a malicious binary.
Check for any network activity from a "svchost.exe -k LocalService" process that seems suspicious.
