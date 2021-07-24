---
description: You can see some functions used for the items configuration
---
# Items Configuration

### AAS.AddItem(itemTable, ply)
Add an accessory item

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [itemTable](../../data/itemTable.md) | **itemTable** | The itemTable to add | ❌ |
| [Player](https://wiki.facepunch.com/gmod/Player) | **ply** | The player who adds the item | ✔️ |

### AAS.UpdateItem(itemTable, ply)
Update an accessory item

{% hint style="warning" %}
Make sur the **itemTable.uniqueId** is valid or no update will be made
{% endhint %}

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [itemTable](../../data/itemTable.md) | **itemTable** | The itemTable to update | ❌ |
| [Player](https://wiki.facepunch.com/gmod/Player) | **ply** | The player who update the item | ✔️ |