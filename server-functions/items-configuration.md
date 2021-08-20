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
| [boolean](https://www.lua.org/pil/2.2.html) | **noSendInformation** | If you don't want to send the item informations to the player | ✔️ |
| [boolean](https://www.lua.org/pil/2.2.html) | **checkIfExist** | If you don't want to recreate the item if it exists (internally call **AAS.ItemExist** for check if the item exists) | ✔️ |
| [boolean](https://www.lua.org/pil/2.2.html) | **baseItem** | If the item is by default | ✔️ |

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

