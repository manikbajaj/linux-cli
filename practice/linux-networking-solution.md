# Solution: Networking In Linux

---

1. **Network Reachability with `ping`:**

    a. To ping Google's primary DNS:
    ```bash
    ping 8.8.8.8
    ```

    b. To ping a website (replace `www.example.com` with your desired website):
    ```bash
    ping www.example.com
    ```

    c. To adjust the interval and limit the number of pings:
    ```bash
    ping -i 2 -c 5 www.example.com
    ```

---

2. **Network Path with `traceroute`:**

    a. Visualizing the path to a website:
    ```bash
    traceroute www.example.com
    ```

    b. The number of lines (hops) before reaching the destination in the `traceroute` output represents the number of nodes the packets traveled through.

    c. To compare with another website (replace `www.anotherexample.com` with your second website):
    ```bash
    traceroute www.anotherexample.com
    ```
    Students should manually compare the output of the two traceroutes to identify common nodes or ISPs.

---

3. **Interface Diagnostics with `ip`:**

    a. List all network interfaces:
    ```bash
    ip addr show
    ```

    b. The primary network interface will usually be named `eth0` (for wired) or `wlan0` (for wireless). Look for these in the output.

    c. Fetching specific details:

    IP Address:
    ```bash
    ip -4 -br addr show dev eth0 | awk '{print $3}' | cut -d '/' -f1
    ```
    
    Broadcast Address:
    ```bash
    ip -4 -br addr show dev eth0 | awk '{print $4}' | cut -d '/' -f1
    ```

    Subnet Mask:
    ```bash
    ip -4 -br addr show dev eth0 | awk '{print $3}' | cut -d '/' -f2
    ```

    d. Checking the default gateway:
    ```bash
    ip route | grep default
    ```

---

**Note:** Replace `eth0` with `wlan0` or any other interface name if your primary interface is different.