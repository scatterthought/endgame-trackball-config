# Version 1.2.1
## Changes from previous version
* Swapped Middle and Right mouse buttons
* Split twist-scroll acceleration toggle into separate Enable/Disable buttons (so that you can be certain whether you're turning it on or off)
* Moved twist-scroll toggle to the User layer
* Reverted twist-scroll and drag-scroll sensitivities to the defaults

### Past releases
* Version 1.2.0 - [Readme](version_1_2_0.md) | [Download](https://github.com/scatterthought/endgame-trackball-config/releases/tag/v.1.2.0)
* Version 1.1.0 - [Readme](version_1_1_0.md) | [Download](https://github.com/scatterthought/endgame-trackball-config/releases/tag/v.1.1.0)
* Version 1.0.0 - [Readme](version_1_0_0.md) | [Download](https://github.com/scatterthought/endgame-trackball-config/releases/tag/v.1.0.0)

## Default
The Default layer provides the five standard mouse buttons, plus the ability to toggle on the Snipe and Scroll layers with the encoders.
| Left | Right |
| ---- | ----- |
| *Tap*: Back mouse button,<br>*Hold*: momentary Extras layer | *Tap*: Forward mouse button,<br>*Hold*: momentary Extras layer |
| Middle mouse button | Middle mouse button |
| Right mouse button | Right mouse button |
| Left mouse button | Mouse mouse button |
| *Encoder*: Snipe layer (Clockwise),<br>Scroll layer (Counter-clockwise) | *Encoder*: Snipe layer (Counter-clockwise),<br>Scroll layer (Clockwise) |

## Extras
The Extras layer provides ZMK Studio Unlock, power off, and Chromium browser-tab management in two-button combinations.
*  To close a tab, press both top-middle buttons together.
*  To reopen a closed tab, press one of the top-middle buttons and a top-corner button.
*  To refresh a tab, press one of the top-middle buttons and a bottom-corner button.

| Left | Right |
| ---- | ----- |
| Close tab (Ctrl+W) | Close tab (Ctrl+W) |
| Reopen closed tab (Ctrl+Shift+T) | Reopen closed tab (Ctrl+Shift+T) |
| Refresh (F5) | Refresh (F5) |
| ZMK Studio Unlock | Power off |
| *Encoder*: Disabled | *Encoder*: Disabled |

## Snipe
The Snipe layer reduces pointer speed 1/3rd of normal, allowing for precision clicking with the Left and Right mouse buttons.
* This layer also provides access to the Device layer to adjust DPI, pointer, and scroll settings.

| Left | Right |
| ---- | ----- |
| Enable Device layer | Enable User layer |
| Transparent | Transparent |
| Return to Default layer | Return to Default layer |
| Transparent | Transparent |
| *Encoder*: Scroll layer (Counter-clockwise only) | *Encoder*: Scroll layer (Clockwise only) |

## Scroll
When the Scroll layer is enabled, moving the ball scrolls vertically and horizontally.
* This layer also provides access to the Device layer to adjust DPI, pointer, and scroll settings.

| Left | Right |
| ---- | ----- |
| Enable Device layer | Enable User layer |
| Return to Default layer | Return to Default layer |
| Return to Default layer | Return to Default layer |
| Return to Default layer | Return to Default layer |
| *Encoder*: Snipe layer (Clockwise only) | *Encoder*: Snipe layer (Counter-clockwise only) |

## Device
The Device layer contains settings for polling rate, pointer sensitivity, and twist scroll.
* This layer can only be accessed by first enabling the Snipe or Scroll layers.
* Pointer and twist-scroll sensitivities increase or decrease to the limit and do **not** wrap around.
* Polling rate and twist-scroll acceleration increase to the maximum limit, then wrap around to start over from the minimum.
  
| Left | Right |
| ---- | ----- |
| Disable twist-scroll acceleration | Enable twist-scroll acceleration |
| Increase twist-scroll sensitivity | Increase twist-scroll acceleration |
| Decrease twist-scroll sensitivity | Decrease twist-scroll acceleration |
| Return to Default layer | Return to Default layer |
| *Encoder*: Pointer sensitivity (Clockwise to increase) | *Encoder*: Polling rate (**Counter**-clockwise to increase) |

## User
The User layer contains settings for RGB lighting and Bluetooth.
* This layer can only be accessed by first enabling the Snipe or Scroll layers.
  
| Left | Right |
| ---- | ----- |
| Enable/disable twist scroll | Clear all Bluetooth profiles |
| Change RGB lighting effect | Next Bluetooth device |
| Toggle RGB lighting on/off | Previous Bluetooth device |
| Return to Default layer | Return to Default layer |
| *Encoder*: Disabled | *Encoder*: Disabled |
