# RKA Windows Companion v1.4.0

Ships inside RKA Client & Companion Setup 1.4.0; PCs with the Setup's update task install it by themselves. Set the newest agent version (1.4.0) in Lovable.

- **Tools > Intranet server.** rkaserver's fixed address (its DHCP reservation on the router), saved in this PC's hosts file in the same line RKA Client Setup writes. Save address, Remove and Check (which shows the hosts line and where Windows finds rkaserver now). LAN addresses only.
- **Chrome startup shows again when it's still on.** The panel is hidden once RKA Client is the guest's desktop, but a PC set up before RKA Client can still have the old Chrome startup task, which opens a Chrome window under the Client. The panel now shows whenever that task exists, with a note, so staff can turn it off.
