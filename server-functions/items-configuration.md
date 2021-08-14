---
description: You can see some functions used for the items configuration
---

# Item Configuration

## AAS.AddItem\(itemTable, ply, noSendInformation\)

Add an accessory

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [itemTable](../structs/item-table.md) | **itemTable** | The itemTable to add | ❌ |
| [Player](https://wiki.facepunch.com/gmod/Player) | **ply** | The player who adds the item | ✔️ |
| [boolean](https://www.lua.org/pil/2.2.html) | **noSendInformation** | If you didn't want to send the item informations to the player | ✔️ |

## AAS.UpdateItem\(itemTable, ply\)

Update an accessory

{% hint style="warning" %}
Make sur the **itemTable.uniqueId** is valid or no update will be made
{% endhint %}

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [itemTable](../structs/item-table.md) | **itemTable** | The itemTable to update | ❌ |
| [Player](https://wiki.facepunch.com/gmod/Player) | **ply** | The player who update the item | ✔️ |

## AAS.DeleteItem\(itemTable, ply\)

Delete an accessory

{% hint style="warning" %}
Make sur the **itemTable.uniqueId** is valid or no delete will be made
{% endhint %}

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [itemTable](../structs/item-table.md) | **itemTable** | The itemTable to delete | ❌ |
| [Player](https://wiki.facepunch.com/gmod/Player) | **ply** | The player who delete the item | ✔️ |

