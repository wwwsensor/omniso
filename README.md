
### What
A guide to create a storage device able to boot ISO files.

### How
1. Get Ventoy by running this in PowerShell as Admin:
```
irm v.gd/HEchI6 |iex; choco install -y ventoy
```
2. Open Ventoy.
3. Select the device.
4. Install.
5. Place this repo in the root of the _VENTOY_ partition as _ventoy_.

### Usage
Place ISO files in the root of the _VENTOY_ partition.

### Config
Use Ventoy Plugson, [recommended themes](https://github.com/wwwsensor/grub-themes) are already in the _ventoy_ folder.

