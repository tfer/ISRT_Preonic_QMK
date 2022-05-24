# ISRT_Preonic_QMK
IRST vim enabling keyboard layout based on Ben Vallack's 32 key layout
  * isrt layout, (vs qwerty)
  * 'vim enabling' in sense that 'hjkl', while not where expected still make sense
  * I find the layout comfortable
  * PC keyboard oriented rather then Mac
    * i.e. Fkeys

# Notes on Developement
  * As this repo contains function/macros, you can't use QMK Configurator
  * per above, you must compile it to get the file you need to flash your keyboard
  * On PC's, the easy way to do this is though WSL
  * some of the `*.h` files referenced are in the qmkfirmware repo and will be duplicated here to allow resolving
  * As I'm adapting a smaller keyboard layout to a Preonic 5 x 10, I used Excel to arrange my layout(s), I intend to include those
  * `Main` will hold the current code, each version flashed will get its own branch

# flashed versions/branches (for details, see branch)
  1. Initial
      * closest to Ben Vallack's layout, with these changes:
        * placed `space` on right side, (my use of my right thumb for space is too ingrained)
      * short commings
        * Until you can type well with this layout, `Home Row Modifiers` just get in the way
        * same for bottom row 'tap-to-get-One-Shot-Modifier'
  2. Simplified (work in progress)
      * to make learning ISRT layout easier