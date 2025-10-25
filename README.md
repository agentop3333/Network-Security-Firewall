# Network-Security-Firewall
Windows Firewall: Using the Windows Defender Firewall with Advanced Security GUI.
Key Steps Executed (Windows Component)
The task required the following specific actions on a Windows machine:

1.Rule Creation: Creating a custom Inbound Rule to specifically target and Block network traffic destined for TCP Port 23 (Telnet) across all network profiles (Domain, Private, and Public).

2.Testing: Proving the effectiveness of the rule by attempting a remote connection (telnet 192.168.0.101 23) from a second machine. The expected and confirmed result was "Connect failed," validating the firewall block.

3.Restoration: Deleting the custom block rule to restore the system to its original state.

Deliverable
The final deliverable is a screenshot/configuration file demonstrating the firewall rules applied (which my screenshots clearly document) and a summary of the testing outcome
