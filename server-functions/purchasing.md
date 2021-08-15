---
description: You can see some purchasing functions
---

# Purchasing

## PLAYER:AASBuyItem\(uniqueId\)

Buy an accessory

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to purchase | ❌ |

## PLAYER:AASIsBought\(uniqueId\)

Return if the player have bought an item

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to check | ❌ |

## AAS.GiveItem(steamId64, uniqueId, price)

Give an item to the player

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **steamId64** | The player steamid64 who you want to create the accessory | ❌ |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to give | ❌ |
| [number](https://www.lua.org/pil/2.3.html) | **price** |  The item price (used for the sell) | ✔️ (default: 0) |

## PLAYER:AASSellItem\(uniqueId\)

Sell an accessory

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to sell | ❌ |


Return :

| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| [boolean](https://www.lua.org/pil/2.2.html) | **haveBought** | If the player have bought the item |

