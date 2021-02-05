# PowerShell Cheat Sheet

A cheat sheet for PowerShell and Windows commands.

# Help

| Command                    | Description                                    |
| -------------------------- | ---------------------------------------------- |
| `Get-Help Foo-Bar`         | Get help on the 'Foo-Bar' command              |
| `Get-Help Foo-Bar -Full`   | Get full help on the 'Foo-Bar' command         |
| `Get-Help Foo-Bar -Online` | Get help on the 'Foo-Bar' command in a browser |
| `Get-Command *foo*`        | Get all commands containing 'foo'              |
| `Get-Command -Module Foo`  | Get all commands from module 'Foo'             |

# Modules

| Command                     | Description                                   |
| --------------------------- | --------------------------------------------- |
| `Get-Module -ListAvailable` | List all modules                              |
| `Find-Module *foo*`         | Find all modules containing 'foo'             |
| `Install-Module Foo`        | Install module 'foo'                          |

# Variables

| Variable                    | Description                                   |
| --------------------------- | --------------------------------------------- |
| `$LastExitCode`             | The exit code from the last exited process    |
| `$PSVersionTable`           | PowerShell and OS version                     |

# Networking

| Variable                         | Description                                   |
| -------------------------------- | --------------------------------------------- |
| `netstat -aon \| findstr "5000"` | Find process ID using port                    |
