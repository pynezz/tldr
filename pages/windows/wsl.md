# wsl

> Manage the Windows Subsystem for Linux.
> More information: <https://learn.microsoft.com/windows/wsl/reference>.

- Start a Linux shell (in the default distribution):

`wsl {{shell_command}}`

- Run a Linux command without using a shell:

`wsl {{[-e|--exec]}} {{command}} {{command_arguments}}`

- Specify a particular distribution:

`wsl {{[-d|--distribution]}} {{distribution}} {{shell_command}}`

- List available distributions:

`wsl {{[-l|--list]}}`

- Export a distribution to a `.tar` file:

`wsl --export {{distribution}} {{path\to\distro_file.tar}}`

- Import a distribution from a `.tar` file:

`wsl --import {{distribution}} {{path\to\install_location}} {{path/to/distro_file.tar}}`

- Change the version of wsl used for the specified distribution:

`wsl --set-version {{distribution}} {{version}}`

- Shut down Windows Subsystem for Linux:

`wsl --shutdown`
