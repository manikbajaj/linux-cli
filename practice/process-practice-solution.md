# Solution: Linux Process

## Objective:

To successfully complete the practice exercise related to Linux processes and their management using various commands.

# Solutions:

## **`ps` Command:**

### Task:

1. List all the processes running on your system and display them in a user-friendly format.
2. Display the process ID, user ID, and command used for each process running on the system.

### Solution:

```bash
$ ps aux
```

This command displays all the processes in a user-friendly format, listing detailed information about each process.

## **Process States:**

### Task:

1. Run a process and use the `ps` command to determine its state.
2. Interpret the state of the running process and identify if there are any additional characters with the state character.

### Solution:

```bash
$ gedit &
$ ps x | grep gedit
```

This will show the state of the `gedit` process. For example, if the state is `S`, it means the process is sleeping.

## **Controlling Process with Signals:**

### Task:

1. Start a `gedit` process.
2. Identify the PID of the `gedit` process.
3. Send a `SIGSTOP` signal to pause the `gedit` process.
4. Confirm if the `gedit` process is stopped.
5. Send a `SIGCONT` signal to resume the `gedit` process.
6. Confirm if the `gedit` process has resumed.
7. Finally, terminate the `gedit` process using the appropriate signal.

### Solution:

```bash
$ gedit &
```

This starts a `gedit` process in the background.

```bash
$ pgrep gedit
```

This command finds the PID of the `gedit` process.

```bash
$ kill -STOP [PID]
```

This command sends a `SIGSTOP` signal to pause the `gedit` process.

```bash
$ ps x | grep gedit
```

This will confirm whether the `gedit` process is stopped (T state).

```bash
$ kill -CONT [PID]
```

This command sends a `SIGCONT` signal to resume the `gedit` process.

```bash
$ ps x | grep gedit
```

This will confirm whether the `gedit` process has resumed.

```bash
$ kill -TERM [PID]
```

This command will terminate the `gedit` process using the `SIGTERM` signal.

## **`pstree` Command:**

### Task:

1. Display the tree of processes.
2. Identify any process with its PID and determine its parent and child processes.

### Solution:

```bash
$ pstree -p
```

This command displays a tree of processes, and with the `-p` option, it shows the PID of each process.

## **`xload` Command:**

### Task:

1. Use the `xload` command to monitor system load. Modify the scale and update interval of the graph.

### Solution:

```bash
$ xload -scale 2 -update 1
```

This command starts `xload` with a modified scale and update interval. The `-scale 2` option changes the scale of the graph, and the `-update 1` option changes the update interval to 1 second.

This solution is a reference for completing the given tasks and achieving a proper understanding of managing processes in Linux. Students should execute these commands practically to gain hands-on experience.
