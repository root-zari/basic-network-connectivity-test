<img width="439" height="209" alt="Screenshot 2026-10-17 170709" src="https://github.com/user-attachments/assets/83dc41b0-c221-41c3-b149-de5cb3d694c2" />
# basic-network-connectivity-test
A beginner-friendly hands-on lab exploring network connectivity between two devices using the ping command
# Basic Network Connectivity Testing Using Ping

## Project Overview

This project documents my first hands-on networking experiment as a beginner in cybersecurity. I tested network connectivity between two devices connected to the same mobile hotspot using the `ping` command.

The objective was to understand how IP addresses help devices communicate over a network and how basic command-line tools can be used for network troubleshooting.

## Objectives

- Understand basic IP addressing.
- Test connectivity between two devices on the same network.
- Learn the purpose of the `ping` command.
- Observe response times and packet loss.
- Build practical networking knowledge for cybersecurity.

## Lab Setup

- **Devices:** Two devices connected to the same mobile hotspot.
- **Network:** Shared local wireless network.
- **Tool:** Command Prompt / Terminal.
- **Command used:** `ping <target-IP-address>`

## Procedure

1. Connected both devices to the same mobile hotspot.
2. Identified the target device's IP address.
3. Opened the command-line interface on my device.
4. Executed the ping command using the target device's IP address.
5. Observed the responses and connectivity statistics.

## How Ping Works

The `ping` command sends ICMP Echo Request messages to a target IP address and waits for Echo Replies.

A successful response can provide information such as:
- **Bytes:** Size of the response data.
- **Time:** Approximate round-trip time in milliseconds.
- **TTL (Time to Live):** A packet field that limits how many network hops it can traverse.
- **Packet loss:** The percentage of requests that did not receive replies.

## Results and Observations

The ping test was performed between two devices connected to the same hotspot.

- **Connectivity:** [Record whether replies were received.]
- **Response time:** [Add the observed time in milliseconds.]
- **Packet loss:** [Record the actual percentage from the output.]
- **Additional observations:** [Describe any timeouts or other results.]

## What I Learned

- How to use `ping` for basic network connectivity testing.
- How IP addresses identify devices at the network layer.
- How ICMP Echo Requests and Echo Replies support connectivity checks.
- How response times and packet loss help with troubleshooting.
- Why a successful ping does not necessarily mean that a device's applications or services are accessible.

## Ethical Considerations

This experiment was conducted in a controlled learning environment with the other participant's knowledge and permission. No attempt was made to access private files, accounts, or unauthorized services.

## Future Improvements

- Compare ping results across different network conditions.
- Learn to inspect network configuration using `ipconfig` or `ip addr`.
- Explore packet analysis with Wireshark.
- Study TCP, UDP, ports, and basic network troubleshooting.

## References

- [Microsoft Learn: ping command](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ping)

---

*Beginner Cybersecurity Lab | Networking Fundamentals*
