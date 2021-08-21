---
description: You can see some offsets functions
---

# Offsets

## PLAYER:AASSendAllOfsets()

Send all player offsets to the player

## PLAYER:AASSaveOffsets(uniqueId, pos, ang, scale)

Save player personal item offsets

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to save offsets | ❌ |
| [Vector](https://wiki.facepunch.com/gmod/Vector) | **pos** | The offset pos | ✔️ |
| [Angle](https://wiki.facepunch.com/gmod/Angle) | **ang** | The offset angle | ✔️ |
| [Vector](https://wiki.facepunch.com/gmod/Vector) | **scale** | The offset scale | ✔️ |

## PLAYER:AASGetOffsets(uniqueId)

Get player item offset

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The item uniqueId to get offsets | ❌ |

Return :

| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| [offsetTable](../structs/offset-table.md) | **offsetTable** | The item offsets table |

