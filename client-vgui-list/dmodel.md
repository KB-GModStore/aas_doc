---
description: A Model derived of a DModelPanel
---

# AAS:DModel

## PANEL:SetDrawModelAccessories\(bool\)

Set if you want to draw accesories

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [boolean](https://www.lua.org/pil/2.2.html) | **bool** | If you want to draw accesories | ❌ |

## PANEL:SetDrawAccessories\(uniqueId\)

Draw model accessory. Called internally AAS.GetTableById and PANEL:createAccessory.

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId what you want to draw | ❌ |

## PANEL:createAccessory\(itemTable\)

Create the accessory and draw it on the model

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [itemTable](../structs/item-table.md) | **itemTable** | The item table what you want to draw | ❌ |

## PANEL:RemoveDrawAccessories\(uniqueId\)

Remove an accessory from the model

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId what you want to remove | ❌ |

