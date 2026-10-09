# Snake Stack Core beta

Private playtest builds distributed here for Windows, Android and Fire OS. These are development candidates, with installation confirmation on Android/Fire OS. Save data stays on each device.

## Current beta: 0.36.0

[Download Core 0.36.0](https://github.com/jkubalek-snakestack/snake-stack-core-beta/releases/tag/v0.36.0-beta), or use **Settings → Version & updates** in an installed build.

- Swap by selecting a letter first, dragging onto Swap, or choosing Swap first. An expired opportunity has a two-second disabled transition before Stuck Snake returns.
- Multiplayer totals carry across rounds toward 100. The host can start the next shared countdown directly, or reopen the lobby to adjust the table. All players and Observer screens need **protocol 8**.
- Touch placement keeps the board viewing position. Room codes remain visible during play. Foreground game rooms and Observer screens keep devices awake.
- Home quietly checks the signed update feed and marks Settings when an update is available. No automatic installation or game interruption.
- SNAKE STACK! now uses a short rattlesnake finish cue. Sound: craigsmith's [G12-26-Rattlesnake Rattle.wav](https://freesound.org/people/craigsmith/sounds/437958/), CC0 1.0; a 1.65-second excerpt of the public preview with a soft fade. Sound credit is also in Settings.

The Android APK retains **ARMv7** for the 32-bit Fire TV Cube, plus ARM64 and x86_64. Update over the existing app; do not uninstall or clear game data. Physical Fire TV permission/launcher behavior and tablet touch feel still require device testing. iOS needs the separate unsigned Xcode export and Mac/signing; it is not an installable package here.

## Signed update feed

Installed clients verify the signed beta notice and downloaded package size/hash. [Stable beta feed](https://github.com/jkubalek-snakestack/snake-stack-core-beta/releases/download/beta-feed/beta.json). Versioned packages remain available on their release pages.
