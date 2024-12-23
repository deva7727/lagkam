# LagKam Plugin

**LagKam** is a customizable Minecraft plugin that introduces a countdown timer for dropped items. This allows players to see the remaining time for items on the ground before they despawn. The countdown time can be adjusted via the plugin's configuration file.

## Features

- Customizable item drop countdown.
- Countdown is displayed in the item’s name and lore.
- Countdown time can be changed via the plugin’s config file.
- Automatically removes items when the countdown reaches zero.

## Installation

1. Download the plugin `.jar` file.
2. Place the `.jar` file into your Minecraft server's **plugins** folder.
3. Restart the server to load the plugin.
4. Customize the countdown time in the `config.yml` file located in the `LagKam` plugin folder.

## Configuration

You can adjust the default countdown time by editing the `config.yml` file in the plugin folder.

```yaml
# Default countdown time in seconds
itemDropCountdown: 60
