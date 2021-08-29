---
description: The list of console commands for items
---

# Items

{% hint style="warning" %}
All console commands needs to be called by a superadmin player or by the server console !
{% endhint %}

Remove all entities \(Called [AAS.RemoveEntity](../server-functions/entities-saving.md) internally\)

## aas\_reload\_basicitem

Reload all basic items \(preconfigured items by workshop id\)

{% hint style="warning" %}
Just this console command need to be called clientside !
{% endhint %}

## aas_sh_item_to_aas

Transfer all sh accessories items to aas items

## aas\_give\_items\_steamid64\(steamid64, uniqueId\)

Give an item to a player by the steamid4

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **steamid64** | The player steamid64 who you want to give the item | ❌ |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to give | ❌ |

## aas\_save\_item\_data

Save the item list in a data file (Called [AAS.ConvertSqlToDataTable](../server-functions/utils.md) internally)

## aas_sh_inventory_to_aas

Transfer all sh accessories inventories to aas inventories