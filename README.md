```sed
s/((Cavemen|Point (.*?\b )?Grunt|Pointy|Mous(e|y|ey)) )?GUI/CLI\/TUI\/keyboard driven GUI/g
s/Proprietary bloat/FLOSS+POSIX+unix_philosophy/g
s/(binary|BLOB(s)?) formats/plain-text based formats/g
s/((Shift-)|(Ctrl-)|(Alt-))*(\w)/${2:+S-}${3:+C-}${4:+A-}\L$5\E/g
s/Ctrl-Y/Ctrl-Shift-Z/g
s/Ctrl-Shift-Z/C-S-z/g
```

```sed
s/MS (Word|PowerPoint)|LibreOffice (Writer|Impress)/markup-based tools/
s/MS Access/Sql/g
s/cmd/msys2 bash/g
s/bash/bash with powershell like improvements/g
s/MS Explorer/doublecmd/g
s/MS Windows 11 Tiling/dwm-port/g
s/(w3(.org) )?(X)?HTML (?(3)1|5)?/whatwg XHTML5/g
s/MS Windows/??/
s/Postman/curl\/humao HTTP Rest Client/
```

```sed
s/Google Play Store/F-droid/g
s/Google Photos/tibbi Simple Gallery/g
s/Google Messages/QKSMS/g
s/Google Keyboard/??/g
s/Goole Dialer/??/g
s/Google Contacts/OpenContacts/g
s/(Google funded )?Mozilla Firefox/LibreWolf/g
s/Google Android/??/g
```

```sed
s/(Rubber Dome|Mechanical) Switches/Scissor Switches/g
s/Staggered layout/Orthogonal layout/g
```

```sed
s/Trends/Modesty\/Culture\/Comfort/gi
s/Looks\/Appearance/Functionality/gi
s/Convenience/Guided Correctness/gi
s/Vagance/Attention/gi
```
