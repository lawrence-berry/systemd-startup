# Run a script on boot via SystemD Timer units

Copy the other 2 files into /etc/systemd/system/

Then run:

```
sudo systemcl mystartupscript.timer start
sudo systemcl mystartupscript.timer enable
sudo systemcl list-timers
```

Reboot!
