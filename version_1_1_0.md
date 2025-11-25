# Version 1.1.0
## Default
The Default layer provides the five standard mouse buttons, plus the ability to toggle on the Snipe and Scroll layers with the encoders.
| Left | Right |
| ---- | ----- |
| *Tap*: Back mouse button,<br>*Hold*: momentary Extras layer | *Tap*: Forward mouse button,<br>*Hold*: momentary Extras layer |
| Right mouse button | Right mouse button |
| Middle mouse button | Middle mouse button |
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
The Snipe layer reduces pointer speed 1/3rd of normal, allowing for precision clicking with the Left/Middle/Right mouse buttons.

| Left | Right |
| ---- | ----- |
| Return to Default layer | Return to Default layer |
| Transparent | Transparent |
| Transparent | Transparent |
| Transparent | Transparent |
| *Encoder*: Disabled | *Encoder*: Disabled |

## Scroll
When the Scroll layer is enabled, moving the ball scrolls vertically and horizontally.
* This layer also provides access to the Device layer for additional settings.
* Pressing any of the bottom buttons returns to the Default layer, which reenables pointer movement and mouse buttons.

| Left | Right |
| ---- | ----- |
| Enable Device layer | Enable Device layer |
| Transparent | Transparent |
| Return to Default layer | Return to Default layer |
| Return to Default layer | Return to Default layer |
| *Encoder*: Disabled | *Encoder*: Disabled |

## Device
The Device layer contains device settings for polling rate, RGB lighting, Bluetooth, pointer sensitivity, and twist-scroll sensitivity.
* This layer can only be accessed by first enabling the Scroll layer.
* Polling rate increases to the maximum limit, then wraps around to start over from the minimum.
* Pointer and twist-scroll sensitivities increase or decrease to the limit and do **not** wrap around.
  
| Left | Right |
| ---- | ----- |
| Cycle polling rate | Clear all Bluetooth profiles |
| Change RGB lighting effect | Next Bluetooth device |
| Toggle RGB lighting on/off | Previous Bluetooth device |
| Return to Default layer | Return to Default layer |
| *Encoder*: Pointer sensitivity<br>(Clockwise to increase) | *Encoder*: Twist scroll sensitivity<br>(**Counter**-clockwise to increase) |
