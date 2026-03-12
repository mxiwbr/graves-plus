# Graves Reworked

![Minecraft](https://img.shields.io/badge/Minecraft-1.21.11-brightgreen)
![Datapack](https://img.shields.io/badge/Type-Datapack-blue)
![Base](https://img.shields.io/badge/Base-VanillaTweaks-lightgrey)
![Modrinth](https://img.shields.io/badge/Available%20on-Modrinth-00AF5C?logo=modrinth)

A small modification of version **4.0.5** of the **Graves** datapack by **vanillatweaks.net** that adds additional control over when graves are created.

## Features

* Creates a **grave when a player dies**, storing their items safely.
* Players can retrieve their items by interacting with the grave.
* **New Feature:** Players with the tag `noGrave` will **not generate a grave on death**.
* Expect more features in the future!

This allows server admins to disable graves for certain players.

## Usage

Give a player the `noGrave` tag:

```
/tag <player> add noGrave
```

Now that player will **not spawn a grave when they die**.

Remove the tag:

```
/tag <player> remove noGrave
```

## Installation

1. Download the datapack.
2. Place the `graves-plus.zip` file inside your world's `datapacks` folder.
3. Run `/datapack list` and search for the datapack
4. Run `/datapack enable graves-plus.zip`
5. You are ready to go!

## Credits

Original **Graves Datapack** created by **VanillaTweaks.net**.
This is a **modified version** with additional functionality.
