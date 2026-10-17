# savescreen-life

SaveLife for [polpo](https://github.com/polpo-system/polpo): a fader of the screen saver SaveScreen (the
package savescreen): Conway's game of life on the screen.

```
portia.Install savescreen-life
```

## Using

    SaveLife.Install            Life becomes the current fader
    SaveLife.html               its description (with an HTML viewer)

## What is here

    src/SaveLife.Mod
    share/SaveLife.html, SaveLife.gif   the description
    test/SaveLifeTest.Mod

 The source comes from ETH Linux Oberon (OLR, 2017-06-18), converted from an Oberon text to plain
text; the first commit has it unchanged. It compiles unchanged with all five of polpo's compilers
(x86, ARM, ARMv7, RISC-V, MIPS).

## Tests

    SaveLifeTest.Run      1 check: the module loaded; it needs the desktop's display

The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
