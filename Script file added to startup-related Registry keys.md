# Description
An attacker may add a script file to the Registry "Run Keys" or the "Winlogon\Userinit" key to cause it to be executed as the user logs in.
# Attacker's Goals
Gain persistence using the legitimate Windows registry run key mechanism, which executes commands on user login or computer boot.
# Investigative Actions
Verify if the registered script is malicious.
Check if the installing software is a malicious binary or script.
