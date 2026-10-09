# Snake Stack Core beta

## Current beta: 0.38.0

[Download Core 0.38.0](https://github.com/jkubalek-snakestack/snake-stack-core-beta/releases/tag/v0.38.0-beta), or use **Settings → Version & updates**. Every player and Observer must update together to **multiplayer protocol 9**. Existing saves and preferences stay on each device.

- Larger, stable six-row challenge/practice boards; long boards retain manual scrolling.
- Gentle selection and placement feedback, optional light Android haptics, and reduced-motion support.
- Consistent menus with pinned primary actions, readable wrapping and stable scroll gutters.
- Temporary, non-blocking move guidance through Why? and explanations for unavailable actions.
- Nearby Wi-Fi/LAN room search on Windows/Android/Fire OS, followed by a connection review. Saved forms and shared invitations remain available when network discovery is blocked.
- Animated round totals toward 100. Every player chooses Ready for next round before the host starts the shared countdown.
- Distinct original countdown, STACK, Bite and Stuck cues, with important-call priority and optional call sounds. The existing CC0 rattlesnake finish remains.
- Restrained Observer long-word, projected-lead and finish highlights. Full boards and current hands stay visible; focusing a player gives a closer view.
- English meanings plus offline Portuguese coverage for **5,850 spellings / 9,045 senses**, with accented lemmas and source links. [OpenWordnet-PT](https://github.com/own-pt/openWordnet-PT), CC BY 4.0; authors and license are bundled. Accepted dictionaries are unchanged. Words outside bundled coverage have Wiktionary/Wikcionário references.
- Independent reading sizes and non-color board status symbols, with keyboard/controller focus and optional motion/sound/haptic preferences.

Android includes ARMv7 for the 32-bit Fire TV Cube, ARM64 and x86_64. Install over the existing app; do not uninstall or clear player data. Physical tablet/Fire TV behavior and cross-device discovery still require retesting. The host emulator remains unavailable, so successful Android runtime acceptance is not claimed.

iOS is a separate unsigned Xcode export requiring Mac compilation/signing and device tests. Direct connections use the local-network permission explanation. Automatic iOS UDP discovery is disabled pending Apple network provisioning or a native Bonjour implementation.

These are development candidates. Desktop Unity render/input, gameplay/network contracts, package signing/branding checks and the signed HTTPS update path are verified separately from physical-device acceptance.

[Stable signed beta feed](https://github.com/jkubalek-snakestack/snake-stack-core-beta/releases/download/beta-feed/beta.json). Clients verify the notice signature and package size/hash; updates never install automatically during gameplay.
