# toolexec
execute terminal applications into a live terminal using desktop files

toolexec file should be placed in /usr/bin

example usage
```[Desktop Entry]
Name=nmap
Comment=Network exploration or security auditing
Encoding=UTF-8
Exec=toolexec "nmap"
Icon=nmap.png
StartupNotify=false
Terminal=true
Type=Application
```

```toolexec "nmap"```
