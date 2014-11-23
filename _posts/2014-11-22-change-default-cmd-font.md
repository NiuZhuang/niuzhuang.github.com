---
layout: post
title: Change default font of cmd.exe to consolas
---

Save below text as .reg file and double click it. Then the font get changed.

```
Windows Registry Editor Version 5.00
[HKEY_CURRENT_USER\Console\%SystemRoot%_system32_cmd.exe]
"WindowSize"=dword:00170058
"ScreenBufferSize"=dword:01900119
"WindowPosition"=dword:0079004b
"ColorTable01"=dword:00235600
"FontSize"=dword:00150000
"FontWeight"=dword:00000190
"FaceName"="Consolas"
"FontFamily"=dword:00000036
```


