# remotemaps
 .remotemap files for Reason's devices.

1. Check if the RE/device is already in here.
2. Do a pullrequest formatted as they are in here.
3. Maximum of 119 parameters per bank are allowed.

```
Scope	DeviceName		com.Dev.Device

Map	1		param1
<---->
Map	119		param119

Please make sure it's Map,1tab,Number,2tabs,Name
```

For ease of use I made a small script.

Paste the entire content of the textfile you get from "File -> Export Device Remote Info" in Reason.

[LINK](mjxl.net/txt2remote)