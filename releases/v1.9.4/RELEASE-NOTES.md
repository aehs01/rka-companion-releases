# RKA Companion 1.9.4

Goes with RKA Client 2.3.0.

- **The Companion window opens again.** Since 1.9.2, opening RKA Companion stopped at "RKA WPF Startup Error: The property 'Tag' cannot be found on this object". The new Taskbar apps lockdown row's buttons were never looked up. The window now looks up every lockdown row from one list, and a self-test check makes sure no row is left out again. The background agent was never affected.
- **PCs follow the intranet server when its address changes.** When rkaserver stops answering at the address saved on the PC for 90 seconds, the background agent looks for it on the PC's own network. It checks only private addresses on the PC's own subnet, at most once every 5 minutes. A machine counts as the server only if it serves the Retro Knights LAN theme. The agent prefers the network card it last saw the server on, and changes nothing if it finds two candidates it can't tell apart. It then saves the new address in the PC's hosts file, on the same "# RKA Client" line Setup and the Companion write, and logs the move. The offline screen notices within 30 seconds, so a PC comes back on its own a few minutes after the server moves.
- RKA Companion > Tools > Intranet server says so.

40 self-test checks pass.
