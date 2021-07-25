---
description: You can see the item options table base structure
---
# Item Jobs
The table contains all item base options.

<!--  If the item is desactivate all users who bought it can equip it -->

### Table Structure
| Types | Parameters | Descriptions
| :--- | :--- | :--- |
| [boolean](https://www.lua.org/pil/2.2.html) | new | If the tag "new" is visible |
| [boolean](https://www.lua.org/pil/2.2.html) | vip | If the tag "vip" is visible |
| [boolean](https://www.lua.org/pil/2.2.html) | activate | If the item is activate (is visible in the market) |
| [Color](https://wiki.facepunch.com/gmod/Color) | color | The item color |
| [string](https://www.lua.org/pil/2.4.html) | bone | The bone that the the item follow |