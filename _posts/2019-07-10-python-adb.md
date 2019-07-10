---
layout:       post
title:           Python and ADB tool
category:     blog
description:  Use Python to execute adb commands
---

Use Python to execute adb commands for controling mobile like smart phone and tablet.

### Install
[Python link](https://www.python.org/downloads/)
[adb link](https://developer.android.com/studio/releases/platform-tools "adb link")
Here is Windows
pppppp1

### Command
adb command to get list of connected devices:
```shell
adb devices
```

### Start developing
1. Create a Python file in adb tool folder
ppppp2

2. edit Python file

```python
import os

# define adb cmd
adb = 'adb devices'
# execute cmd
os.system(adb)
# wait until press enter for Observed result
os.system("pause")


```

### Demo result
double click to execute python
pppppp3
