# RKA Windows Companion v1.2.0

A standard release (no more "pilot" builds). It ships inside RKA Client & Companion Setup, and PCs with the Setup's update task install it by themselves.

## What's new

- **Unlock everything that works however the guest was locked.** Block writes a setting for the guest; Allow deletes it, which is Windows' default. Before 1.2, Restore went back to a snapshot taken the first time the Companion applied a lockdown, so a guest locked by an earlier Companion couldn't be unlocked. Unlock everything, Emergency Restore.cmd, Lovable's Restore and uninstalling RKA Client & Companion all now return the guest to Windows' defaults.
- **Block and Allow on every row**, acting straight away, with a green Blocked or red Allowed status. No more ticks, Apply and Restore.
- **New rows:**
  - RKA Client at sign-in (turn the guest's RKA Client desktop on or off).
  - Password changes (takes Change a password off Ctrl+Alt+Del).
  - Windows tips and pop-ups.
  - USB storage for the guest only.
  - Windows Update restarts only after closing time.
- **Updates page:** the RKA Client, Companion and agent versions, the last update check, warnings when something lags, and one Update now that runs the Setup's update task. Clicking the versions at the bottom opens it. "Include pilot versions" is gone.
- **The desktop shortcut is now called RKA Companion.** RKA Client & Companion Setup puts it on every administrator's desktop (never the guest's) and removes the old "Retro Knights PC Control Center" shortcut.
- **The Lovable page** gets one-line tips on every button. **Copy diagnostics** in Tools zips the logs, without tokens, for support.
- **Approved websites** shows the sites that are always allowed, which now include Outlook/Hotmail, GOG, and the background addresses that Google, Yahoo and Microsoft sign-in pages load from.
- **Clearer LAN play:** "Turn on LAN play" and "Turn off LAN play", with an honest status when it's off. Workers run hidden, so no PowerShell windows flash.
- **For anyone who isn't an administrator,** the window only says "RKA Companion is for staff."
- **The agent** reports its version to RKA Client, Lovable's Restore means Unlock everything, and the approved-website limit rises to 100 entries.

## Upgrading

Install RKA Client & Companion Setup (it includes this version), or use Updates > Install Companion from a ZIP file. The agent upgrades at the same time; then set the new agent version (1.2.0) in Lovable. On PCs locked by an older Companion, open Guest lockdown, click Unlock everything, then Block what you want.
