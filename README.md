# StoneRose for Ghostty

Soft color theme with stony blues and rosy reds.

## Installation

Download the theme into Ghostty's custom theme directory:

```sh
mkdir -p "${XDG_CONFIG_HOME:-$HOME/.config}/ghostty/themes"
curl -fsSL https://raw.githubusercontent.com/ajguerrer/stonerose-ghostty/main/themes/StoneRose \
  -o "${XDG_CONFIG_HOME:-$HOME/.config}/ghostty/themes/StoneRose"
```

Add or update the theme setting in your Ghostty configuration:

```ini
theme = StoneRose
```

Configuration locations:

- **macOS:** `~/Library/Application Support/com.mitchellh.ghostty/config.ghostty`
- **Linux:** `${XDG_CONFIG_HOME:-$HOME/.config}/ghostty/config.ghostty`

Older installations may use a file named `config` instead.

Reload the configuration with **Cmd+Shift+,** on macOS or **Ctrl+Shift+,** on Linux. If Ghostty is closed, the theme loads when you launch it.

See the [Ghostty configuration documentation](https://ghostty.org/docs/config) for details.

## License

MIT. See [LICENSE](LICENSE).
