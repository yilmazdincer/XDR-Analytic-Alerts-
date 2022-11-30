# Description
An unusual request to AWS Instance Metadata Service (IMDS) was made by a web service. An attacker might exploit a web vulnerability or service to execute this technique, such as SSRF
# Attacker's Goals
Extract sensitive AWS tokens to access restricted resources.
# Investigative Actions
Check which web service was exploited to carry the attack.
Check what other commands were executed via the web service or on the target machine.
Check the AWS instance profile attached to the victim machine and its permissions, to find out which resources may be affected.
