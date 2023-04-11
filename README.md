# David Lin's Personal Mechanical Keyboards Research Notes

### Why get a mechanical keyboard?

<pre>
o Use everyday at work
o Customize 
o Rise was helped by the pandemic
o Because it's fun!
</pre>

<hr>

### Keyboard Profiles
<pre>
o Normal/Conventional
o Low

Upsides of low profile keyboards
o portability
o aesthetics 

Downsides of low profile keyboards
o smaller keycaps
o require special switches
o lack of case space to mod

Layouts
o ANSI (most popular, US)
o ISO  (hard to find, EU)
</pre>

<hr>

### C A S E S
<pre>
o Aluminum 
o Brass 
o Stainless steel
o Plastics
o Wood
</pre>

<hr>

### S W I T C H E S
<pre>
Brands
o Cherry MX
o Gateron
o Kailh 
o many others!

Profiles
o Linear (Red)    = No feedback | Smooth | Buttery | Quiet | Popular among gamers
o Tactile (Brown) = Feedback/Bump | Office | Productivity
o Clicky (Blue)   = Loud | Annoying to some

Popular
o Boba U4T (tactile)

Tip: When purchasing make sure switches are 
     compatible with your PCB.

Stems
o Cherry 
o Wall

Mounting
o Plate | 3-pin
o PCB   | 5-pin
</pre>

<hr>

### P C B s
<pre>
Things to consider 
o Programmablity (QMK/VIA) | Layer Mapping
o RGB
o South facing LEDs - which means it won't have issues with most key caps
o Wired/Wireless
o Bluetooth
o Hot swappable vs Solderable
o Switch compatibility
</pre>

<hr>

### K E Y C A P S
<pre>
ABS    : Standard | Paint can begin to wear and shine after long use | GMK most popular
PBT    : Withstands shine
Rubber : Soft
OSA Profile Double-shot PBT Keycaps
Double Shot ABS
Drop.com

Profiles
o cherry
o sa
o mt3
o cat
o dsa
</pre>

<hr>

### S T A B I L I Z E R S
<pre>
Screw-in
Any key larger than 1 unit requires a stab
Should be lubed!
</pre>

<hr>

### P L A T E S
<pre>
o Polycarbonate
o Aluminum
o Stainless steal
o Brass
o Carbon filter
o Acrylic
o Palm

Primarily related to "flex"
</pre>

<hr>

### G A S K E T S
<pre>
Silicone
Pouring
</pre>

<hr>

### F O R M   F A C T O R S
<pre>
Wide range:
27%, 40%, 60%, 65%, 75%, 100

80% = Ten Keyless (TKL)

Really depends on which keys you need or could care less about

Examples include:
o Numpad
o Number keys
o Navigation cluster
o Arrow keys
</pre>

<hr>

