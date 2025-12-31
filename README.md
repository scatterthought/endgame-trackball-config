# Ambidextrous Endgaming
This keymap enables the efog.tech Endgame trackball to be used with either hand interchangeably. It's intended for when the Endgame is positioned between a split keyboard, pointing directly at the monitor.

Buttons are optimized for the user's hands to be at an angle to the trackball (since it's directly in front of their body).

## Changes in Version 2.0
I no longer maintain forked firmware for the Endgame, since the new Marshmallow UI in the OEM firmware provides a configuration webpage for saving keymaps and adjusting device settings. My keymaps are now implemented as overrides to the default keymap in ZMK Studio.
* Moved RGB and Bluetooth settings to the Device layer
* Removed the User layer

### Past releases
* Version 1.2.1 - [Readme](version_1_2_1.md) | [Download](https://github.com/scatterthought/endgame-trackball-config/releases/tag/v.1.2.1)
* Version 1.2.0 - [Readme](version_1_2_0.md) | [Download](https://github.com/scatterthought/endgame-trackball-config/releases/tag/v.1.2.0)
* Version 1.1.0 - [Readme](version_1_1_0.md) | [Download](https://github.com/scatterthought/endgame-trackball-config/releases/tag/v.1.1.0)
* Version 1.0.0 - [Readme](version_1_0_0.md) | [Download](https://github.com/scatterthought/endgame-trackball-config/releases/tag/v.1.0.0)

## Default
The Default layer provides the five standard mouse buttons, plus the ability to toggle on the Snipe and Scroll layers with the encoders or access the Extras layer momentarily.
| Left | ZMK Studio (left) | Right | ZMK Studio (right) |
| ---- | ----- | ---- | ----- |
| Back mouse button, <br>Hold for Extras layer | Hold/tap (layer/mouse key): <br>Extras, MB4 | Forward mouse button, <br>Hold for Extras layer | Hold/tap (layer/mouse key): <br>Extras, MB5 |
| Middle mouse button | Mouse Key Press: MB3 | Middle mouse button | Mouse Key Press: MB3 |
| Right mouse button | Mouse Key Press: MB2 | Right mouse button | Mouse Key Press: MB2 |
| Left mouse button | Mouse Key Press: MB1 | Mouse mouse button | Mouse Key Press: MB1 |
| *Encoder up*: Snipe Layer | To Layer: Snipe | *Encoder up*: Snipe Layer | To Layer: Snipe |
| *Encoder down*: Scroll Layer | To Layer: Scroll | *Encoder down*: Scroll Layer | To Layer: Scroll |

## Extras
The Extras layer provides ZMK Studio Unlock, power off, and Chromium browser-tab management in two-button combinations.
*  To close a tab, press both top-middle buttons together.
*  To reopen a closed tab, press one of the top-middle buttons and a top-corner button.
*  To refresh a tab, press one of the top-middle buttons and a bottom-corner button.

| Left | ZMK Studio (left) | Right | ZMK Studio (right) |
| ---- | ----- | ---- | ----- |
| Close tab | Key Press: LCtrl + Keyboard W | Close tab | Key Press: LCtrl + Keyboard W |
| Reopen closed tab | Key Press: LCtrl + LShift + Keyboard T | Reopen closed tab | Key Press: LCtrl + LShift + Keyboard T |
| Refresh (F5) | Key Press: Keyboard F5 | Refresh (F5) | Key Press: Keyboard F5 |
| ZMK Studio Unlock | Studio Unlock | Power off | Power off |
| *Encoder up*: Disabled | None | *Encoder up*: Disabled | None |
| *Encoder down*: Disabled | None | *Encoder down*: Disabled | None |

## Snipe
The Snipe layer reduces pointer speed 1/3rd of normal, allowing for precision clicking with the Left and Right mouse buttons.
* This layer also provides access to the Device layer.

| Left | ZMK Studio (left) | Right | ZMK Studio (right) |
| ---- | ----- | ---- | ----- |
| Enable Device layer | To Layer: Device | Enable Device layer | To Layer: Device |
| Middle mouse button | Transparent | Middle mouse button | Transparent |
| Return to Default layer | To Layer: Default | Return to Default layer | To Layer: Default |
| Left mouse button | Transparent | Left mouse button | Transparent |
| *Encoder up*: Disabled | None | *Encoder up*: Disabled | None |
| *Encoder down*: Scroll Layer | To Layer: Scroll | *Encoder down*: Scroll Layer | To Layer: Scroll |

## Scroll
When the Scroll layer is enabled, moving the ball scrolls vertically and horizontally.
* This layer also provides access to the Device layer.

| Left | ZMK Studio (left) | Right | ZMK Studio (right) |
| ---- | ----- | ---- | ----- |
| Enable Device layer | To Layer: Device | Enable Device layer | To Layer: Device |
| Return to Default layer | To Layer: Default | Return to Default layer | To Layer: Default |
| Return to Default layer | To Layer: Default | Return to Default layer | To Layer: Default |
| Return to Default layer | To Layer: Default | Return to Default layer | To Layer: Default |
| *Encoder up*: Snipe Layer | To Layer: Snipe | *Encoder up*: Snipe Layer | To Layer: Snipe |
| *Encoder down*: Disabled | None | *Encoder down*: Disabled | None |

## Device
The Device layer contains settings for RGB lighting and Bluetooth.
* This layer can only be accessed by first enabling the Snipe or Scroll layers.
  
| Left | ZMK Studio (left) | Right | ZMK Studio (right) |
| ---- | ----- | ---- | ----- |
| RGB off | RGB off | Clear all Bluetooth profiles | Bluetooth: Clear all profiles |
| Change RGB lighting effect | Underglow: Next Effect | Next Bluetooth profile | Bluetooth: Next Profile |
| Toggle RGB lighting on/off | Toggle RGB | Previous Bluetooth profile | Bluetooth: Previous Profile |
| Return to Default layer | To Layer: Default | Return to Default layer | To Layer: Default |
| *Encoder up*: Disabled | None | *Encoder up*: Disabled | None |
| *Encoder down*: Disabled | None | *Encoder down*: Disabled | None |
