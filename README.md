# Gomps Game Settings

There will always be games that don't work perfectly with the default GOMPS settings. This repo hosts good GOMPS settings for specific games.

File names have the format `[game-id].json`. The game ID can be found in Gomps Manager, next to the game's name. For example, for the game "Grow Home", the entry looks like `Grow Home  Legacy MONO x86  ID: growhome`. In this case, the ID is just `growhome`, and the settings file would be `growhome.json`.

## New Readme

While some games work with Gomps right away, many will need adjustments to make it work properly, and most will need some changes to make it actually look nice. This is where Gomps game configs come in.

Gomps configs are stored in this repository, and shared with all users. This means the configs only need to be figured out once, and then every user can have the same experience. The configs can be adjusted and updated, and users will always get the latest version.

Gomps game configs are stored in JSON files. You can use any text editor to edit these files, but I recommend using something that supports JSON schema, such as Visual Studio Code, Sublime Text, or most heavy-duty IDEs.

Gomps game configs have a [JSON schema](https://github.com/the-gomps/gomps-game-configs/blob/main/gomps-settings-schema.json) that makes it easier to write the JSON file. If you use a text editor that supports JSON schema, this improves autocomplete, and makes the editor mark errors (such as typos or incorrect formatting).
