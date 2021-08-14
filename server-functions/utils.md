---
description: You can see some utils functions
---

# Utils

## PLAYER:AASModelEquiped(model)

Return if the player has the model equiped

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **model** | The model | ❌ |

Return :

| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| [boolean](https://www.lua.org/pil/2.2.html) | isEquiped | If the player has the model equiped |

## AAS.ItemExists(model, skin)

Return if the item exists by it model and skin

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **model** | The item model | ❌ |
| [number](https://www.lua.org/pil/2.3.html) | **radius** | The item skin | ❌ |

Return :

| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| [boolean](https://www.lua.org/pil/2.2.html) | exists | If the item exists |

## PLAYER:AASCheckDistEnt\(class, radius\)
Return if a certain entity class is near the player

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **class** | The entity class | ❌ |
| [number](https://www.lua.org/pil/2.3.html) | **radius** | The max distance between the player and the entity | ❌ |

## PLAYER:AASCheckJob(uniqueId)
Return if the player has the good job for interact with the item

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to unequip | ❌ |