# wii_tools
Tools for wii homebrew

# nandpack

This is a script to manipulate wii save files. It has a focus on allowing to patch Twilight Princess save files to inject custom code in the game, but it can be used to do various generic stuff to any wii save file.

## Prerequisites
- Python 3
- The `pycryptodomex` python module (v`3.6.1`). You can install it using `pip` with the following command: `python3 -m pip install pycryptodomex==3.6.1`

## Usage
You can find a list and description of the available commands by running the script without any argument:

    $ ./nandpack.py

# Licences

The algorithm used for the encryption of wii save files in `nandpack` comes from the Dolphin Emulator Project, which is licenced under GPLv2. The binary data which is injected in the save files come from a source code made by PistonMiner, and edited by Zephiles, under the licence GPLv3.

Otherwise, the rest of the "Wii tools" project is licenced under an MIT licence.