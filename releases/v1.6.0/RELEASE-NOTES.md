# RKA Windows Companion v1.6.0

Goes with Control Room 0.2 (retroknightsarcade.com/control-room).

- The background agent reports this PC's network card addresses (physical adapters only) to Lovable, when Lovable asks for them (`network_macs`), so the Control Room app can wake the PC from off. Sent when they change or every 6 hours.
- For waking to work, turn on Wake-on-LAN in the PC's BIOS and turn off Windows Fast Startup (Control Panel > Power Options > Choose what the power buttons do).
- Set the newest agent version (1.6.0) in Control Room > Manage PCs after publishing.