### M O U N T S
<pre>
Top
Tray
Gasket 
</pre>
[Learn more here](https://thomasbaart.nl/wp-content/uploads/2019/04/20190407_KeyboardMountingStylesCheatSheet.png)

<hr>

### C O R E S
<pre>
Plastic
Aluminum
</pre>

<hr>

### L U B E S
Krytox 205 G<br>
[Get it here](https://kineticlabs.com/lube/krytox/205-grade-0)

<hr>

### K E Y M A P P I N G 
Activates the following by toggling to Layer03 via the RightCtrl button<br>
o numbers in the navigation cluster | 0 uses the up arrow key<br>
o RGB +/- by using left/right arrow keys<p>

STEP 1 - Connect keyboard to USB then navigate to [VIA](https://www.caniusevia.com) | Chrome browser not supported<br>

STEP 2 - Load the following file<br>
<details>
<summary>my_keychron_k8_pro_via_config.json</summary>

```
{
  "name": "Keychron K8 Pro ANSI RGB",
  "vendorProductId": 875823744,
  "macros": ["", "", "", "", "", "", "", "", "", "", "", "", "", "", "", ""],
  "layers": [
    [
      "KC_ESC",
      "KC_BRID",
      "KC_BRIU",
      "CUSTOM(4)",
      "CUSTOM(5)",
      "RGB_VAD",
      "RGB_VAI",
      "KC_MPRV",
      "KC_MPLY",
      "KC_MNXT",
      "KC_MUTE",
      "KC_VOLD",
      "KC_VOLU",
      "KC_NO",
      "CUSTOM(8)",
      "CUSTOM(10)",
      "RGB_MOD",
      "KC_GRV",
      "KC_1",
      "KC_2",
      "KC_3",
      "KC_4",
      "KC_5",
      "KC_6",
      "KC_7",
      "KC_8",
      "KC_9",
      "KC_0",
      "KC_MINS",
      "KC_EQL",
      "KC_BSPC",
      "KC_INS",
      "KC_HOME",
      "KC_PGUP",
      "KC_TAB",
      "KC_Q",
      "KC_W",
      "KC_E",
      "KC_R",
      "KC_T",
      "KC_Y",
      "KC_U",
      "KC_I",
      "KC_O",
      "KC_P",
      "KC_LBRC",
      "KC_RBRC",
      "KC_BSLS",
      "KC_DEL",
      "KC_END",
      "KC_PGDN",
      "KC_CAPS",
      "KC_A",
      "KC_S",
      "KC_D",
      "KC_F",
      "KC_G",
      "KC_H",
      "KC_J",
      "KC_K",
      "KC_L",
      "KC_SCLN",
      "KC_QUOT",
      "KC_NO",
      "KC_ENT",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_LSFT",
      "KC_NO",
      "KC_Z",
      "KC_X",
      "KC_C",
      "KC_V",
      "KC_B",
      "KC_N",
      "KC_M",
      "KC_COMM",
      "KC_DOT",
      "KC_SLSH",
      "KC_NO",
      "KC_RSFT",
      "KC_NO",
      "KC_UP",
      "KC_NO",
      "KC_LCTL",
      "CUSTOM(0)",
      "CUSTOM(2)",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_SPC",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "CUSTOM(3)",
      "CUSTOM(1)",
      "MO(1)",
      "KC_RCTL",
      "KC_LEFT",
      "KC_DOWN",
      "KC_RGHT"
    ],
    [
      "KC_TRNS",
      "KC_F1",
      "KC_F2",
      "KC_F3",
      "KC_F4",
      "KC_F5",
      "KC_F6",
      "KC_F7",
      "KC_F8",
      "KC_F9",
      "KC_F10",
      "KC_F11",
      "KC_F12",
      "KC_NO",
      "KC_TRNS",
      "KC_TRNS",
      "RGB_TOG",
      "KC_TRNS",
      "CUSTOM(11)",
      "CUSTOM(12)",
      "CUSTOM(13)",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "RGB_TOG",
      "RGB_MOD",
      "RGB_VAI",
      "RGB_HUI",
      "RGB_SAI",
      "RGB_SPI",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "RGB_RMOD",
      "RGB_VAD",
      "RGB_HUD",
      "RGB_SAD",
      "RGB_SPD",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_NO",
      "KC_TRNS",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_TRNS",
      "KC_NO",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "CUSTOM(14)",
      "MAGIC_TOGGLE_NKRO",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_NO",
      "KC_TRNS",
      "KC_NO",
      "KC_TRNS",
      "KC_NO",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_TRNS",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS"
    ],
    [
      "KC_ESC",
      "KC_F1",
      "KC_F2",
      "KC_F3",
      "KC_F4",
      "KC_F5",
      "KC_F6",
      "KC_F7",
      "KC_F8",
      "KC_F9",
      "KC_F10",
      "KC_F11",
      "KC_F12",
      "KC_NO",
      "KC_PSCR",
      "CUSTOM(9)",
      "RGB_MOD",
      "KC_GRV",
      "KC_1",
      "KC_2",
      "KC_3",
      "KC_4",
      "KC_5",
      "KC_6",
      "KC_7",
      "KC_8",
      "KC_9",
      "KC_0",
      "KC_MINS",
      "KC_EQL",
      "KC_BSPC",
      "KC_INS",
      "KC_HOME",
      "KC_PGUP",
      "KC_TAB",
      "KC_Q",
      "KC_W",
      "KC_E",
      "KC_R",
      "KC_T",
      "KC_Y",
      "KC_U",
      "KC_I",
      "KC_O",
      "KC_P",
      "KC_LBRC",
      "KC_RBRC",
      "KC_BSLS",
      "KC_DEL",
      "KC_END",
      "KC_PGDN",
      "KC_CAPS",
      "KC_A",
      "KC_S",
      "KC_D",
      "KC_F",
      "KC_G",
      "KC_H",
      "KC_J",
      "KC_K",
      "KC_L",
      "KC_SCLN",
      "KC_QUOT",
      "KC_NO",
      "KC_ENT",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_LSFT",
      "KC_NO",
      "KC_Z",
      "KC_X",
      "KC_C",
      "KC_V",
      "KC_B",
      "KC_N",
      "KC_M",
      "KC_COMM",
      "KC_DOT",
      "KC_SLSH",
      "KC_NO",
      "KC_RSFT",
      "KC_NO",
      "KC_UP",
      "KC_NO",
      "KC_LCTL",
      "KC_LGUI",
      "KC_LALT",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_SPC",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_RALT",
      "KC_RGUI",
      "MO(3)",
      "TO(3)",
      "KC_LEFT",
      "KC_DOWN",
      "KC_RGHT"
    ],
    [
      "KC_TRNS",
      "KC_BRID",
      "KC_BRIU",
      "CUSTOM(6)",
      "CUSTOM(7)",
      "RGB_VAD",
      "RGB_VAI",
      "KC_MPRV",
      "KC_MPLY",
      "KC_MNXT",
      "KC_MUTE",
      "KC_VOLD",
      "KC_VOLU",
      "KC_NO",
      "KC_7",
      "KC_8",
      "KC_9",
      "KC_TRNS",
      "CUSTOM(11)",
      "CUSTOM(12)",
      "CUSTOM(13)",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_4",
      "KC_5",
      "KC_6",
      "RGB_TOG",
      "RGB_MOD",
      "RGB_VAI",
      "RGB_HUI",
      "RGB_SAI",
      "RGB_SPI",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_1",
      "KC_2",
      "KC_3",
      "KC_TRNS",
      "RGB_RMOD",
      "RGB_VAD",
      "RGB_HUD",
      "RGB_SAD",
      "RGB_SPD",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_NO",
      "KC_TRNS",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_TRNS",
      "KC_NO",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "CUSTOM(14)",
      "MAGIC_TOGGLE_NKRO",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_NO",
      "KC_TRNS",
      "KC_NO",
      "KC_0",
      "KC_NO",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_TRNS",
      "KC_NO",
      "KC_NO",
      "KC_NO",
      "KC_TRNS",
      "KC_TRNS",
      "KC_TRNS",
      "TO(2)",
      "RGB_RMOD",
      "KC_DOWN",
      "RGB_MOD"
    ]
  ],
  "encoders": []
}
```

</details>

STEP 3 - Save<p>

Resources<br>
[QMK Tutorial](https://docs.qmk.fm/#/newbs)<br>
[QMK Firmware](https://github.com/Keychron/qmk_firmware/tree/bluetooth_playground/keyboards/keychron/k8_pro)<br>
[Layers Demo](https://youtu.be/MZI4lz_toFY)<br>

<hr>
 
### Y o u T u b e r s
[Taeha Types](https://youtu.be/1NpNygIrnaQ)<br>
[Glarses]()<br>
[Hipyo Tech](https://www.youtube.com/@HipyoTech)<br>
[Switch and Click]()<br>

<hr>

### R E S O U R C E S
via.com



### T E R M S
<pre>
Thock
Travel
Flex
Actuation force
Stems
Bottoming out
Stabalizers (aka Stabs)
Linear vs Tactile
Foam
Case ping (from aluminum casing)
Pogger
Legending
Device Firmware Upgrade (DFU)
QMK/VIA
Flashing
</pre>

<hr>

### T O O L S
<pre>
Lube kits
Electric screwdriver
Keycap puller
Dielectric grease
Syringe
</pre>

<hr>


### D O W N S I D E S
<pre>
Group buys can take between a month to years<br>
Can be an expensive hobby<br>
</pre>

<hr>

### F A Q
What's the best mechanical keyboard?
```
There's no right answer!
It's all a matter of personal preference.
```
What is a holy panda?
```
It's a Frankenstein switch.
```
What is a 1800 keyboard layout?
```
1800-Compact is an alternative full-size 
layout that has the same number of keys 
as a full-size keyboard in a slightly 
more compact arrangement. Here, the arrow 
keys are squished below the Enter key, 
while the other navigational keys go above 
the number pad.
```

