
# Super Metroid Debugging Labels for Mesen-S

## What do I do with it?

Open the Debugger window in Mesen-S and select `Import/Export` > `Import Labels`. Select the `.msl` file to add labels to the debugger view and trace logs.

You can incsrc the `.asm` file to add labels for WRAM addresses to your asar assembly projects. Add `--symbols=wla --symbols-path=Debug_Symbols.sym` as a command line option to generate WLA symbols when assembling. These symbols can also be imported into Mesen-S.


## Contributing

Feel free to open a pull request to submit improvements, open an issue and discuss naming conventions, or contact me if you're interested in contributing directly.


## Thanks

Thanks to P.JBoy for the bank logs and generated labels we started with. Also Metroid Construction :)
