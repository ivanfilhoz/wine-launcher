wine-launcher
=============

A simple launcher for Wine which converts regular Unix paths into Wine paths (Z:\\). Use it in your .desktop files.

\# wine-launcher.py
\# 
\# Script created by Ivan Filho (ivanslf@gmail.com)
\# 
\# Put into your home folder (~) and edit/create a new .desktop file
\# 
\# Usage:
\#
\#   Exec=python ~/wine-launcher.py App.exe %F [arg1] [...]
\#
\# Each Unix file path (/) will be converted into Wine path format (Z:\\)
[...]
