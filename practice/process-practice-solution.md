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
$ sleep 300
$ ps x | grep sleep
```

This will show the state of the `sleep` process. For example, if the state is `S`, it means the process is sleeping.

## **Controlling Process with Signals:**

### Solution:

```bash
$ sleep 300
```

Find the PID of the process

```bash
ps u 
```

This command sends a `SIGSTOP` signal to pause the `sleep` process.
```bash
$ kill -STOP [PID]
```


This will confirm whether the `sleep` process is stopped (T state).

```bash
$ ps x | grep sleep
```

This command sends a `SIGCONT` signal to resume the `sleep` process.

```bash
$ kill -CONT [PID]
```

This will confirm whether the `sleep` process has resumed.

```bash
$ ps x | grep sleep
```


This command will terminate the `sleep` process using the `SIGTERM` signal.
```bash
$ kill -TERM [PID]
```



