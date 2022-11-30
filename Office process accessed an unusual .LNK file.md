# Description
An attacker may embed a .LNK file in an Office document to execute malicious code.
# Attacker's Goals
Modify or create a shortcut to gain code or program execution.
# Investigative Actions
Check if the Office document contains a shortcut object.
Check the content (strings) of the document object for a .LNK shortcut.
Check the content of the shortcut.
