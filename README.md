# Ambidextrous Endgaming
This keymap enables the efog.tech Endgame trackball to be used with either hand interchangeably. It's intended for when the Endgame is positioned between a split keyboard, pointing directly at the monitor.

Buttons are optimized for the user's hands to be at an angle to the trackball (since it's directly in front of their body).

## Changes in Version 2.0
I no longer maintain forked firmware for the Endgame, thanks to improvements in the OEM firmware. Notably, Marshmallow UI offloads the pointer/scrolling settings to a configuration webpage. My keymaps are now implemented in ZMK Studio.
* Moved RGB and Bluetooth settings to the Device layer
* Removed the User layer

### Past releases
* Version 1.2.0 - [Readme](version_1_2_0.md) | [Download](https://github.com/scatterthought/endgame-trackball-config/releases/tag/v.1.2.0)
* Version 1.1.0 - [Readme](version_1_1_0.md) | [Download](https://github.com/scatterthought/endgame-trackball-config/releases/tag/v.1.1.0)
* Version 1.0.0 - [Readme](version_1_0_0.md) | [Download](https://github.com/scatterthought/endgame-trackball-config/releases/tag/v.1.0.0)

## Default
The Default layer provides the five standard mouse buttons, plus the ability to toggle on the Snipe and Scroll layers with the encoders or access the Extras layer momentarily.
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
* This layer also provides access to the Device layer.

| Left | Right |
| ---- | ----- |
| Enable Device layer | Enable Device layer |
| Transparent | Transparent |
| Return to Default layer | Return to Default layer |
| Transparent | Transparent |
| *Encoder*: Scroll layer (Counter-clockwise only) | *Encoder*: Scroll layer (Clockwise only) |

## Scroll
When the Scroll layer is enabled, moving the ball scrolls vertically and horizontally.
* This layer also provides access to the Device layer.

| Left | Right |
| ---- | ----- |
| Enable Device layer | Enable Device layer |
| Return to Default layer | Return to Default layer |
| Return to Default layer | Return to Default layer |
| Return to Default layer | Return to Default layer |
| *Encoder*: Snipe layer (Clockwise only) | *Encoder*: Snipe layer (Counter-clockwise only) |

## Device
The Device layer contains settings for RGB lighting and Bluetooth.
* This layer can only be accessed by first enabling the Snipe or Scroll layers.
  
| Left | Right |
| ---- | ----- |
| RGB off | Clear all Bluetooth profiles |
| Change RGB lighting effect | Next Bluetooth profile |
| Toggle RGB lighting on/off | Previous Bluetooth profile |
| Return to Default layer | Return to Default layer |
| *Encoder*: Disabled | *Encoder*: Disabled |
