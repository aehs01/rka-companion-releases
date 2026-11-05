# RKA Windows Companion v1.5.0

Goes with RKA Client 1.7 and Control Room (retroknightsarcade.com/control-room). Set the newest agent version (1.5.0) in Lovable.

- **PC health for Control Room.** The background agent passes RKA Client 1.7's health report to Lovable with each check-in: free space on the system and games drives, whether the intranet loads, whether the last reset signed out of every launcher, which launchers have an account signed in (ids only, never account names), errors in the last hour, uptime and game counts. It sends the report only once Lovable says it accepts one (the client_health feature), and re-checks every field first.
