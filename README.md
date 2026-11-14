# Arya Launcher

A lightweight, personal launcher for **Minecraft: Java Edition**, built with Python, GTK 4 and Libadwaita for Linux.

## Features

- **Instances:** create separate game profiles for any Minecraft version (release, snapshot, beta, alpha) with Vanilla, Fabric, Quilt, Forge or NeoForge. Each instance has its own worlds, mods and settings.
- **Mod library:** search and install mods, resource packs and shaders from [Modrinth](https://modrinth.com), filtered by the instance's version and loader, with required dependencies installed automatically.
- **Automatic Java:** downloads the right Java runtime for each Minecraft version.
- **Game log viewer:** search and filter warnings and errors.
- **Low memory use:** the interface uses around 60 MB of RAM.

## Microsoft account sign-in

Arya Launcher signs in with a Microsoft account using the **OAuth 2.0 device code flow** (the user enters a code at microsoft.com/link). The tokens are used only to:

1. authenticate with Xbox Live / XSTS, and
2. get a Minecraft access token and profile to start the game.

The refresh token is stored locally in the system keyring (GNOME Keyring). No data is sent to any server other than Microsoft, Xbox Live and Minecraft services, and nothing is shared with third parties.

## Status

Personal project, used by its author on their own computer. Not distributed commercially.

Not affiliated with Mojang Studios or Microsoft. Minecraft is a trademark of Mojang Studios.
