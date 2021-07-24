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
| string | **text** | The text to break |
| number | **max** | The max of characters by line |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- | :--- |
| string | **newText** | The broken text |

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
| vector | **pos** | The vector to convert | ❌ |
| vector | **offset** | The offset | ❌ |
| angle | **ang** | The angle | ❌ |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- | :--- |
| vector | **newVector** | The converted vector |

### AAS.ConvertAngle(ang, offset)
Convert the angle with the offset

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| angle | **ang** | The angle to convert | ❌ |
| vector | **offset** | The offset | ❌ |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- | :--- |
| angle | **newAng** | The converted angle |

### AAS.GetTableById(uniqueId)
Get the item table from the uniqueId

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| number | **uniqueId** | The uniqueId where you want to get the item table | ❌ |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- | :--- |
| table | [itemTable](../../data/itemTable.md) | The item table (or **{}** if not found) |