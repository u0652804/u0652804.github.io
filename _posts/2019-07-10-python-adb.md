---
layout:       post
title:        Python and ADB tool(1)
category:     blog
description:  Use Python to execute adb commands(1)
---

Use Python to execute adb commands for controling mobile like smart phone and tablet.
### Idea
Execute adb by Python must let there in same directory.
kinds:
1. Put Python file in adb tool directory before execute.(Use case)
2. When executing Python file, change execute directory to adb tool directory.
3. Setted adb tool in Environment Variable before coding.

### Install
[Python link](https://www.python.org/downloads/)
[adb link](https://developer.android.com/studio/releases/platform-tools "adb link")
Here is Windows
![p1](https://github.com/u0652804/u0652804.github.io/blob/master/images/other/up_res/Python_adb/Python_adb_p1.png?raw=true "p1")

### Command
adb command to get list of connected devices:
```shell
adb devices
```

### Start developing
1. Create a Python file in adb tool folder
![p2](https://github.com/u0652804/u0652804.github.io/blob/master/images/other/up_res/Python_adb/Python_adb_p2.png?raw=true "p2")

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
![p3](https://github.com/u0652804/u0652804.github.io/blob/master/images/other/up_res/Python_adb/Python_adb_p3.png?raw=true "p3")
