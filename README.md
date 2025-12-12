# AMX Mod X Plugin Example

A minimal template for creating AMX Mod X plugins.

## Features
- Compiles without hassle
- Intellisense and Autocomplete
- No dependencies or configurations are needed (Amx Mod X compiler + Includes bundled)
- Amx Mod X 1.10 + ReAPI included

## Requirements
- VS Code
- AMXXPawn extension: [KliPPy.amxxpawn-language](https://marketplace.visualstudio.com/items?itemName=KliPPy.amxxpawn-language)

## Quick Start
1. Open folder in VS Code
2. Edit or create a new script in `scripting` folder.
3. Press `CTRL+SHIFT+B` to run build task from `.vscode/tasks.json`
4. Your compiled plugins will be inside `build` folder.

## Project Structure
```
AMXX-Plugin-Example/
├─ scripting/       # .sma source files
├─ build/           # compiled .amxx files
├─ include/         # include files
├─ bin              # Compiler binary
└─ README.md
```

## Notes

- All settings for AMXXPawn Extension are inside `.vscode/settings.json`

- If you are on Linux open `.vscode/settings.json` and uncomment:

    ```json
    "amxxpawn.compiler.executablePath": "${workspaceRoot}/bin/linux/amxxpc"
    ```