# RKA Windows Companion v1.1.0-PILOT

Pilot build. Try it on RKA-TEST-LAPTOP before the other PCs.

## What's new

- **Four pages instead of six:** This PC, Guest lockdown, Lovable & updates, Tools. This PC shows the guest account, lockdown, RKA Client, Lovable, the background agent, LAN play and USB storage at a glance.
- **No typed phrases.** The Companion asks only before changes that reach past the guest account: blocking USB storage, opening LAN play, turning on remote changes or remote USB control, disconnecting the agent and installing updates.
- **Apply changes updates a lockdown that's already on.** It puts the guest's original settings back first, then applies the new ticks, so Restore original settings always returns the PC to how it started.
- **Task Manager block** for the guest, on the Guest lockdown page and from Lovable's existing Task Manager switch.
- **LAN play:** one switch lets every PC on the arcade's local network reach this PC, so any LAN game can host and join, including games added later. The firewall keeps blocking the internet. It also turns off the block rules Windows makes when a game's firewall prompt is cancelled, and keeps doing that whenever Windows adds a new one. Close undoes both.
- **Gaming sign-in sites always allowed** when Chrome and Edge are restricted: Riot, Epic, EA, Battle.net, Ubisoft, Steam, Xbox and PlayStation sign-in, Gmail, Outlook, Yahoo and iCloud mail for sign-in codes, and the captcha sites those pages use.
- **RKA Client 0.5 or later:** Lovable announcements show in the Client as a small message in a bottom corner that never takes focus from a game. This PC shows the Client's version and whether a customer is playing.
- **Ready for the next Lovable update:** the agent can report RKA Client's status and handle Reset this PC, staff unlock and the LAN play switch. Until Lovable knows these, the agent uses the 1.0 check-in, so nothing breaks; the new parts switch on by themselves after the update.
- Chrome startup is hidden when RKA Client is the guest's shell.

## Upgrading

Companion 1.0.9 can install this from Lovable & updates > Install from a ZIP file, or from GitHub once it's published. The agent is upgraded at the same time. After installing, check that Lovable shows agent 1.1.0 for this PC.
