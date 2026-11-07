# RKA Windows Companion v1.9.0

Goes with RKA Client 2.1.0. Nothing changes in Lovable for this release.

- **Connect this PC to Lovable, in the window.** The top of the Lovable page has one box: the PC's name (filled in from Windows, made upper case, spaces taken out) and its token from Control Room. Connect does the connection, the background agent and the first check-in in one go, and says plainly what happened: connected, or why not (a name or token that can't be used, or Lovable turning the check-in down). The token goes to the protected setup only through that process's own environment, is trimmed of a pasted space or line break, and is cleared from the box straight away.
- **Install or repair agent on a PC that isn't connected yet** now points at the Connect box instead of failing.
- **Real error messages.** A setup step that fails shows its reason in the window, instead of "Its log is in ProgramData\RKA-Lockdown-Agent". The agent setup prints its reason where the window reads it, and the window also reads PowerShell's own error output.
- **Connect or reconnect this PC** (the old PowerShell window) stays open when it stops, so the reason can be read.
- **No firewall pop-up for LAN games.** With LAN play on, Windows no longer shows "Windows Security Alert: allow access?" when a game starts listening. On a guest PC that pop-up needs an administrator to answer, so it asked for the admin password the first time a LAN game such as Call of Duty 4 ran. LAN play's allow rule already lets the local network in, and turning LAN play off turns the pop-up back on.
- Updating the agent also refreshes LAN play when it is on, so its maintenance task gets this version too.
- Agent and scripts at 1.9.0.
