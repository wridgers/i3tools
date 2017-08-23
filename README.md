# i3tools

Some tools for [i3](https://i3wm.org/).

## i3-workspace-rename

Dynamically rename current workspace.

```
# default to rofi, with some hardcoded suggestions.
bindsym $mod+Shift+n exec ~/path/to/i3-workspace-rename
# use i3-input
bindsym $mod+Shift+n exec i3-input -F 'exec ~/path/to/i3-workspace-rename %s' -P 'Rename workspace: '
```

## i3-workspace-switcher

Switch workspace by name with rofi. Also makes a new workspace.

```
bindsym $mod+n exec ~/path/to/i3-workspace-switcher
```
