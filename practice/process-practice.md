# Practice Exercise: Linux Process

## Objective:

This exercise will help students reinforce their understanding of Linux commands related to processes and their management.

# Tasks:

## **`ps` Command:**

1.  List all the processes running on your system and display them in a user-friendly format.
2.  Display the process ID, user ID, and command used for each process running on the system.

## **Process States:**

    1.  Run a process and use the `ps` command to determine its state.
    2.  Interpret the state of the running process and identify if there are any additional characters with the state character.

## **Controlling Process with Signals:**

    1.  Start a `sleep` process.
    2.  Identify the PID of the `sleep` process.
    3.  Send a `SIGSTOP` signal to pause the `sleep` process.
    4.  Confirm if the `sleep` process is stopped.
    5.  Send a `SIGCONT` signal to resume the `sleep` process.
    6.  Confirm if the `sleep` process has resumed.
    7.  Finally, terminate the `sleep` process using the appropriate signal.

