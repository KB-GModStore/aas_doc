---
description: You can see some purchasing functions
---

# Purchasing

## PLAYER:AASBuyItem\(uniqueId\)

Buy an accessory

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to purchase | ❌ |

## PLAYER:AASSellItem\(uniqueId\)

Sell an accessory

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to sell | ❌ |

## PLAYER:AASIsBought\(uniqueId\)

Return if the player have bought an item

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to check | ❌ |

Return :

| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| [boolean](https://www.lua.org/pil/2.2.html) | **haveBought** | If the player have bought the item |

