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
| 23  | cp - Copy Files And Directories                    | [https://cloudaffle.com/series/linux-file-system/cp-command/](https://cloudaffle.com/series/linux-file-system/cp-command/)                                                           |
| 24  | mv - Move and Rename Files                         | [https://cloudaffle.com/series/linux-file-system/mv-command/](https://cloudaffle.com/series/linux-file-system/mv-command/)                                                           |
| 25  | rm - Remove Files And Directories                  | [https://cloudaffle.com/series/linux-file-system/mv-command/](https://cloudaffle.com/series/linux-file-system/mv-command/)                                                           |
| 26  | Links In Linux                                     | [https://cloudaffle.com/series/linux-file-system/links-in-linux/](https://cloudaffle.com/series/linux-file-system/links-in-linux/)                                                   |
| 27  | ln - Create Links                                  | [https://cloudaffle.com/series/linux-file-system/ln-command-to-create-links/](https://cloudaffle.com/series/linux-file-system/ln-command-to-create-links/)                           |
| 28  | ln - Overwrite Existing Files                      | [https://cloudaffle.com/series/linux-file-system/overwrite-existing-files/](https://cloudaffle.com/series/linux-file-system/overwrite-existing-files/)                               |
| 29  | Identifying Links In Terminal                      | [https://cloudaffle.com/series/linux-file-system/identifying-links/](https://cloudaffle.com/series/linux-file-system/identifying-links/)                                             |
| 30  | Practice Exercise For Linux File System            | [https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-file-system.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-file-system.md)                   |
| 31  | Solution To Practice Exercise                      | [https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-file-system-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-file-system-solution.md) |

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
| 53  | uniq - Filter Adjacent Duplicate Lines   | [https://cloudaffle.com/series/redirection-in-linux/uniq-command/](https://cloudaffle.com/series/redirection-in-linux/uniq-command/)                                                       |
| 54  | wc - Word Count                          | [https://cloudaffle.com/series/redirection-in-linux/wc-command/](https://cloudaffle.com/series/redirection-in-linux/wc-command/)                                                           |
| 55  | head and tail commands                   | [https://cloudaffle.com/series/redirection-in-linux/head-tail-command/](https://cloudaffle.com/series/redirection-in-linux/head-tail-command/)                                             |
| 56  | sort - Command                           | [https://cloudaffle.com/series/redirection-in-linux/sort-command/](https://cloudaffle.com/series/redirection-in-linux/sort-command/)                                                       |
| 57  | Pipelines                                | [https://cloudaffle.com/series/redirection-in-linux/pipelines-in-linux/](https://cloudaffle.com/series/redirection-in-linux/pipelines-in-linux/)                                           |
| 58  | Pipelines And Filters                    | [https://cloudaffle.com/series/redirection-in-linux/pipelines-and-filters/](https://cloudaffle.com/series/redirection-in-linux/pipelines-and-filters/)                                     |
| 59  | Practice: Pipelines and Filters          | [https://github.com/manikbajaj/linux-cli/blob/main/practice/pipelines-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/pipelines-practice.md)                       |
| 60  | Solution: Practice Pipelines and Filters | [https://github.com/manikbajaj/linux-cli/blob/main/practice/pipelines-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/pipelines-practice-solution.md)     |

## Mastering Shell Expansions

| Sno | Lecture Title                        | Notes                                                                                                                                                                                  |
| --- | ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -   | Intro To Mastering Shell Expansions  | NA                                                                                                                                                                                     |
| -   | Expansion                            | [https://cloudaffle.com/series/how-shell-receives-inputs/what-is-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/what-is-expansion/)                               |
| -   | Pathname Expansion                   | [https://cloudaffle.com/series/how-shell-receives-inputs/understanding-pathname-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/understanding-pathname-expansion/) |
| -   | Tilde Expansion                      | [https://cloudaffle.com/series/how-shell-receives-inputs/tilde-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/tilde-expansion/)                                   |
| -   | Arithmetic Expansion                 | [https://cloudaffle.com/series/how-shell-receives-inputs/arithmetic-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/arithmetic-expansion/)                         |
| -   | Brace Expansion                      | [https://cloudaffle.com/series/how-shell-receives-inputs/brace-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/brace-expansion/)                                   |
| -   | Parameter Expansion                  | [https://cloudaffle.com/series/how-shell-receives-inputs/parameter-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/parameter-expansion/)                           |
| -   | Command Substitution                 | [https://cloudaffle.com/series/how-shell-receives-inputs/command-substitution/](https://cloudaffle.com/series/how-shell-receives-inputs/command-substitution/)                         |
| -   | Variable Expansion                   | [https://cloudaffle.com/series/how-shell-receives-inputs/variable-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/variable-expansion/)                             |
| -   | Alias Expansion                      | [https://cloudaffle.com/series/how-shell-receives-inputs/alias-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/alias-expansion/)                                   |
| -   | History Expansion                    | [https://cloudaffle.com/series/how-shell-receives-inputs/history-expansion/](https://cloudaffle.com/series/how-shell-receives-inputs/history-expansion/)                               |
| -   | Word Splitting                       | [https://cloudaffle.com/series/how-shell-receives-inputs/word-splitting/](https://cloudaffle.com/series/how-shell-receives-inputs/word-splitting/)                                     |
| -   | Practice: Mastering Shell Expansions | [https://github.com/manikbajaj/linux-cli/blob/main/practice/expansion-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/expansion-practice.md)                   |
| -   | Solution: Mastering Shell Expansions | [https://github.com/manikbajaj/linux-cli/blob/main/practice/expansion-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/expansion-practice-solution.md) |
| -   | Quoting                              | [https://cloudaffle.com/series/how-shell-receives-inputs/quoting-in-linux/](https://cloudaffle.com/series/how-shell-receives-inputs/quoting-in-linux/)                                 |
| -   | Double Quotes                        | [https://cloudaffle.com/series/how-shell-receives-inputs/double-quotes/](https://cloudaffle.com/series/how-shell-receives-inputs/double-quotes/)                                       |
| -   | Single Quotes                        | [https://cloudaffle.com/series/how-shell-receives-inputs/single-quotes/](https://cloudaffle.com/series/how-shell-receives-inputs/single-quotes/)                                       |

## Keyboard Tricks

| Sno | Lecture Title                      | Notes                                                                                                                                                                            |
| --- | ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -   | Intro: Keyboard Tricks             | [https://cloudaffle.com/series/how-shell-receives-inputs/escaping-special-characters/](https://cloudaffle.com/series/how-shell-receives-inputs/escaping-special-characters/)     |
| -   | Bash Readline                      | [https://cloudaffle.com/series/linux-keyboard-tricks/bash-readline/](https://cloudaffle.com/series/linux-keyboard-tricks/bash-readline/)                                         |
| -   | Cursor Movements                   | [https://cloudaffle.com/series/linux-keyboard-tricks/cursor-movements/](https://cloudaffle.com/series/linux-keyboard-tricks/cursor-movements/)                                   |
| -   | Modifying Text                     | [https://cloudaffle.com/series/linux-keyboard-tricks/cursor-movements/](https://cloudaffle.com/series/linux-keyboard-tricks/cursor-movements/)                                   |
| -   | Text Completion                    | [https://cloudaffle.com/series/linux-keyboard-tricks/using-history/](https://cloudaffle.com/series/linux-keyboard-tricks/using-history/)                                         |
| -   | Using History                      | [https://cloudaffle.com/series/linux-keyboard-tricks/using-history/](https://cloudaffle.com/series/linux-keyboard-tricks/using-history/)                                         |
| -   | Practice Exercise: Keyboard Tricks | [https://github.com/manikbajaj/linux-cli/blob/main/practice/keyboard-tricks-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/keyboard-tricks-practice.md) |
| -   | Solution: Keyboard Tricks          | [https://github.com/manikbajaj/linux-cli/blob/main/practice/keyboard-tricks-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/keyboard-tricks-solution.md) |

## Linux Permissions

| Sno | Lecture Title                  | Notes                                                                                                                                                                                      |
| --- | ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| -   | Intro Linux Permissions        | NA                                                                                                                                                                                         |
| -   | Multiuser Operating Systems    | [https://cloudaffle.com/series/linux-permissions/multi-user-operating-systems/](https://cloudaffle.com/series/linux-permissions/multi-user-operating-systems/)                             |
| -   | Owner, Group, Everbody         | [https://cloudaffle.com/series/linux-permissions/owners-groups-everybody/](https://cloudaffle.com/series/linux-permissions/owners-groups-everybody/)                                       |
| -   | id - User Identity             | [https://cloudaffle.com/series/linux-permissions/id-command/](https://cloudaffle.com/series/linux-permissions/id-command/)                                                                 |
| -   | read, write, execute           | [https://cloudaffle.com/series/linux-permissions/file-access-permissions/](https://cloudaffle.com/series/linux-permissions/file-access-permissions/)                                       |
| -   | Permission Attributes Examples | [https://cloudaffle.com/series/linux-permissions/permission-attribute-examples/](https://cloudaffle.com/series/linux-permissions/permission-attribute-examples/)                           |
| -   | chmod - Symbolic Mode          | [https://cloudaffle.com/series/linux-permissions/change-file-permissions/](https://cloudaffle.com/series/linux-permissions/change-file-permissions/)                                       |
| -   | chmod - Numeric Mode           | [https://cloudaffle.com/series/linux-permissions/chmod-numeric-mode/](https://cloudaffle.com/series/linux-permissions/chmod-numeric-mode/)                                                 |
| -   | Practice: Linux Permissions    | [https://github.com/manikbajaj/linux-cli/blob/main/practice/permissions-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/permissions-practice.md)                   |
| -   | Solution: Linux Permissions    | [https://github.com/manikbajaj/linux-cli/blob/main/practice/permissions-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/permissions-practice-solution.md) |
| -   | Changing Identities            | [https://cloudaffle.com/series/linux-permissions/changing-identities-linux/](https://cloudaffle.com/series/linux-permissions/changing-identities-linux/)                                   |
| -   | Managing Users                 | [https://cloudaffle.com/series/linux-permissions/managing-users-in-linux/](https://cloudaffle.com/series/linux-permissions/managing-users-in-linux/)                                       |
| -   | su - Switching Users           | [https://cloudaffle.com/series/linux-permissions/su-switching-users/](https://cloudaffle.com/series/linux-permissions/su-switching-users/)                                                 |
| -   | Understanding Groups           | NA                                                                                                                                                                                         |
| -   | sudo and Sudoers File          | [https://cloudaffle.com/series/linux-permissions/the-need-for-sudo-and-su/](https://cloudaffle.com/series/linux-permissions/the-need-for-sudo-and-su/)                                     |
| -   | File Owners                    | [https://cloudaffle.com/series/linux-permissions/file-owners-and-groups/](https://cloudaffle.com/series/linux-permissions/file-owners-and-groups/)                                         |
| -   | chown - Change File Owner      | [https://cloudaffle.com/series/linux-permissions/chown-change-file-owner/](https://cloudaffle.com/series/linux-permissions/chown-change-file-owner/)                                       |
| -   | chgrp - Change Group           | [https://cloudaffle.com/series/linux-permissions/chgrp-change-group/](https://cloudaffle.com/series/linux-permissions/chgrp-change-group/)                                                 |

## Linux Processes

| Sno | Lecture Title                     | Notes                                                                                                                                                                              |
| --- | --------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -   | Intro: Linux Processes            | NA                                                                                                                                                                                 |
| -   | Linux Processes And Multitasking  | [https://cloudaffle.com/series/linux-processes/understanding-linux-processes/](https://cloudaffle.com/series/linux-processes/understanding-linux-processes/)                       |
| -   | PIDs, Child and Daemons           | [https://cloudaffle.com/series/linux-processes/pid-child-process/](https://cloudaffle.com/series/linux-processes/pid-child-process/)                                               |
| -   | ps - View Processes               | [https://cloudaffle.com/series/linux-processes/understanding-linux-processes/](https://cloudaffle.com/series/linux-processes/understanding-linux-processes/)                       |
| -   | Process States                    | [https://cloudaffle.com/series/linux-processes/process-states-linux/](https://cloudaffle.com/series/linux-processes/process-states-linux/)                                         |
| -   | top - Process Interactive Utility | [https://cloudaffle.com/series/linux-processes/top-for-process-detailed-view/](https://cloudaffle.com/series/linux-processes/top-for-process-detailed-view/)                       |
| -   | Signals                           | [https://cloudaffle.com/series/linux-processes/signals-importance/](https://cloudaffle.com/series/linux-processes/signals-importance/)                                             |
| -   | Shutting Down System              | [https://cloudaffle.com/series/linux-processes/shutting-down-system/](https://cloudaffle.com/series/linux-processes/shutting-down-system/)                                         |
| -   | Practice Exercise: Linux Process  | [https://github.com/manikbajaj/linux-cli/blob/main/practice/process-practice.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/process-practice.md)                   |
| -   | Solution Exercise: Linux Process  | [https://github.com/manikbajaj/linux-cli/blob/main/practice/process-practice-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/process-practice-solution.md) |

## Linux Environment

| Sno | Lecture Title                        | Notes                                                                                                                                                                                  |
| --- | ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -   | Intro: Linux Environment             | NA                                                                                                                                                                                     |
| -   | Understanding Environment            | [https://cloudaffle.com/series/linux-environment/understanding-linux-environment/](https://cloudaffle.com/series/linux-environment/understanding-linux-environment/)                   |
| -   | Environment And Shell Variables      | [https://cloudaffle.com/series/linux-environment/environment-shell-variables/](https://cloudaffle.com/series/linux-environment/environment-shell-variables/)                           |
| -   | How Is Enviroment Established        | [https://cloudaffle.com/series/linux-environment/how-environment-is-established/](https://cloudaffle.com/series/linux-environment/how-environment-is-established/)                     |
| -   | Startup File                         | [https://cloudaffle.com/series/linux-environment/the-stratup-file/](https://cloudaffle.com/series/linux-environment/the-stratup-file/)                                                 |
| -   | The PATH                             | [https://cloudaffle.com/series/linux-environment/understanding-path/](https://cloudaffle.com/series/linux-environment/understanding-path/)                                             |
| -   | Practice: Modifying the .bashrc File | [https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-startup-file.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-startup-file.md)                   |
| -   | Solution: Modifying the .bashrc File | [https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-startup-file-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/linux-startup-file-solution.md) |

## Introduction To Vi

| Sno | Lecture Title                 | Notes                                                                                                                                                                                  |
| --- | ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -   | Introduction To Vi            | NA                                                                                                                                                                                     |
| -   | History of VI                 | [https://cloudaffle.com/series/introduction-to-vim/what-is-vi/](https://cloudaffle.com/series/introduction-to-vim/what-is-vi/)                                                         |
| -   | Editing Modes In VI           | [https://cloudaffle.com/series/introduction-to-vim/vi-modes/](https://cloudaffle.com/series/introduction-to-vim/vi-modes/)                                                             |
| -   | VI Basics                     | [https://cloudaffle.com/series/introduction-to-vim/vi-basics/](https://cloudaffle.com/series/introduction-to-vim/vi-basics/)                                                           |
| -   | Deleting Text In VI           | [https://cloudaffle.com/series/introduction-to-vim/deleting-text-in-vi/](https://cloudaffle.com/series/introduction-to-vim/deleting-text-in-vi/)                                       |
| -   | Cut, Copy, Paste              | [https://cloudaffle.com/series/introduction-to-vim/cut-copy-paste-vi/](https://cloudaffle.com/series/introduction-to-vim/cut-copy-paste-vi/)                                           |
| -   | Joining Lines                 | [https://cloudaffle.com/series/introduction-to-vim/joining-lines/](https://cloudaffle.com/series/introduction-to-vim/joining-lines/)                                                   |
| -   | Search And Replace            | [https://cloudaffle.com/series/introduction-to-vim/search-and-replace/](https://cloudaffle.com/series/introduction-to-vim/search-and-replace/)                                         |
| -   | Editing Multiple Files        | [https://cloudaffle.com/series/introduction-to-vim/working-with-multiple-files/](https://cloudaffle.com/series/introduction-to-vim/working-with-multiple-files/)                       |
| -   | Copying Content Between Files | [https://cloudaffle.com/series/introduction-to-vim/copying-content-betwen-files/](https://cloudaffle.com/series/introduction-to-vim/copying-content-betwen-files/)                     |
| -   | Practice: Mastering VI Editor | [https://github.com/manikbajaj/linux-cli/blob/main/practice/vi-editor-in-linux.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/vi-editor-in-linux.md)                   |
| -   | Solution: Mastering VI Editor | [https://github.com/manikbajaj/linux-cli/blob/main/practice/vi-editor-in-linux-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/vi-editor-in-linux-solution.md) |

## Package Management

| Sno | Lecture Title                      | Notes                                                                                                                                                                                  |
| --- | ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -   | Intro - Package Management         | NA                                                                                                                                                                                     |
| -   | What Are Packages                  | [https://cloudaffle.com/series/linux-package-management/what-is-package-management/](https://cloudaffle.com/series/linux-package-management/what-is-package-management/)               |
| -   | How Package System Works           | [https://cloudaffle.com/series/linux-package-management/how-package-system-works/](https://cloudaffle.com/series/linux-package-management/how-package-system-works/)                   |
| -   | Package Management Tools           | [https://cloudaffle.com/series/linux-package-management/package-management-tools/](https://cloudaffle.com/series/linux-package-management/package-management-tools/)                   |
| -   | Find and Install Packages          | [https://cloudaffle.com/series/linux-package-management/find-install-packages/](https://cloudaffle.com/series/linux-package-management/find-install-packages/)                         |
| -   | Remove Packages                    | [https://cloudaffle.com/series/linux-package-management/remove-packages/](https://cloudaffle.com/series/linux-package-management/remove-packages/)                                     |
| -   | Updating Packages                  | [https://cloudaffle.com/series/linux-package-management/updating-packages/](https://cloudaffle.com/series/linux-package-management/updating-packages/)                                 |
| -   | Fetch Package Information          | [https://cloudaffle.com/series/linux-package-management/information-about-packages/](https://cloudaffle.com/series/linux-package-management/information-about-packages/)               |
| -   | Practice: Linux Package Management | [https://github.com/manikbajaj/linux-cli/blob/main/practice/package-management.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/package-management.md)                   |
| -   | Solution: Linux Package Management | [https://github.com/manikbajaj/linux-cli/blob/main/practice/package-management-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/package-management-solution.md) |

## Storage Management In Linux

| Sno | Lecture Title                      | Notes                                                                                                                                                                                  |
| --- | ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -   | Intro: Storage Management In Linux | NA                                                                                                                                                                                     |
| -   | Types Of Storage                   | [https://cloudaffle.com/series/linux-storage-media/types-of-storage/](https://cloudaffle.com/series/linux-storage-media/types-of-storage/)                                             |
| -   | Mounting And Unmounting            | [https://cloudaffle.com/series/linux-storage-media/types-of-storage/](https://cloudaffle.com/series/linux-storage-media/types-of-storage/)                                             |
| -   | Understanding What Are Partitions  | NA                                                                                                                                                                                     |
| -   | Mount A Drive                      | [https://cloudaffle.com/series/linux-storage-media/mounting-unmounting-example/](https://cloudaffle.com/series/linux-storage-media/mounting-unmounting-example/)                       |
| -   | Why Is Unmounting Needed           | [https://cloudaffle.com/series/linux-storage-media/why-unmounting-is-important/](https://cloudaffle.com/series/linux-storage-media/why-unmounting-is-important/)                       |
| -   | Determining Device Names           | [https://cloudaffle.com/series/linux-storage-media/determining-device-names-in-linux/](https://cloudaffle.com/series/linux-storage-media/determining-device-names-in-linux/)           |
| -   | Linux File Systems                 | [https://cloudaffle.com/series/linux-storage-media/introduction-to-file-systems/](https://cloudaffle.com/series/linux-storage-media/introduction-to-file-systems/)                     |
| -   | Creating New File System           | [https://cloudaffle.com/series/linux-storage-media/creating-new-file-system/](https://cloudaffle.com/series/linux-storage-media/creating-new-file-system/)                             |
| -   | Test And Repair File System        | [https://cloudaffle.com/series/linux-storage-media/test-and-repairing-file-system/](https://cloudaffle.com/series/linux-storage-media/test-and-repairing-file-system/)                 |
| -   | Creating Drive Images              | [https://cloudaffle.com/series/linux-storage-media/creating-images-of-drives/](https://cloudaffle.com/series/linux-storage-media/creating-images-of-drives/)                           |
| -   | Practice - Storage Management      | [https://github.com/manikbajaj/linux-cli/blob/main/practice/storage-management.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/storage-management.md)                   |
| -   | Solution - Storage Management      | [https://github.com/manikbajaj/linux-cli/blob/main/practice/storage-management-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/storage-management-solution.md) |

## Networking In Linux

| Sno | Lecture Title                            | Notes                                                                                                                                        |
| --- | ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| -   | Intro: Networking In Linux               | NA                                                                                                                                           |
| -   | ping                                     | [https://cloudaffle.com/series/networking-in-linux/types-of-storage/](https://cloudaffle.com/series/networking-in-linux/types-of-storage/)   |
| -   | traceroute                               | [https://cloudaffle.com/series/networking-in-linux/traceroute/](https://cloudaffle.com/series/networking-in-linux/traceroute/)               |
| -   | netstat and route tables                 | [https://cloudaffle.com/series/networking-in-linux/ip/](https://cloudaffle.com/series/networking-in-linux/ip/)                               |
| -   | Network Infrastructure For Demonstration | NA                                                                                                                                           |
| -   | Understanding FTP                        | [https://cloudaffle.com/series/networking-in-linux/ftp/](https://cloudaffle.com/series/networking-in-linux/ftp/)                             |
| -   | Installing FTP                           | NA                                                                                                                                           |
| -   | Using FTP                                | [https://cloudaffle.com/series/networking-in-linux/using-ftp/](https://cloudaffle.com/series/networking-in-linux/using-ftp/)                 |
| -   | Understanding SSH                        | [https://cloudaffle.com/series/networking-in-linux/understanding-ssh/](https://cloudaffle.com/series/networking-in-linux/understanding-ssh/) |
| -   | Connecting To SSH                        | [https://cloudaffle.com/series/networking-in-linux/connecting-to-ssh/](https://cloudaffle.com/series/networking-in-linux/connecting-to-ssh/) |
| -   | SFTP                                     | [https://cloudaffle.com/series/networking-in-linux/using-sftp/](https://cloudaffle.com/series/networking-in-linux/using-sftp/)               |
| -   | SSH vs FTP                               | [https://cloudaffle.com/series/networking-in-linux/ssh-vs-ftp/](https://cloudaffle.com/series/networking-in-linux/ssh-vs-ftp/)               |

## Searching For Files

| Sno | Lecture Title                      | Notes                                                                                                                                                                                                  |
| --- | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| -   | Intro: Searching For Files         | NA                                                                                                                                                                                                     |
| -   | locate                             | [https://cloudaffle.com/series/linux-searching-for-files/locate-command/](https://cloudaffle.com/series/linux-searching-for-files/locate-command/)                                                     |
| -   | find                               | [https://cloudaffle.com/series/linux-searching-for-files/find-command/](https://cloudaffle.com/series/linux-searching-for-files/find-command/)                                                         |
| -   | find - Tests                       | [https://cloudaffle.com/series/linux-searching-for-files/find-size-and-type/](https://cloudaffle.com/series/linux-searching-for-files/find-size-and-type/)                                             |
| -   | Understanding Timestamps           | NA                                                                                                                                                                                                     |
| -   | find- Pre Existing Tests           | [https://cloudaffle.com/series/linux-searching-for-files/find-pre-existing-tests/](https://cloudaffle.com/series/linux-searching-for-files/find-pre-existing-tests/)                                   |
| -   | find - Logical Operators           | [https://cloudaffle.com/series/linux-searching-for-files/find-logical-operators/](https://cloudaffle.com/series/linux-searching-for-files/find-logical-operators/)                                     |
| -   | find and xargs                     | [https://cloudaffle.com/series/linux-searching-for-files/find-and-xargs/](https://cloudaffle.com/series/linux-searching-for-files/find-and-xargs/)                                                     |
| -   | Practice - Search For Files Part 1 | [https://github.com/manikbajaj/linux-cli/blob/main/practice/searching-files-practice-1.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/searching-files-practice-1.md)                   |
| -   | Solution - Search For Files Part 1 | [https://github.com/manikbajaj/linux-cli/blob/main/practice/searching-files-practice-solution-1.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/searching-files-practice-solution-1.md) |

## Archiving In Linux

| Sno | Lecture Title                       | Notes                                                                                                                                                                                  |
| --- | ----------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -   | Intro: Archiving In Linux           | NA                                                                                                                                                                                     |
| -   | Compressing Files                   | [https://cloudaffle.com/series/linux-archiving/compressing-files/](https://cloudaffle.com/series/linux-archiving/compressing-files/)                                                   |
| -   | gzip                                | [https://cloudaffle.com/series/linux-archiving/gzip/](https://cloudaffle.com/series/linux-archiving/gzip/)                                                                             |
| -   | bzip                                | [https://cloudaffle.com/series/linux-archiving/bzip/](https://cloudaffle.com/series/linux-archiving/bzip/)                                                                             |
| -   | tar                                 | [https://cloudaffle.com/series/linux-archiving/archiving-using-tar/](https://cloudaffle.com/series/linux-archiving/archiving-using-tar/)                                               |
| -   | zip                                 | [https://cloudaffle.com/series/linux-archiving/zip/](https://cloudaffle.com/series/linux-archiving/zip/)                                                                               |
| -   | Practice: Compression and Archiving | [https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux.md)                   |
| -   | Solution: Compression and Archiving | [https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux-solution.md) |

## Bash Scripting

| Sno | Lecture Title                       | Notes                                                                                                                                                                                  |
| --- | ----------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -   | Intro: Archiving In Linux           | NA                                                                                                                                                                                     |
| -   | Compressing Files                   | [https://cloudaffle.com/series/linux-archiving/compressing-files/](https://cloudaffle.com/series/linux-archiving/compressing-files/)                                                   |
| -   | gzip                                | [https://cloudaffle.com/series/linux-archiving/gzip/](https://cloudaffle.com/series/linux-archiving/gzip/)                                                                             |
| -   | bzip                                | [https://cloudaffle.com/series/linux-archiving/bzip/](https://cloudaffle.com/series/linux-archiving/bzip/)                                                                             |
| -   | tar                                 | [https://cloudaffle.com/series/linux-archiving/archiving-using-tar/](https://cloudaffle.com/series/linux-archiving/archiving-using-tar/)                                               |
| -   | zip                                 | [https://cloudaffle.com/series/linux-archiving/zip/](https://cloudaffle.com/series/linux-archiving/zip/)                                                                               |
| -   | Practice: Compression and Archiving | [https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux.md)                   |
| -   | Solution: Compression and Archiving | [https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux-solution.md](https://github.com/manikbajaj/linux-cli/blob/main/practice/archiving-in-linux-solution.md) |
