# Practice: Networking In Linux

**Objective:** This exercise aims to help you apply the knowledge you've gained on the Linux networking commands `ping`, `traceroute`, and `ip`. 

---

**Tasks:**

1. **Network Reachability with `ping`:**
    a. Ping Google's primary DNS `8.8.8.8`.
    b. Use `ping` to check the reachability of a website of your choice (e.g., `www.example.com`).
    c. Adjust the interval of pinging to 2 seconds and limit the number of pings to 5.

2. **Network Path with `traceroute`:**
    a. Using `traceroute`, visualize the path packets take to reach `www.example.com`.
    b. Identify the number of hops it takes for the packets to reach their destination.
    c. Compare the output with another website (e.g., `www.anotherexample.com`). Can you identify any common nodes or ISPs?

3. **Interface Diagnostics with `ip`:**
    a. List all the network interfaces available on your machine using the `ip` command.
    b. Identify the primary network interface you are using for internet connectivity (usually named `eth0` or `wlan0`).
    c. Fetch the IP address, broadcast address, and subnet mask of your primary interface.
    d. Identify the route your machine takes to reach the outside world by checking the default gateway.

---

**Note:** Make sure you run these commands in a safe environment and that you understand the implications of network probing. Always respect privacy and terms of use when pinging or tracing routes to servers or websites.
