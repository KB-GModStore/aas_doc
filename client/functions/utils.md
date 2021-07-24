---
description: You can see some utils functions
---
# Utils Functions

### AAS.LoadFonts()
Load addon fonts

### AAS.BreakText(text, max)
Break with \n the text after x characters in the line

{% hint style="warning" %}
You need to use the function in the **[draw.DrawText](https://wiki.facepunch.com/gmod/draw.DrawText)** function
{% endhint %}

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **text** | The text to break |
| [number](https://www.lua.org/pil/2.3.html) | **max** | The max of characters by line |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **newText** | The broken text |

Example:
```lua
local text = "Lorem ipsum dolor sit amet, consectetur."

local breakText = AAS.BreakText(text, 25) -- Return a text with max 25 characters by lines
hook.Add("HUDPaint", "AAS:Documentation:BreakText", function()
    
    print(breakText)
    draw.DrawText(breakText, "DermaDefault", ScrW()/2, 50, Color(255, 255, 255), TEXT_ALIGN_CENTER)
end)
```
Output:
```bash
Lorem ipsum dolor sit\n
amet, consectetur.
```

### AAS.ConvertVector(pos, offset, ang)
Convert the vector with the offset

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [Vector](https://wiki.facepunch.com/gmod/Vector) | **pos** | The vector to convert | ❌ |
| [Vector](https://wiki.facepunch.com/gmod/Vector) | **offset** | The offset | ❌ |
| [Angle](https://wiki.facepunch.com/gmod/Angle) | **ang** | The angle | ❌ |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- | :--- |
| [Vector](https://wiki.facepunch.com/gmod/Vector) | **newVector** | The converted vector |

### AAS.ConvertAngle(ang, offset)
Convert the angle with the offset

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [Angle](https://wiki.facepunch.com/gmod/Angle) | **ang** | The angle to convert | ❌ |
| [Vector](https://wiki.facepunch.com/gmod/Vector) | **offset** | The offset | ❌ |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- | :--- |
| [Angle](https://wiki.facepunch.com/gmod/Angle) | **newAng** | The converted angle |

### AAS.GetTableById(uniqueId)
Get the item table from the uniqueId

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **uniqueId** | The uniqueId where you want to get the item table | ❌ |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- | :--- |
| [itemTable](/structs/item-table.md) | itemTable | The item table (or **{}** if not found) |