# wine-launcher

A simple launcher for Wine which converts regular Unix paths into Wine paths (Z:\\). Use it in your .desktop files.

## Usage

Put into your home folder (~) and edit/create a new .desktop file:

```
Exec=~/wine-launcher.py App.exe %F [arg1] [...]
```

Each Unix file path (/) will be converted into Wine path format (Z:\\)
