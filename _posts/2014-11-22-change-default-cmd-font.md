---
layout: post
title: 修改cmd默认字体为consolas
category: default
---

将下面代码存为.reg格式，双击执行，就可以修改字体。

{code}
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
{code}


