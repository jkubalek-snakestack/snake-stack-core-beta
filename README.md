# Snake Stack Core beta

## Current beta: 0.83.0

[Download Core 0.83](https://github.com/jkubalek-snakestack/snake-stack-core-beta/releases/tag/v0.83.0-beta), or use the download button beside **Setup** in the game. Use the same release across your room; multiplayer protocol remains **23**. Install over the existing beta to retain its local player data.

- Safer room recovery, rejoining and host handoff, with confirmed moves preserved and old move effects kept quiet.
- Stronger progress import, player switching, account boundaries, backup retention and deletion handling.
- Direct recovery for a silent Stack Tracks mix, while respecting intentional mute.
- Fixed long Windows receipt paths that could block returning from Merriton results.
- A bounded, signed update bridge for older beta installations, with verified legacy/current Windows installation and hosted downloads.

The included game still offers ten original Stack Tracks scores and Archive, twenty character worlds, Merriton, completed-board inspection, personal keyboard/controller access and optional Cadence/Ensemble prototypes. Multiplayer → **On this screen** adapts its independent boards to the device, controllers and available space; phones keep one board. Physical-device and controller comfort remain separate acceptance tasks.

Public downloads cover Windows and ARM32/ARM64 Android/Fire OS. The included music and worlds work offline. Purchases and advertising remain inactive. Offline family play remains available; this beta does not provide managed parental consent for child online accounts. Storefront, final rights, physical-device and real remote-service acceptance remain open. The private iOS handoff is an unsigned Release Xcode export; Apple enrollment, Mac compilation/signing and TestFlight upload remain pending.

The game verifies signed update notices and package hashes. Installation begins when the player chooses it after leaving active play. [Current signed feed](https://github.com/jkubalek-snakestack/snake-stack-core-beta/releases/download/beta-feed/beta-v2.json). The [legacy feed](https://github.com/jkubalek-snakestack/snake-stack-core-beta/releases/download/beta-feed/beta.json) stays pinned to the bounded 0.83 bridge for returning older installations.

Publisher: Snake Stack Games LLC · support@snake-stack.com.

Known touch issue: a board swipe beginning on a placed tile can start a move. Start scrolling from empty board space for now; swipe-versus-move handling is queued for the next patch.
