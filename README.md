# Host specific configuration for fish

This fisherman plugin gives fish support for host specific configuration.

This plugin will automatically source a file defined in `~/.config/fish/hosts/(hostname|cut -d . -f 1).fish` if it exists

## Install

Install as a fisherman plugin

```
fisher rcoedo/host-conf-fish
```
