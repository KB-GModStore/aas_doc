---
description: You can see some notifications UI functions
---

# Notifications

## AAS.Notification\(time, msg\)

Send a notification to the [LocalPlayer](https://wiki.facepunch.com/gmod/Global.LocalPlayer)

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | time | Notification display time | ❌ |
| [string](https://www.lua.org/pil/2.4.html) | msg | The notification message content | ❌ |

Example :

```lua
AAS.Notification(5, "Hello world !")
```

Output :

![](../.gitbook/assets/notification.png)

