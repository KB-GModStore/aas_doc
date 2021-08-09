---
description: You can see some inventory functions
---

# Inventory

## AAS.GetInventoryByCategory(category)

Return a table with all bought items in the category

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **category** | The category of items you want to get | ❌ |

Return :

| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| [table](https://www.lua.org/pil/2.5.html) | **categoryItems** | Contain all bought items in the category |

## AAS.CountInventory()

Get the number of bought items

Return :

| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **count** | The number of bought items |

## AAS.ItemIsBought(uniqueId)

Return if the [LocalPlayer](https://wiki.facepunch.com/gmod/Global.LocalPlayer) has bought the item

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to check if is bought | ❌ |

Return :

| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| [boolean](https://www.lua.org/pil/2.2.html) | **isBought** | If the item is bought |