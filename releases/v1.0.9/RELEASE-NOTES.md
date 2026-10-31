# Retro Knights Windows Companion v1.0.9 — PILOT

- Bundles all v1.0.8 pilot improvements (snapshot-safe remote browser changes, guest shortcut copying and read-only game compatibility scan).
- Built-in, administrator-initiated public GitHub updater: Stable / Pilot channel, Check for Updates, Download & Install with explicit confirmation; no GitHub login needed.
- Fixed repository and asset-name allowlist; compares on GitHub API version tags and checks download length and SHA-256 against GitHub release-asset digest.
- Protected staging directory and distinct download/install approvals; local or LAN archive install remains available separately.
- Enrolled background agent and heartbeat tasks upgrade together. Fixes a v1.0.8 updater subprocess/rollback issue when agent setup fails.
- Copies replaced application files into protected rollback directory; enrollment, consent and recovery data under ProgramData are preserved.
- Pilot release: tested by source parsers and archive/checksum validation. Real Windows upgrade, remote recovery, and authentic agent heartbeat remain to be tested on one arcade PC.
- GitHub asset digests protect integrity relative to GitHub metadata; no publisher-authenticated code signature has been configured. A compromised repository could still distribute malicious code.
- Guest sessions cannot install updates; the updater requires an elevated administrator account and explicit consent.
