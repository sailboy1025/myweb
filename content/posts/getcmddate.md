---
title: "cmd shortcut"
date: 2023-07-15T20:24:45-04:00
draft: false
tags: ['code']
---
## A quick way to get MD dateformat in clip board

In cmd.

```
powershell -command "Get-Date -Format 'yyyy-MM-ddTHH:mm:ssK' | clip"
```