# Macro module (added)

Type these in the Minecraft chat box:

    /macro list
    /macro view <name>
    /macro add <name> [cmd1\ncmd2]     create (optionally with lines separated by \n)
    /macro edit <name> [cmd1\ncmd2]    replace the macro, or with no lines: select it for the Mod Menu editor
    /macro append <name> <command>     add one line
    /macro delete <name>
    /macro run <name>
    /macro stop
    /macro export [file]               writes /sdcard/games/BedrockTools/<file> (default macros_export.txt)
    /macro import [file]

Macros are plain text files: /sdcard/games/BedrockTools/macros/<name>.mcfunction
They are global (every world). Copy that folder to move them to another device.

Inside a macro: one command per line, "#" or "//" starts a comment, "wait 500" pauses 500 ms.
Editor: Mod Menu > Macro > Edit Name / Edit Content, then press Save Button.
