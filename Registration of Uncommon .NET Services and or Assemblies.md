# Description
Regasm.exe and regsvcs.exe are used to register .NET COM assemblies, which are typically located in specific paths, attackers might leverage that to execute code within a Microsoft signed binary.
# Attacker's Goals
Load untrusted code into a trusted Microsoft context to evade detection.
# Investigative Actions
Verify if the loaded dll is known to be malicious.
Track down which process dropped the library being loaded.
Validate if the actions being done by the regasm.exe process are malicious.
