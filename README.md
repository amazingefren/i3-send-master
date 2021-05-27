# i3-send-master

Simple Script for sending focused window to biggest container

Like *bspc...biggest.window*
OR *master/stack layout* **minus the layout**

### Dependencies
- [i3ipc-python](https://github.com/altdesktop/i3ipc-python)
- [i3-gaps](https://github.com/Airblader/i3)
- [python3](https://www.python.org/)
### Executable Permissions
```
$ chmod +x ./i3-send-master
```
### i3 Config Bind
```
$ bindsym KEY exec --no-startup-id $PATH/i3-send-master
```
