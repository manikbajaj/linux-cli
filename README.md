# Linux Command Line For Developers Masterclass

# Navigate Repository Contents

- [Introduction To Linux](#introduction-to-linux)
- [The Linux File System](#the-linux-file-system)
- [Understanding Commands In Linux](#understanding-commands-in-linux)
- [Command Line Redirection](#command-line-redirection)
- [Mastering Shell Expansions](#mastering-shell-expansions)
- [Keyboard Tricks](#keyboard-tricks)
- [Linux Permissions](#linux-permissions)
- [Linux Processes](#linux-processes)
- [Linux Environment](#linux-environment)
- [Introduction To Vi](#introduction-to-vi)
- [Package Management](#package-management)
- [Storage Management In Linux](#storage-management-in-linux)
- [Networking In Linux](#networking-in-linux)
- [Searching For Files](#searching-for-files)
- [Archiving In Linux](#archiving-in-linux)
- [Bash Scripting](#bash-scripting)

## Introduction To Linux

| Sno | Lecture Title                                    | Notes |
| --- | ------------------------------------------------ | ----- |
| 1   | Introduction to the course                       | NA    |
| 2   | What Are Operating Systems                       | NA    |
| 3   | The Correct Pronounciation                       | NA    |
| 4   | Resources And Practice Important!                | NA    |
| 5   | A Brief History Of How It Started                | NA    |
| 6   | Why Distributions And Not Operating System       | NA    |
| 7   | Debian vs. Fedora vs. macOS (Unix and Unix Like) | NA    |
| 8   | Installing Ubuntu on MacOs                       | NA    |
| 9   | Installing Ubuntu On Windows Using WSL2          | NA    |

## The Linux File System

| Sno | Lecture Title                                      | Notes                                                                                                                                                                                |
| --- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 10  | Section Intro - The Linux File System              | NA                                                                                                                                                                                   |
| 11  | Basic Structure Of A Command                       | [https://cloudaffle.com/series/linux-file-system/basic-command-structure/](https://cloudaffle.com/series/linux-file-system/basic-command-structure/)                                 |
| 12  | Navigation Inside the Terminal                     | [https://cloudaffle.com/series/linux-file-system/basic-navigation-in-terminal/](https://cloudaffle.com/series/linux-file-system/basic-navigation-in-terminal/)                       |
| 13  | Don’t Try To Memorise Commands (Benefits Of Notes) | NA                                                                                                                                                                                   |
| 14  | Overview Of The Directory Structure                | NA                                                                                                                                                                                   |
| 15  | Understanding The Directory Structure In Linux     | [https://cloudaffle.com/series/linux-file-system/filesystem-directory-structure/](https://cloudaffle.com/series/linux-file-system/filesystem-directory-structure/)                   |
| 16  | The \`ls\` Command in Linux                        | [https://cloudaffle.com/series/linux-file-system/indepth-ls-command/](https://cloudaffle.com/series/linux-file-system/indepth-ls-command/)                                           |
| 17  | \`ls\` Long Format                                 | [https://cloudaffle.com/series/linux-file-system/ls-long-format-explanation/](https://cloudaffle.com/series/linux-file-system/ls-long-format-explanation/)                           |
| 18  | The \`file\` Command                               | [https://cloudaffle.com/series/linux-file-system/file-command-in-linux/](https://cloudaffle.com/series/linux-file-system/file-command-in-linux/)                                     |
| 19  | The \`less\` Command                               | [https://cloudaffle.com/series/linux-file-system/less-command-in-linux/](https://cloudaffle.com/series/linux-file-system/less-command-in-linux/)                                     |
| 20  | Introduction To Wildcards                          | [https://cloudaffle.com/series/linux-file-system/wildcard-characters-in-linux/](https://cloudaffle.com/series/linux-file-system/wildcard-characters-in-linux/)                       |
| 21  | Deeper Dive Into Character Classes                 | [https://cloudaffle.com/series/linux-file-system/character-classes/](https://cloudaffle.com/series/linux-file-system/character-classes/)                                             |
| 22  | mkdir - Create Directories                         | [https://cloudaffle.com/series/linux-file-system/mkdir-command/](https://cloudaffle.com/series/linux-file-system/mkdir-command/)                                                     |
| -   | Linux File System Quiz 1                           | NA                                                                                                                                                                                   |
| 23  | cp - Copy Files And Directories                    | [https://cloudaffle.com/series/linux-file-system/cp-command/](https://cloudaffle.com/series/linux-file-system/cp-command/)                                                           |
| 24  | mv - Move and Rename Files                         | [https://cloudaffle.com/series/linux-file-system/mv-command/](https://cloudaffle.com/series/linux-file-system/mv-command/)                                                           |
| 25  | rm - Remove Files And Directories                  | [https://cloudaffle.com/series/linux-file-system/mv-command/](https://cloudaffle.com/series/linux-file-system/mv-command/)                                                           |
| 26  | Links In Linux                                     | [https://cloudaffle.com/series/linux-file-system/links-in-linux/](https://cloudaffle.com/series/linux-file-system/links-in-linux/)                                                   |
| 27  | ln - Create Links                                  | [https://cloudaffle.com/series/linux-file-system/ln-command-to-create-links/](https://cloudaffle.com/series/linux-file-system/ln-command-to-create-links/)                           |
| 28  | ln - Overwrite Existing Files                      | [https://cloudaffle.com/series/linux-file-system/overwrite-existing-files/](https://cloudaffle.com/series/linux-file-system/overwrite-existing-files/)                               |
| 29  | Identifying Links In Terminal                      | [https://cloudaffle.com/series/linux-file-system/identifying-links/](https://cloudaffle.com/series/linux-file-system/identifying-links/)                                             |
| 30  | Practice Exercise For Linux File System            | [https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-file-system.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-file-system.md)                   |
| 31  | Solution To Practice Exercise                      | [https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-file-system-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-file-system-solution.md) |
| -   | Linux File System Quiz 2                           | NA                                                                                                                                                                                   |

## Understanding Commands In Linux

| Sno | Lecture Title                                     | Notes                                                                                                                                                                                                      |
| --- | ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 32  | Section Introduction                              | NA                                                                                                                                                                                                         |
| 33  | Understanding What Are Commands                   | [https://cloudaffle.com/series/commands-in-linux/what-are-commands/](https://cloudaffle.com/series/commands-in-linux/what-are-commands/)                                                                   |
| 34  | type - Check Command Type                         | [https://cloudaffle.com/series/commands-in-linux/type-command/](https://cloudaffle.com/series/commands-in-linux/type-command/)                                                                             |
| 35  | which - Executable Location                       | [https://cloudaffle.com/series/commands-in-linux/which-command/](https://cloudaffle.com/series/commands-in-linux/which-command/)                                                                           |
| 36  | help - Info On Built-ins                          | [https://cloudaffle.com/series/commands-in-linux/help-command/](https://cloudaffle.com/series/commands-in-linux/help-command/)                                                                             |
| 37  | help vs —- help                                   | [https://cloudaffle.com/series/commands-in-linux/help-command-vs-help-option/](https://cloudaffle.com/series/commands-in-linux/help-command-vs-help-option/)                                               |
| 38  | man - Program's Manual                            | [https://cloudaffle.com/series/commands-in-linux/understanding-man-pages/](https://cloudaffle.com/series/commands-in-linux/understanding-man-pages/)                                                       |
| 39  | apropos - Display Suitable Command                | [https://cloudaffle.com/series/commands-in-linux/apropose-command/](https://cloudaffle.com/series/commands-in-linux/apropose-command/)                                                                     |
| 40  | whatis - One Line Man Pages                       | [https://cloudaffle.com/series/commands-in-linux/whatis-command/](https://cloudaffle.com/series/commands-in-linux/whatis-command/)                                                                         |
| 41  | info - Display Info Entry                         | [https://cloudaffle.com/series/commands-in-linux/info-entry-of-program/#man-vs-info](https://cloudaffle.com/series/commands-in-linux/info-entry-of-program/#man-vs-info)                                   |
| 42  | Practice Exercise For Commands In Linux           | [https://github.com/manikbajaj/linux-cli/blob/main/practice/understanding-linux-commands.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/understanding-linux-commands.md)                   |
| 43  | Solution: Practice Exercise For Commands In Linux | [https://github.com/manikbajaj/linux-cli/blob/main/practice/understanding-linux-commands-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/understanding-linux-commands-solution.md) |
| -   | Understanding Commands In Linux Quiz              | NA                                                                                                                                                                                                         |

## Command Line Redirection

| Sno | Lecture Title                            | Notes                                                                                                                                                                                      |
| --- | ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 44  | Intro To Command Line Redirection        | NA                                                                                                                                                                                         |
| 45  | Streams And Redirection                  | [https://cloudaffle.com/series/redirection-in-linux/what-is-redirection/](https://cloudaffle.com/series/redirection-in-linux/what-is-redirection/)                                         |
| 46  | Redirecting stdout                       | [https://cloudaffle.com/series/redirection-in-linux/redirecting-standard-output/](https://cloudaffle.com/series/redirection-in-linux/redirecting-standard-output/)                         |
| 47  | Redirecting stderr                       | [https://cloudaffle.com/series/redirection-in-linux/redirecting-standard-error/](https://cloudaffle.com/series/redirection-in-linux/redirecting-standard-error/)                           |
| 48  | Redirecting stdin                        | [https://cloudaffle.com/series/redirection-in-linux/redirecting-standard-input/](https://cloudaffle.com/series/redirection-in-linux/redirecting-standard-input/)                           |
| 49  | Redirection Order                        | [https://cloudaffle.com/series/redirection-in-linux/significance-of-redirection-order/](https://cloudaffle.com/series/redirection-in-linux/significance-of-redirection-order/)             |
| 50  | Practice: Redirection                    | [https://github.com/manikbajaj/linux-cli/blob/main/practice/redirection-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/redirection-practice.md)                   |
| 51  | Solution: Practice Redirection           | [https://github.com/manikbajaj/linux-cli/blob/main/practice/redirection-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/redirection-practice-solution.md) |
| 52  | grep - Global Regular Expression Print   | [https://cloudaffle.com/series/redirection-in-linux/grep-command/](https://cloudaffle.com/series/redirection-in-linux/grep-command/)                                                       |
| -   | Command Line Redirection Quiz 1          | [https://cloudaffle.com/series/redirection-in-linux/grep-command/](https://cloudaffle.com/series/redirection-in-linux/grep-command/)                                                       |
| 53  | uniq - Filter Adjacent Duplicate Lines   | [https://cloudaffle.com/series/redirection-in-linux/uniq-command/](https://cloudaffle.com/series/redirection-in-linux/uniq-command/)                                                       |
| 54  | wc - Word Count                          | [https://cloudaffle.com/series/redirection-in-linux/wc-command/](https://cloudaffle.com/series/redirection-in-linux/wc-command/)                                                           |
| 55  | head and tail commands                   | [https://cloudaffle.com/series/redirection-in-linux/head-tail-command/](https://cloudaffle.com/series/redirection-in-linux/head-tail-command/)                                             |
| 56  | sort - Command                           | [https://cloudaffle.com/series/redirection-in-linux/sort-command/](https://cloudaffle.com/series/redirection-in-linux/sort-command/)                                                       |
| 57  | Pipelines                                | [https://cloudaffle.com/series/redirection-in-linux/pipelines-in-linux/](https://cloudaffle.com/series/redirection-in-linux/pipelines-in-linux/)                                           |
| 58  | Pipelines And Filters                    | [https://cloudaffle.com/series/redirection-in-linux/pipelines-and-filters/](https://cloudaffle.com/series/redirection-in-linux/pipelines-and-filters/)                                     |
| 59  | Practice: Pipelines and Filters          | [https://github.com/manikbajaj/linux-cli/blob/main/practice/pipelines-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/pipelines-practice.md)                       |
| 60  | Solution: Practice Pipelines and Filters | [https://github.com/manikbajaj/linux-cli/blob/main/practice/pipelines-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/pipelines-practice-solution.md)     |
| -   | Command Line Redirection Quiz 2          | NA                                                                                                                                                                                         |

## Mastering Shell Expansions

| Sno | Lecture Title                        | Notes                                                                                                                                                                                  |
| --- | ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 61  | Intro To Mastering Shell Expansions  | NA                                                                                                                                                                                     |
| 62  | Expansion                            | [https://cloudaffle.com/series/how-shell-receives-inputs/what-is-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/what-is-expansion/)                               |
| 63  | Pathname Expansion                   | [https://cloudaffle.com/series/how-shell-receives-inputs/understanding-pathname-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/understanding-pathname-expansion/) |
| 64  | Tilde Expansion                      | [https://cloudaffle.com/series/how-shell-receives-inputs/tilde-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/tilde-expansion/)                                   |
| 65  | Arithmetic Expansion                 | [https://cloudaffle.com/series/how-shell-receives-inputs/arithmetic-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/arithmetic-expansion/)                         |
| 66  | Brace Expansion                      | [https://cloudaffle.com/series/how-shell-receives-inputs/brace-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/brace-expansion/)                                   |
| 67  | Parameter Expansion                  | [https://cloudaffle.com/series/how-shell-receives-inputs/parameter-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/parameter-expansion/)                           |
| 68  | Command Substitution                 | [https://cloudaffle.com/series/how-shell-receives-inputs/command-substitution/](https://cloudaffle.com/series/how-shell-receives-inputs/command-substitution/)                         |
| -   | Mastering Shell Expansions Quiz 1    | NA                                                                                                                                                                                     |
| 69  | Variable Expansion                   | [https://cloudaffle.com/series/how-shell-receives-inputs/variable-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/variable-expansion/)                             |
| 70  | Alias Expansion                      | [https://cloudaffle.com/series/how-shell-receives-inputs/alias-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/alias-expansion/)                                   |
| 71  | History Expansion                    | [https://cloudaffle.com/series/how-shell-receives-inputs/history-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/history-expansion/)                               |
| 72  | Word Splitting                       | [https://cloudaffle.com/series/how-shell-receives-inputs/word-splitting/](https://cloudaffle.com/series/how-shell-receives-inputs/word-splitting/)                                     |
| 73  | Practice: Mastering Shell Expansions | [https://github.com/manikbajaj/linux-cli/blob/main/practice/expansion-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/expansion-practice.md)                   |
| 74  | Solution: Mastering Shell Expansions | [https://github.com/manikbajaj/linux-cli/blob/main/practice/expansion-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/expansion-practice-solution.md) |
| 75  | Quoting                              | [https://cloudaffle.com/series/how-shell-receives-inputs/quoting-in-linux/](https://cloudaffle.com/series/how-shell-receives-inputs/quoting-in-linux/)                                 |
| 76  | Double Quotes                        | [https://cloudaffle.com/series/how-shell-receives-inputs/double-quotes/](https://cloudaffle.com/series/how-shell-receives-inputs/double-quotes/)                                       |
| 77  | Single Quotes                        | [https://cloudaffle.com/series/how-shell-receives-inputs/single-quotes/](https://cloudaffle.com/series/how-shell-receives-inputs/single-quotes/)                                       |
| -   | Mastering Shell Expansions Quiz 2    | NA                                                                                                                                                                                     |

## Keyboard Tricks

| Sno | Lecture Title                      | Notes                                                                                                                                                                            |
| --- | ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 78  | Intro: Keyboard Tricks             | [https://cloudaffle.com/series/how-shell-receives-inputs/escaping-special-characters/](https://cloudaffle.com/series/how-shell-receives-inputs/escaping-special-characters/)     |
| 79  | Bash Readline                      | [https://cloudaffle.com/series/linux-keyboard-tricks/bash-readline/](https://cloudaffle.com/series/linux-keyboard-tricks/bash-readline/)                                         |
| 80  | Cursor Movements                   | [https://cloudaffle.com/series/linux-keyboard-tricks/cursor-movements/](https://cloudaffle.com/series/linux-keyboard-tricks/cursor-movements/)                                   |
| 81  | Modifying Text                     | [https://cloudaffle.com/series/linux-keyboard-tricks/cursor-movements/](https://cloudaffle.com/series/linux-keyboard-tricks/cursor-movements/)                                   |
| 82  | Text Completion                    | [https://cloudaffle.com/series/linux-keyboard-tricks/using-history/](https://cloudaffle.com/series/linux-keyboard-tricks/using-history/)                                         |
| 83  | Using History                      | [https://cloudaffle.com/series/linux-keyboard-tricks/using-history/](https://cloudaffle.com/series/linux-keyboard-tricks/using-history/)                                         |
| 84  | Practice Exercise: Keyboard Tricks | [https://github.com/manikbajaj/linux-cli/blob/main/practice/keyboard-tricks-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/keyboard-tricks-practice.md) |
| 85  | Solution: Keyboard Tricks          | [https://github.com/manikbajaj/linux-cli/blob/main/practice/keyboard-tricks-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/keyboard-tricks-solution.md) |

## Linux Permissions

| Sno | Lecture Title               | Notes                                                                                                                                                                                      |
| --- | --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 86  | Intro Linux Permissions     | NA                                                                                                                                                                                         |
| 87  | Multiuser Operating Systems | [https://cloudaffle.com/series/linux-permissions/multi-user-operating-systems/](https://cloudaffle.com/series/linux-permissions/multi-user-operating-systems/)                             |
| 88  | Owner, Group, Everbody      | [https://cloudaffle.com/series/linux-permissions/owners-groups-everybody/](https://cloudaffle.com/series/linux-permissions/owners-groups-everybody/)                                       |
| 89  | id - User Identity          | [https://cloudaffle.com/series/linux-permissions/id-command/](https://cloudaffle.com/series/linux-permissions/id-command/)                                                                 |
| 90  | read, write, execute        | [https://cloudaffle.com/series/linux-permissions/file-access-permissions/](https://cloudaffle.com/series/linux-permissions/file-access-permissions/)                                       |
| 91  | chmod - Symbolic Mode       | [https://cloudaffle.com/series/linux-permissions/change-file-permissions/](https://cloudaffle.com/series/linux-permissions/change-file-permissions/)                                       |
| 92  | chmod - Numeric Mode        | [https://cloudaffle.com/series/linux-permissions/chmod-numeric-mode/](https://cloudaffle.com/series/linux-permissions/chmod-numeric-mode/)                                                 |
| 93  | Practice: Linux Permissions | [https://github.com/manikbajaj/linux-cli/blob/main/practice/permissions-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/permissions-practice.md)                   |
| 94  | Solution: Linux Permissions | [https://github.com/manikbajaj/linux-cli/blob/main/practice/permissions-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/permissions-practice-solution.md) |
| -   | Linux Permissions Quiz 1    | [https://github.com/manikbajaj/linux-cli/blob/main/practice/permissions-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/permissions-practice-solution.md) |
| 95  | Changing Identities         | [https://cloudaffle.com/series/linux-permissions/changing-identities-linux/](https://cloudaffle.com/series/linux-permissions/changing-identities-linux/)                                   |
| 96  | Managing Users              | [https://cloudaffle.com/series/linux-permissions/managing-users-in-linux/](https://cloudaffle.com/series/linux-permissions/managing-users-in-linux/)                                       |
| 97  | su - Switching Users        | [https://cloudaffle.com/series/linux-permissions/su-switching-users/](https://cloudaffle.com/series/linux-permissions/su-switching-users/)                                                 |
| 98  | Understanding Groups        | NA                                                                                                                                                                                         |
| 99  | sudo and Sudoers File       | [https://cloudaffle.com/series/linux-permissions/the-need-for-sudo-and-su/](https://cloudaffle.com/series/linux-permissions/the-need-for-sudo-and-su/)                                     |
| 100 | File Owners                 | [https://cloudaffle.com/series/linux-permissions/file-owners-and-groups/](https://cloudaffle.com/series/linux-permissions/file-owners-and-groups/)                                         |
| 101 | chown - Change File Owner   | [https://cloudaffle.com/series/linux-permissions/chown-change-file-owner/](https://cloudaffle.com/series/linux-permissions/chown-change-file-owner/)                                       |
| 102 | chgrp - Change Group        | [https://cloudaffle.com/series/linux-permissions/chgrp-change-group/](https://cloudaffle.com/series/linux-permissions/chgrp-change-group/)                                                 |
| -   | Linux Permissions Quiz 2    | [https://cloudaffle.com/series/linux-permissions/chgrp-change-group/](https://cloudaffle.com/series/linux-permissions/chgrp-change-group/)                                                 |

## Linux Processes

| Sno | Lecture Title                     | Notes                                                                                                                                                                              |
| --- | --------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 103 | Intro: Linux Processes            | NA                                                                                                                                                                                 |
| 104 | Linux Processes And Multitasking  | [https://cloudaffle.com/series/linux-processes/understanding-linux-processes/](https://cloudaffle.com/series/linux-processes/understanding-linux-processes/)                       |
| 105 | PIDs, Child and Daemons           | [https://cloudaffle.com/series/linux-processes/pid-child-process/](https://cloudaffle.com/series/linux-processes/pid-child-process/)                                               |
| 106 | ps - View Processes               | [https://cloudaffle.com/series/linux-processes/understanding-linux-processes/](https://cloudaffle.com/series/linux-processes/understanding-linux-processes/)                       |
| 107 | Process States                    | [https://cloudaffle.com/series/linux-processes/process-states-linux/](https://cloudaffle.com/series/linux-processes/process-states-linux/)                                         |
| 108 | top - Process Interactive Utility | [https://cloudaffle.com/series/linux-processes/top-for-process-detailed-view/](https://cloudaffle.com/series/linux-processes/top-for-process-detailed-view/)                       |
| 109 | Signals                           | [https://cloudaffle.com/series/linux-processes/signals-importance/](https://cloudaffle.com/series/linux-processes/signals-importance/)                                             |
| 110 | Shutting Down System              | [https://cloudaffle.com/series/linux-processes/shutting-down-system/](https://cloudaffle.com/series/linux-processes/shutting-down-system/)                                         |
| 111 | Practice Exercise: Linux Process  | [https://github.com/manikbajaj/linux-cli/blob/main/practice/process-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/process-practice.md)                   |
| 112 | Solution Exercise: Linux Process  | [https://github.com/manikbajaj/linux-cli/blob/main/practice/process-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/process-practice-solution.md) |
| -   | Linux Process Quiz                | [https://github.com/manikbajaj/linux-cli/blob/main/practice/process-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/process-practice-solution.md) |

## Linux Environment

| Sno | Lecture Title                        | Notes                                                                                                                                                                                  |
| --- | ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 113 | Intro: Linux Environment             | NA                                                                                                                                                                                     |
| 114 | Understanding Environment            | [https://cloudaffle.com/series/linux-environment/understanding-linux-environment/](https://cloudaffle.com/series/linux-environment/understanding-linux-environment/)                   |
| 115 | Environment And Shell Variables      | [https://cloudaffle.com/series/linux-environment/environment-shell-variables/](https://cloudaffle.com/series/linux-environment/environment-shell-variables/)                           |
| 116 | How Is Enviroment Established        | [https://cloudaffle.com/series/linux-environment/how-environment-is-established/](https://cloudaffle.com/series/linux-environment/how-environment-is-established/)                     |
| 117 | Startup File                         | [https://cloudaffle.com/series/linux-environment/the-stratup-file/](https://cloudaffle.com/series/linux-environment/the-stratup-file/)                                                 |
| 118 | The PATH                             | [https://cloudaffle.com/series/linux-environment/understanding-path/](https://cloudaffle.com/series/linux-environment/understanding-path/)                                             |
| 119 | Practice: Modifying the .bashrc File | [https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-startup-file.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-startup-file.md)                   |
| 120 | Solution: Modifying the .bashrc File | [https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-startup-file-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-startup-file-solution.md) |
| -   | Linux Environment Quiz               | [https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-startup-file-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-startup-file-solution.md) |

## Introduction To Vi

| Sno | Lecture Title                 | Notes                                                                                                                                                                                  |
| --- | ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 121 | Introduction To Vi            | NA                                                                                                                                                                                     |
| 122 | History of VI                 | [https://cloudaffle.com/series/introduction-to-vim/what-is-vi/](https://cloudaffle.com/series/introduction-to-vim/what-is-vi/)                                                         |
| 123 | Editing Modes In VI           | [https://cloudaffle.com/series/introduction-to-vim/vi-modes/](https://cloudaffle.com/series/introduction-to-vim/vi-modes/)                                                             |
| 124 | VI Basics                     | [https://cloudaffle.com/series/introduction-to-vim/vi-basics/](https://cloudaffle.com/series/introduction-to-vim/vi-basics/)                                                           |
| 125 | Deleting Text In VI           | [https://cloudaffle.com/series/introduction-to-vim/deleting-text-in-vi/](https://cloudaffle.com/series/introduction-to-vim/deleting-text-in-vi/)                                       |
| 126 | Cut, Copy, Paste              | [https://cloudaffle.com/series/introduction-to-vim/cut-copy-paste-vi/](https://cloudaffle.com/series/introduction-to-vim/cut-copy-paste-vi/)                                           |
| 127 | Joining Lines                 | [https://cloudaffle.com/series/introduction-to-vim/joining-lines/](https://cloudaffle.com/series/introduction-to-vim/joining-lines/)                                                   |
| 128 | Search And Replace            | [https://cloudaffle.com/series/introduction-to-vim/search-and-replace/](https://cloudaffle.com/series/introduction-to-vim/search-and-replace/)                                         |
| 129 | Editing Multiple Files        | [https://cloudaffle.com/series/introduction-to-vim/working-with-multiple-files/](https://cloudaffle.com/series/introduction-to-vim/working-with-multiple-files/)                       |
| 130 | Copying Content Between Files | [https://cloudaffle.com/series/introduction-to-vim/copying-content-betwen-files/](https://cloudaffle.com/series/introduction-to-vim/copying-content-betwen-files/)                     |
| 131 | Practice: Mastering VI Editor | [https://github.com/manikbajaj/linux-cli/blob/main/practice/vi-editor-in-linux.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/vi-editor-in-linux.md)                   |
| 132 | Solution: Mastering VI Editor | [https://github.com/manikbajaj/linux-cli/blob/main/practice/vi-editor-in-linux-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/vi-editor-in-linux-solution.md) |
| -   | Introduction To Vi Quiz       | [https://github.com/manikbajaj/linux-cli/blob/main/practice/vi-editor-in-linux-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/vi-editor-in-linux-solution.md) |

## Package Management

| Sno | Lecture Title                      | Notes                                                                                                                                                                                  |
| --- | ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 133 | Intro - Package Management         | NA                                                                                                                                                                                     |
| 134 | UNderstanding Package Management   | NA                                                                                                                                                                                     |
| 135 | What Are Packages                  | [https://cloudaffle.com/series/linux-package-management/what-is-package-management/](https://cloudaffle.com/series/linux-package-management/what-is-package-management/)               |
| 136 | How Package System Works           | [https://cloudaffle.com/series/linux-package-management/how-package-system-works/](https://cloudaffle.com/series/linux-package-management/how-package-system-works/)                   |
| 137 | Package Management Tools           | [https://cloudaffle.com/series/linux-package-management/package-management-tools/](https://cloudaffle.com/series/linux-package-management/package-management-tools/)                   |
| 138 | Find and Install Packages          | [https://cloudaffle.com/series/linux-package-management/find-install-packages/](https://cloudaffle.com/series/linux-package-management/find-install-packages/)                         |
| 139 | Remove Packages                    | [https://cloudaffle.com/series/linux-package-management/remove-packages/](https://cloudaffle.com/series/linux-package-management/remove-packages/)                                     |
| 140 | Updating Packages                  | [https://cloudaffle.com/series/linux-package-management/updating-packages/](https://cloudaffle.com/series/linux-package-management/updating-packages/)                                 |
| 141 | Fetch Package Information          | [https://cloudaffle.com/series/linux-package-management/information-about-packages/](https://cloudaffle.com/series/linux-package-management/information-about-packages/)               |
| 142 | Practice: Linux Package Management | [https://github.com/manikbajaj/linux-cli/blob/main/practice/package-management.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/package-management.md)                   |
| 143 | Solution: Linux Package Management | [https://github.com/manikbajaj/linux-cli/blob/main/practice/package-management-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/package-management-solution.md) |
| -   | Linux Package Management Quiz      | [https://github.com/manikbajaj/linux-cli/blob/main/practice/package-management-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/package-management-solution.md) |

## Storage Management In Linux

| Sno | Lecture Title                      | Notes                                                                                                                                                                                  |
| --- | ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 144 | Intro: Storage Management In Linux | NA                                                                                                                                                                                     |
| 145 | Types Of Storage                   | [https://cloudaffle.com/series/linux-storage-media/types-of-storage/](https://cloudaffle.com/series/linux-storage-media/types-of-storage/)                                             |
| 146 | Mounting And Unmounting            | [https://cloudaffle.com/series/linux-storage-media/types-of-storage/](https://cloudaffle.com/series/linux-storage-media/types-of-storage/)                                             |
| 147 | Understanding What Are Partitions  | NA                                                                                                                                                                                     |
| 148 | Mount A Drive                      | [https://cloudaffle.com/series/linux-storage-media/mounting-unmounting-example/](https://cloudaffle.com/series/linux-storage-media/mounting-unmounting-example/)                       |
| 149 | Why Is Unmounting Needed           | [https://cloudaffle.com/series/linux-storage-media/why-unmounting-is-important/](https://cloudaffle.com/series/linux-storage-media/why-unmounting-is-important/)                       |
| 150 | Determining Device Names           | [https://cloudaffle.com/series/linux-storage-media/determining-device-names-in-linux/](https://cloudaffle.com/series/linux-storage-media/determining-device-names-in-linux/)           |
| 151 | Linux File Systems                 | [https://cloudaffle.com/series/linux-storage-media/introduction-to-file-systems/](https://cloudaffle.com/series/linux-storage-media/introduction-to-file-systems/)                     |
| 152 | Creating New File System           | [https://cloudaffle.com/series/linux-storage-media/creating-new-file-system/](https://cloudaffle.com/series/linux-storage-media/creating-new-file-system/)                             |
| 153 | Test And Repair File System        | [https://cloudaffle.com/series/linux-storage-media/test-and-repairing-file-system/](https://cloudaffle.com/series/linux-storage-media/test-and-repairing-file-system/)                 |
| 154 | Creating Drive Images              | [https://cloudaffle.com/series/linux-storage-media/creating-images-of-drives/](https://cloudaffle.com/series/linux-storage-media/creating-images-of-drives/)                           |
| 155 | Practice - Storage Management      | [https://github.com/manikbajaj/linux-cli/blob/main/practice/storage-management.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/storage-management.md)                   |
| 156 | Solution - Storage Management      | [https://github.com/manikbajaj/linux-cli/blob/main/practice/storage-management-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/storage-management-solution.md) |
| -   | Storage Management Quiz            | NA                                                                                                                                                                                     |

## Networking In Linux

| Sno | Lecture Title                            | Notes                                                                                                                                        |
| --- | ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| 157 | Intro: Networking In Linux               | NA                                                                                                                                           |
| 158 | ping                                     | [https://cloudaffle.com/series/networking-in-linux/types-of-storage/](https://cloudaffle.com/series/networking-in-linux/types-of-storage/)   |
| 159 | traceroute                               | [https://cloudaffle.com/series/networking-in-linux/traceroute/](https://cloudaffle.com/series/networking-in-linux/traceroute/)               |
| 160 | netstat and route tables                 | [https://cloudaffle.com/series/networking-in-linux/ip/](https://cloudaffle.com/series/networking-in-linux/ip/)                               |
| 161 | Network Infrastructure For Demonstration | NA                                                                                                                                           |
| 162 | Understanding FTP                        | [https://cloudaffle.com/series/networking-in-linux/ftp/](https://cloudaffle.com/series/networking-in-linux/ftp/)                             |
| 163 | Installing FTP                           | NA                                                                                                                                           |
| 164 | Using FTP                                | [https://cloudaffle.com/series/networking-in-linux/using-ftp/](https://cloudaffle.com/series/networking-in-linux/using-ftp/)                 |
| 165 | Understanding SSH                        | [https://cloudaffle.com/series/networking-in-linux/understanding-ssh/](https://cloudaffle.com/series/networking-in-linux/understanding-ssh/) |
| 166 | Connecting To SSH                        | [https://cloudaffle.com/series/networking-in-linux/connecting-to-ssh/](https://cloudaffle.com/series/networking-in-linux/connecting-to-ssh/) |
| 167 | SFTP                                     | [https://cloudaffle.com/series/networking-in-linux/using-sftp/](https://cloudaffle.com/series/networking-in-linux/using-sftp/)               |
| 168 | SSH vs FTP                               | [https://cloudaffle.com/series/networking-in-linux/ssh-vs-ftp/](https://cloudaffle.com/series/networking-in-linux/ssh-vs-ftp/)               |
| -   | Networking In Linux Quiz                 | NA                                                                                                                                           |

## Searching For Files

| Sno | Lecture Title               | Notes                                                                                                                                                                                                  |
| --- | --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 169 | Intro: Searching For Files  | NA                                                                                                                                                                                                     |
| 170 | locate                      | [https://cloudaffle.com/series/linux-searching-for-files/locate-command/](https://cloudaffle.com/series/linux-searching-for-files/locate-command/)                                                     |
| 171 | find                        | [https://cloudaffle.com/series/linux-searching-for-files/find-command/](https://cloudaffle.com/series/linux-searching-for-files/find-command/)                                                         |
| 172 | find - Tests                | [https://cloudaffle.com/series/linux-searching-for-files/find-size-and-type/](https://cloudaffle.com/series/linux-searching-for-files/find-size-and-type/)                                             |
| 173 | Understanding Timestamps    | NA                                                                                                                                                                                                     |
| 174 | find- Pre Existing Tests    | [https://cloudaffle.com/series/linux-searching-for-files/find-pre-existing-tests/](https://cloudaffle.com/series/linux-searching-for-files/find-pre-existing-tests/)                                   |
| 175 | find - Logical Operators    | [https://cloudaffle.com/series/linux-searching-for-files/find-logical-operators/](https://cloudaffle.com/series/linux-searching-for-files/find-logical-operators/)                                     |
| 176 | find and xargs              | [https://cloudaffle.com/series/linux-searching-for-files/find-and-xargs/](https://cloudaffle.com/series/linux-searching-for-files/find-and-xargs/)                                                     |
| 177 | Practice - Search For Files | [https://github.com/manikbajaj/linux-cli/blob/main/practice/searching-files-practice-1.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/searching-files-practice-1.md)                   |
| 178 | Solution - Search For Files | [https://github.com/manikbajaj/linux-cli/blob/main/practice/searching-files-practice-solution-1.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/searching-files-practice-solution-1.md) |
| -   | Searching For Files Quiz    | NA                                                                                                                                                                                                     |

## Archiving In Linux

| Sno | Lecture Title                       | Notes                                                                                                                                                                                  |
| --- | ----------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 179 | Intro: Archiving In Linux           | NA                                                                                                                                                                                     |
| 180 | Compressing Files                   | [https://cloudaffle.com/series/linux-archiving/compressing-files/](https://cloudaffle.com/series/linux-archiving/compressing-files/)                                                   |
| 181 | gzip                                | [https://cloudaffle.com/series/linux-archiving/gzip/](https://cloudaffle.com/series/linux-archiving/gzip/)                                                                             |
| 182 | bzip                                | [https://cloudaffle.com/series/linux-archiving/bzip/](https://cloudaffle.com/series/linux-archiving/bzip/)                                                                             |
| 182 | tar                                 | [https://cloudaffle.com/series/linux-archiving/archiving-using-tar/](https://cloudaffle.com/series/linux-archiving/archiving-using-tar/)                                               |
| 184 | zip                                 | [https://cloudaffle.com/series/linux-archiving/zip/](https://cloudaffle.com/series/linux-archiving/zip/)                                                                               |
| 185 | Practice: Compression and Archiving | [https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux.md)                   |
| 186 | Solution: Compression and Archiving | [https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux-solution.md) |
| -   | Archiving In Linux Quiz             | NA                                                                                                                                                                                     |

| Sno | Lecture Title             | Notes |
| --- | ------------------------- | ----- |
| 187 | Intro: bash Scripting     | NA    |
| 188 | Hello World               | NA    |
| 189 | Understanding Shebang(#!) | NA    |
| 190 | Community bash Script     | NA    |
| 191 | Party Parrot              | NA    |
| 192 | Get News                  | NA    |
