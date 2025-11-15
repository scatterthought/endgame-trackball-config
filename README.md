# Ambidextrous Endgaming
This keymap enables the efog.tech Endgame trackball to be used with either hand interchangeably. It's intended for when the Endgame is positioned between a split keyboard, pointing directly at the monitor.

Buttons are optimized for the user's hands to be at an angle to the trackball (since it's directly in front of their body).

## Default
The Default layer provides the five standard mouse buttons, plus the ability to enable the Snipe and Scroll layers.
| Left | Right |
| ---- | ----- |
| *Tap*: Back mouse button,<br>*Hold*: momentary Snipe layer | *Tap*: Forward mouse button,<br>*Hold*: momentary Snipe layer |
| Right mouse button | Right mouse button |
| Middle mouse button | Middle mouse button |
| Left mouse button | Mouse mouse button |
| *Encoder*: Switch to Scroll layer | *Encoder*: Switch to Scroll layer |

## Snipe
The Snipe layer reduces pointer speed 1/3rd of normal, which is helpful to counter stiction/precision issues from static bearings. This layer also provides ZMK Studio Unlock, power off, and Chromium browser-tab commands.
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

## Scroll
When the Scroll layer is enabled, moving the ball will scroll vertically and horizontally.
* This layer also provides access to the Device layer for additional settings.
* Pressing any of the bottom buttons will return to the Default layer, which reenables pointer movement and mouse buttons.

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
| Polling rate | Clear all Bluetooth profiles |
| Change RGB lighting effect | Next Bluetooth device |
| Toggle RGB lighting on/off | Previous Bluetooth device |
| Return to Default layer | Return to Default layer |
| *Encoder*: Pointer sensitivity<br>(Clockwise to increase) | *Encoder*: Twist scroll sensitivity<br>(**Counter**-clockwise to increase) |
