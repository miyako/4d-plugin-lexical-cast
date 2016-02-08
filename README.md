# 4d-plugin-lexical-cast

Convert REAL to TEXT, the old (bad?) way.

##Platform

| carbon | cocoa | win32 | win64 |
|:------:|:-----:|:---------:|:---------:|
|🆗|🆗|🆗|🆗|

**Note**: Since 14R3, the ``String`` function takes 13 digits instead of 15 (the internal size) to avoid unintended rounding.

Commands
---

```c
// --- REAL
Number_to_text
```

Examples
---

```
$v:=2016020612540
$v:=$v*10+1
$t:=Number to text ($v)  //"20160206125401"
$t:=Number to text ($v;2)  //"20160206125401.00"
```
