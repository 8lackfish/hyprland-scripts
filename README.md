<h1 align="center">Useful scripts for Hyprland</h1>

## List

| Name (a-z) | Description | Lang | Dependencies |
| --- | --- | --- | --- |
| [batlvl](src/batlvl) | Displays the battery level as a percentage. | sh |
| [imv-hyprpaper](src/imv-hyprpaper) | Pick wallpapers quickly. | sh | hyprpaper v0.8.0+, imv, jq |
| [rofi-search](src/rofi-search) | Make requests to search engines. | sh | jq, rofi, socat, xdg-utils |
| [su1-waybar-hycp](src/su1-waybar-hycp) | Sends SIGUSR1 to Waybar based on cursor position being on a screen edge or at one of the endpoints of a screen edge. The action performed by Waybar when it receives SIGUSR1 is determined by the `on-sigusr1` config option (defaults to `toggle`). | sh | jq |
| [swi-hyprpaper](src/swi-hyprpaper) | Pick wallpapers quickly. | sh | hyprpaper v0.8.0+, jq, swayimg v5.0+ |
| [x-hpp-sess](src/x-hpp-sess) | Start the x-hyprpaper session. | sh | jq |

## Usage

Clone the repository and move into it, then inspect the usage of any script in the [list](#list):
```sh
grep '^###' src/<name> | cut -c4-
```

`<name>` is the name of the script to inspect.
