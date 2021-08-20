---
description: You can see some accessories functions
---

# Accessories

## PLAYER:AASEquipAccessory\(uniqueId, noNotify\)

Equip the accesorry

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to equip | ❌ |
| [number](https://www.lua.org/pil/2.3.html) | **noNotify** | If you don't want to notify the player | ✔️ |

## PLAYER:AASUnEquipAccessoryById\(uniqueId\)

Unequip an accessory by item uniqueId

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to unequip | ❌ |

## PLAYER:AASUnEquipAccessories\(category\)

Unequip the accesorry

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **category** | The category of the item you wish to unequip | ❌ |

## PLAYER:AASUnEquipAllAccessory\(\)

Unequip all player accessories

## PLAYER:AASSendAllAccessory\(\)

Send all accessories of all players to a specific player

## PLAYER:AASSaveModelItem\(\)

Save the player last model and all equiped items

## PLAYER:AASReloadModelItem\(\)

Reload the player last model and all last equiped items

