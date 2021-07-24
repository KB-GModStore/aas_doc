---
description: A Model derived of a DModelPanel
---
# AAS:DModel

### PANEL:SetDrawModelAccessories(bool)
Set if you want to draw accesories

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| boolean | **bool** | If you want to draw accesories | ❌ |

### PANEL:SetDrawAccessories(uniqueId)
Draw model accessory. Called internally AAS.GetTableById and PANEL:createAccessory.

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| number | **uniqueId** | The item uniqueId what you want to draw | ❌ |

### PANEL:createAccessory(itemTable)
Create the accessory and draw it on the model

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| table | [itemTable](../../../data/itemTable.md) | The item table what you want to draw | ❌ |

### PANEL:RemoveDrawAccessories(uniqueId)
Remove an accessory from the model

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| number | **uniqueId** | The item uniqueId what you want to remove | ❌ |