# shell_capture

## Usage
> This cli template shows the date and time in the terminal

shell_capture

## Description

```
This is a template CLI application, which can be used as a boilerplate for awesome CLI tools written in Go.
This template prints the date or time to the terminal.
```
## Examples

```bash
cli-template date
cli-template date --format 20060102
cli-template time
cli-template time --live
```

## Flags
|Flag|Usage|
|----|-----|
|`--debug`|enable debug messages|
|`--disable-update-checks`|disables update checks|
|`--raw`|print unstyled raw output (set it if output is written to a file)|

## Commands
|Command|Usage|
|-------|-----|
|`shell_capture completion`|Generate the autocompletion script for the specified shell|
|`shell_capture date`|Prints the current date.|
|`shell_capture help`|Help about any command|
|`shell_capture time`|Prints the current time|
# ... completion
`shell_capture completion`

## Usage
> Generate the autocompletion script for the specified shell

shell_capture completion

## Description

```
Generate the autocompletion script for shell_capture for the specified shell.
See each sub-command's help for details on how to use the generated script.

```

## Commands
|Command|Usage|
|-------|-----|
|`shell_capture completion bash`|Generate the autocompletion script for bash|
|`shell_capture completion fish`|Generate the autocompletion script for fish|
|`shell_capture completion powershell`|Generate the autocompletion script for powershell|
|`shell_capture completion zsh`|Generate the autocompletion script for zsh|
# ... completion bash
`shell_capture completion bash`

## Usage
> Generate the autocompletion script for bash

shell_capture completion bash

## Description

```
Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:

	source <(shell_capture completion bash)

To load completions for every new session, execute once:

#### Linux:

	shell_capture completion bash > /etc/bash_completion.d/shell_capture

#### macOS:

	shell_capture completion bash > /usr/local/etc/bash_completion.d/shell_capture

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion fish
`shell_capture completion fish`

## Usage
> Generate the autocompletion script for fish

shell_capture completion fish

## Description

```
Generate the autocompletion script for the fish shell.

To load completions in your current shell session:

	shell_capture completion fish | source

To load completions for every new session, execute once:

	shell_capture completion fish > ~/.config/fish/completions/shell_capture.fish

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion powershell
`shell_capture completion powershell`

## Usage
> Generate the autocompletion script for powershell

shell_capture completion powershell

## Description

```
Generate the autocompletion script for powershell.

To load completions in your current shell session:

	shell_capture completion powershell | Out-String | Invoke-Expression

To load completions for every new session, add the output of the above command
to your powershell profile.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion zsh
`shell_capture completion zsh`

## Usage
> Generate the autocompletion script for zsh

shell_capture completion zsh

## Description

```
Generate the autocompletion script for the zsh shell.

If shell completion is not already enabled in your environment you will need
to enable it.  You can execute the following once:

	echo "autoload -U compinit; compinit" >> ~/.zshrc

To load completions for every new session, execute once:

#### Linux:

	shell_capture completion zsh > "${fpath[1]}/_shell_capture"

#### macOS:

	shell_capture completion zsh > /usr/local/share/zsh/site-functions/_shell_capture

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... date
`shell_capture date`

## Usage
> Prints the current date.

shell_capture date

## Flags
|Flag|Usage|
|----|-----|
|`-f, --format string`|specify a custom date format (default "02 Jan 06")|
# ... help
`shell_capture help`

## Usage
> Help about any command

shell_capture help [command]

## Description

```
Help provides help for any command in the application.
Simply type shell_capture help [path to command] for full details.
```
# ... time
`shell_capture time`

## Usage
> Prints the current time

shell_capture time

## Description

```
You can print a live clock with the '--live' flag!
```

## Flags
|Flag|Usage|
|----|-----|
|`-l, --live`|live output|


---
> **Documentation automatically generated with [PTerm](https://github.com/pterm/cli-template) on 05 April 2023**
