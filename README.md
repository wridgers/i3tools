# i3tools

Some tools for [i3](https://i3wm.org/).

## i3-workspace-rename

Dynamically rename workspace.

```
# default to rofi, with some hardcoded suggestions.
bindsym $mod+n exec ~/path/to/i3-workspace-rename
# use i3-input
bindsym $mod+n exec i3-input -F 'exec ~/path/to/i3-workspace-rename %s' -P 'Rename workspace: '
```

## i3-workspace-switcher

Switch workspace with rofi.

```
bindsym $mod+Shift+n exec ~/path/to/i3-workspace-switcher
```
