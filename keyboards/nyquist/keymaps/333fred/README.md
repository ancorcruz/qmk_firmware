# 333fred's Nyquist Layout

This nyquist layout is based on my Ergodox Infinity Layout, which is [here](../../../ergodox/keymaps/333fred/README.md). It doesn't have all of my VS extensions, as I have my nyquist at home, not at work.

## Layers

### QWERTY
The shift modifiers on this layer all use OSM to allow for quick single capitalization. Press and hold F to go to the VIM movement layer. Layer is also a one-shot layer toggle, and can be held down to type multiple characters on the Lower layer. Game is a regular toggle layer.

```
Qwerty
,-----------------------------------------------------------------------------------.
|   `  |   1  |   2  |   3  |   4  |   5  |   6  |   7  |   8  |   9  |   0  |  -   |
|------+------+------+------+------+------+------+------+------+------+------+------|
| Tab  |   Q  |   W  |   E  |   R  |   T  |   Y  |   U  |   I  |   O  |   P  |  \   |
|------+------+------+------+------+-------------+------+------+------+------+------|
| Esc  |   A  |   S  |   D  |LTVIMF|   G  |   H  |   J  |   K  |   L  |   ;  |  "   |
|------+------+------+------+------+------|------+------+------+------+------+------|
| Shift|   Z  |   X  |   C  |   V  |   B  |   N  |   M  |   ,  |   .  |/ Ctrl| Shift|
|------+------+------+------+------+------+------+------+------+------+------+------|
| Ctrl |  Alt |  F4  | GUI  |Lower | Bksp | Spc  | Ent  | Lock |   =  | Game | Del  |
`-----------------------------------------------------------------------------------'
```

### Lower
My symbol and numpad layer. APscr is a macro that sends ALT+PRSC, to take a screenshot of the current application.

```
Lower
,-----------------------------------------------------------------------------------.
| Caps |  F1  |  F2  |  F3  |  F4  |  F5  |  F6  |  F7  |  F8  |  F9  |  F10 |  F11 |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      |   !  |   @  |   (  |   )  |   |  |   7  |   8  |   9  |   *  |   )  |  F12 |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      |   #  |   $  |   {  |   }  |   `  |   4  |   5  |   6  |   +  |   }  |  |   |
|------+------+------+------+------+------|------+------+------+------+------+------|
| APscr|   %  |   ^  |   [  |   ]  |   ~  |   1  |   2  |   3  |   \  | Vol- | Vol+ |
|------+------+------+------+------+------+------+------+------+------+------+------|
| Pscr |      |      |      |      |      |   0  |   .  |   =  | Prev | Next | Play |
`-----------------------------------------------------------------------------------'
```

### VIM Movement
Pressing and holding F moves to this layer, which turns hjkl into vim movement keys. a and d are macros which send WIN+Left and WIN+Right, respectively. Shift and CTRL have been remapped for ease of selecting text.
```
Vim Movement (Hold down F)
,-----------------------------------------------------------------------------------.
|      |      |      |      |      |      |      |      |      |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |      |      |      |      |      |      |      |      |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      | DLeft|DRight| LCTRL|      |      | Left | Down |  Up  | Right|      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |      |      |      |      |      |      |      |      |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |      |      |      | LShft|      |      |      |      |      |      |      |
`-----------------------------------------------------------------------------------'
 ```

### Gaming
This layer is designed for playing games. All one-shot modification has been turned off, and the common game controls keys have been moved around for easier access.
```
Gaming mode (Raise)
,-----------------------------------------------------------------------------------.
| ESC  |      |      |      |      |      |      |      |      |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |      |      |      |      |      |      |      |      |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
| CTRL |      |      |      |   F  |      |      |      |      |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
| Shift|   Z  |      |      |      |      |      |      |      |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
| Enter|      | Lock |      | Alt  |  Spc | Lower| Left |  Up  | Down | Right|QWERTY|
`-----------------------------------------------------------------------------------'
```
