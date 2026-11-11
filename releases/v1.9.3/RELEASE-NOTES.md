# RKA Companion 1.9.3

Goes with RKA Client 2.3.0 and Control Room 0.8.

- **Call staff says which game.** RKA Client 2.3's Call staff picker asks what the customer needs help with and, for a game, signing in or installing, which one. The agent now passes on the game they picked or typed, where it comes from (Steam, Epic, LAN...), a short note they typed, and the game the PC started in the last 15 minutes. It sends them only once the website lists them (Control Room 0.8), so nothing changes until then.
- **New reason: installing or removing a game.** Before Control Room 0.8 it goes as "Something else".
- **Accents come through.** The agent sends its reports as plain-text JSON, so names such as Pokémon arrive as written instead of with a broken letter.

30 self-test checks pass.
