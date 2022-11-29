# Description
A potential persistence file was written to the startup folder.
# Attacker's Goals
Persistence on the host.
# Investigative Actions
Check if the file was written during an installation of a legitimate application (what other files were written by the process).
Check what program opens this file by the extension - Check the registry at HKEY_CLASSES_ROOT.[extension]\shell\[action]\command for the default application or command to execute.
