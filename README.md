# PowerShell Cheat Sheet

A cheat sheet for PowerShell and Windows commands.

Find process ID using port
`netstat -aon | findstr "5000"`

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

$PSVersionTable PowerShell and OS version
