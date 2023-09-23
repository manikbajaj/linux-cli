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

    1.  Start a `gedit` process.
    2.  Identify the PID of the `gedit` process.
    3.  Send a `SIGSTOP` signal to pause the `gedit` process.
    4.  Confirm if the `gedit` process is stopped.
    5.  Send a `SIGCONT` signal to resume the `gedit` process.
    6.  Confirm if the `gedit` process has resumed.
    7.  Finally, terminate the `gedit` process using the appropriate signal.

## **`pstree` Command:**

    1.  Display the tree of processes.
    2.  Identify any process with its PID and determine its parent and child processes.

## **`xload` Command:**

    1.  Use the `xload` command to monitor system load. Modify the scale and update interval of the graph.
