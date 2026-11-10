# RKA Windows Companion v1.9.2

Goes with RKA Client 2.2.2. Nothing changes in Lovable for this release.

- **New guest lockdown item: Taskbar apps and Windows search.** It's the backup for RKA Client's own taskbar hiding. If the Windows taskbar ever shows for the guest, it has no pinned apps (no Chrome or Edge to click), there's no Run box and no Windows-key shortcuts, and Start's search shows no web results, so it can't open a browser. Windows applies it the next time Explorer starts (on a PC where RKA Client is the guest's shell, that's only when something starts Explorer).
- **On by default.** The background agent blocks it once for each guest that's locked down (Task Manager or Settings blocked), while the guest is signed in, and notes it in its log. After that it's staff's choice: Allow on the Guest lockdown page stays Allow.
- **Saved lockdown choices from before an item existed leave that item as it is,** so applying an older saved profile (or Control Room's Apply lockdown with one) doesn't undo the new item.
- Agent and scripts at 1.9.2.
