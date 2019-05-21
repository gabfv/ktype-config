# ktype-config
My own K-Type config:

![Image of configured K-Type with assigned keys](https://github.com/gabfv/ktype-config/blob/master/config%20k-type.png)

## A few notes
### Warning
The config cannot compile right now due to the static color. For some reasons, the Kiibohd Configurator v.1.0 either provide a wrong JSON or it cannot compile with static colors (Perhaps due to combinations with color wave animations and other type of animations?). You can browse the git history for an older version without the static color or remove it from the JSON.
### First layer (Blue)
Mostly numpad keys, media keys and extra function keys.
* Numpad keys are assigned mostly with the number rows. The same number equal the same Numpad key number (for example, 1 is Numpad 1). Additional operative keys (-, +, /, * and =) are assigned to the right of the number row, Numpad dot and Numpad comma are assigned to dot and comma and finally, Numpad Enter is assigned on Enter;
* F13 to F24 are assigned onto the F1-F12 keys.
* Media keys are assigned onto the Insert block of keys, with mute on the Pause key.
  * Pause: Mute.
  * Ins: Play/Pause.
  * Home: Stop.
  * PgUp: Raise the volume.
  * Del: Previous.
  * End: Next.
  * PgDn: Lower the volume.
  * Arrow left: Rewind (doesn't seem to work with VLC).
  * Arrow right: Fast Forward (doesn't seem to work with VLC).
* Screen brightness is assigned to Arrow Up and Arrow Down.
* Since the Screen Lock key is used to activate the second layer, Screen Lock has been moved to the first layer.
### Second layer (Green)
This layer is for visuals (LEDs) control. The key to activate the second layer is Screen Lock.
* Color waves animation are assigned under F1 and F2.
  * F1: Original color wave animation.
  * F2: Modified color wave animation to be more rainbow-like.
* Static colors are assigned under the alphabet keys.
  * W: White.
  * R: Red.
  * Y: Yellow.
  * I: Indigo.
  * O: Orange.
  * F: Forest Green (very similar to Green, actually).
  * G: Green.
  * V: Violet.
  * B: Blue.
* Visual controls are assigned mostly to the Insert block.
  * Print: Lower the brightness of LEDs.
  * Pause: Raise the brightness of LEDs.
  * Ins: Play/Pause the current color animation.
  * Home: Reset the LEDs to the default state (No color/lightning).
  * PgUp: Set the LEDs brightness at 100%.
  * Del: Wipe the current LED config and blank all the LEDs. (Normally this would be different than than Home if the default state had an animation set.)
  * End: Stop the current color animation.
  * PgDn: Toggle the LEDs on/off.
  * Arrow left: Supposedly, this slow the current color animation (doesn't seem to work).
  * Arrow right: Supposedly, this accelerate the current color animation (doesn't seem to work).
