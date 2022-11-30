# Description
When an add-on is running inside Protected Mode attempts to launch a broker process (or any other program), the ElevationPolicy Registry key is checked to determine how the process should be launched. Internet Explorer will run a broker process with higher rights that can use the current user's permissions to take actions that would otherwise be prohibited when rendering content inside the Protected Mode sandbox. https://blogs.msdn.microsoft.com/ieinternals/2009/11/30/understanding-the-protected-mode-elevation-dialog/.
# Attacker's Goals
When an add-on is running inside Protected Mode attempts to launch a broker process, this key is checked to determine how the process should be launched.
Attackers may change this value to make the process launch with higher privileges.
# Investigative Actions
Check whether the injecting process is benign, and if this was a desired behavior as part of its normal execution flow.
