# Practice: Modifying the `.bashrc` File in Ubuntu

## Objective

In Ubuntu, `.bashrc` is a crucial startup file used for configuring user-specific settings for terminal sessions, such as aliases, functions, and shell options. This tutorial aims to provide a practical walk-through to demonstrate how modifications in the `.bashrc` file can impact your shell environment. We will be making a series of changes, each with its distinct purpose and effect.

### Table of Changes and Impact
As a practice you need to make the following changes to the `.bashrc` file to have the impact listed in the table below
| Change                             | Impact                                                                            |
| ---------------------------------- | --------------------------------------------------------------------------------- |
| `export HISTCONTROL=ignoredups`    | Ignores duplicate commands in the history, displaying only unique commands.       |
| `export HISTSIZE=1000`             | Sets the maximum number of commands to be stored in the history to 1000.          |
| `alias l.='ls -d .* --color=auto'` | Creates a shortcut `l.` to list only hidden files with colorized output.          |
| `alias ll='ls -l --color=auto'`    | Creates a shortcut `ll` for a long-format listing of files with colorized output. |

