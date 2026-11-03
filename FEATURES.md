# Feature notes

The server owns account balances, game outcomes and multiplayer state. SQLite saves live on the host. Changing the browser device does not create a separate wallet when joining that same host and account.

Poker includes all-ins, side pots, split pots, legal action checks and reconnect snapshots. Practice is separate from persistent poker funds.

Cases and slots show their probabilities and optional Boost modes. Pots weight entries by their displayed play-value. Trades and invitations require player confirmation; bots cannot automatically wager the player's inventory.

Weapon Lab development is focused on correct inventory selection, original finish textures, browser controls and engine-backed practice telemetry. It is not a port of Counter-Strike or a Steam skin service.

The private release includes a portable Windows launcher. A browser is sufficient for guests. The host must stay running; a public deployment needs a server with persistent storage.

## 1.7 repair checks

The rebuilt practice arena uses direct keyboard/mouse input and a live HUD for health, armor, ammunition, reloads and scores. Measured browser checks cover movement, automatic and semi-automatic fire, empty magazines, reloads, crouching, jumping, scopes, pause and respawn. The application suite passes 178 tests. Physical phone and VPN connections remain unverified.

The local pack covers 376 weapon/knife catalog entries across 42 model families. Glove models remain unavailable. Identical texture masks are shared without image changes, reducing the paint pack from about 354 MiB to 45 MiB.
