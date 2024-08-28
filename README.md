# wii_tools
Tools for wii homebrew

# nandpack

This is a script to manipulate Wii save files. It was first inspired by the `gcipack` tool from  PistonMiner's [ttyd-tools](https://github.com/PistonMiner/ttyd-tools) to hack save files, but it became an independent tool to manipulate Wii saves.

It still has a focus on patching Twilight Princess save files to inject custom code in the game, but it can be used to do various generic stuff to **any** Wii save file, such as unpacking/repacking Wii saves.

The resulting hacked saves can be used on Dolphin or on a real Console, with the exception of *The Legend of Zelda: Twilight Princess*, which needs to be loaded through a homebrew app like SaveGame Manager GX.

## Prerequisites
- Python 3
- The `pycryptodome` python module (v`3.20.0`). You can install it using `pip` with the following command: `python3 -m pip install pycryptodome==3.20.0`

## Usage
You can find a list and description of the available commands by running the script without any argument:

    $ ./nandpack.py

# Licences

The algorithm used for the encryption of wii save files in `nandpack` comes from the Dolphin Emulator Project, which is licenced under GPLv2. The binary data which is injected in the save files come from a source code made by PistonMiner, and edited by Zephiles, under the licence GPLv3.

Otherwise, the rest of the "Wii tools" project is licenced under an MIT licence.