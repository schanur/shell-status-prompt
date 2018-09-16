# shell-status-prompt
Get a nice summary line after each command you run on your shell.

## Features
   * Runs under Zsh and Bash.
   * Show userspace and kernel time of all programs that you run.
   * Show current pid of shell and tty.
   * In case of failure/suspend/etc, give the signal name and the exit code.
   * No external dependencies.

## How it looks like
![Alt text](/screenshot/screenshot_1_crop.png?raw=true "")


## Installation
   * Clone this repository or download and entract the snapshot to a location readable to you:
     git clone https://github.com/schanur/shell-status-prompt.git
     source "/path/of/this/repo/shell-status-prompt.sh"
   * Add the following line to the end of your .bashrc or .zshrc file:

You are done. You see your new status line after you restart your shell session.

## Contribution
I am looking for a better (shorter) and more creative name. Maybe you have a good idea.
Features missing? Give me a hint or implement it yourself and create a pull request.
If you like it (or even if you don't), a short feedback would be nice.


Thanks!

Björn Griebenow
