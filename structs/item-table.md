---
description: You can see the item table structure
---
# Item Table Structure

| Types | Parameters | Descriptions |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **name** | The item name |
| [string](https://www.lua.org/pil/2.4.html) | **description** | The item description |
| [string](https://www.lua.org/pil/2.4.html) | **model** | The item model |
| [itemCategory](../structs/item-categories.md) | **category** | The item category |
| [number](https://www.lua.org/pil/2.3.html) | **price** | The item price |
| [Vector](https://wiki.facepunch.com/gmod/Vector) | **pos** | The item position |
| [Vector](https://wiki.facepunch.com/gmod/Vector) | **scale** | The item scale |
| [Angle](https://wiki.facepunch.com/gmod/Angle) | **ang** | The item angle |
| [itemJobs](../structs/item-jobs.md) | **job** | Jobs who have acces to the item (or all if the table is empty) |
| [itemOptions](../structs/item-categories.md) | **uniqueId** | The item uniqueId |