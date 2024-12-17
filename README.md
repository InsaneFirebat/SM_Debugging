
# Super Metroid Debugging Labels for Mesen-S, Mesen2, and bsnes-plus

## What do I do with it?

Mesen: Open the Debugger window and select `Import/Export` > `Import Labels`. Select the `.msl` or '.mlb' file to add labels to the debugger view and trace logs.

bsnes-plus: Rename the `.sym` file to match your ROM and place it in the same directory. Load the ROM to load the symbols, which will take longer with the `_wram` version.

asar: You can `incsrc wram_symbols.asm` in your ASM files to add labels for WRAM addresses to your assembly projects. Add `--symbols=wla --symbols-path=Debug_Symbols.sym` as a command line option to generate WLA symbols when assembling. These symbols can also be imported into Mesen-S/Mesen2/bsnes-plus.


## Contributing

Feel free to open a pull request to submit improvements, open an issue and discuss naming conventions, or contact me if you're interested in contributing directly.

A copy of the RAM map is included in the repo for the purpose of tracking changes and making updates easier. Original source for this file is linked below


## Thanks

Thanks to P.JBoy for the RAM map, bank logs, and generated labels we started with. Also Metroid Construction :)

https://patrickjohnston.org/bank/index.html

https://patrickjohnston.org/ASM/Lists/Super%20Metroid/RAM%20map.asm

https://metroidconstruction.com/
