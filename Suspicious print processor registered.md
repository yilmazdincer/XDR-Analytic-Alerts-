# Description
The endpoint registered a new print processor, which may be used to gain persistence on the host by loading libraries into the time management service.
# Attacker's Goals
Gain persistence using the legitimate windows print processor mechanism, which loads libraries into Windows services.
# Investigative Actions
Verify if the registered library is malicious.
Check if the installing software is a malicious binary.
Check for any suspicious network activity from svchost.exe or spoolsv.exe.
