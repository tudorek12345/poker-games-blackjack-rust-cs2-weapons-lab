# Feature notes

The server owns account balances, game outcomes and multiplayer state. SQLite saves live on the host. Changing the browser device does not create a separate wallet when joining that same host and account.

Poker includes all-ins, side pots, split pots, legal action checks and reconnect snapshots. Practice is separate from persistent poker funds.

Cases and slots show their probabilities and optional Boost modes. Pots weight entries by their displayed play-value. Trades and invitations require player confirmation; bots cannot automatically wager the player's inventory.

Weapon Lab development is focused on correct inventory selection, original finish textures, browser controls and engine-backed practice telemetry. It is not a port of Counter-Strike or a Steam skin service.

The private release includes a portable Windows launcher. A browser is sufficient for guests. The host must stay running; a public deployment needs a server with persistent storage.
