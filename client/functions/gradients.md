---
description: You can see some functions used for gradients
---
# Gradients Functions

### AAS.SimpleLinearGradient(x, y, w, h, startColor, endColor)
A simple linear gradient with just two offsets

{% hint style="info" %}
This function need to be declared in a render hook
{% endhint %}

| Types | Arguments | Descriptions |
| :--- | :--- | :--- |
| number | **x** | The X position of the linear gradient |
| number | **y** | The Y position of the linear gradient |
| number | **w** | The width of the linear gradient |
| number | **h** | The height of the linear gradient |
| color | **startColor** | The start color of the gradient (up) |
| color | **endColor** | The end color of the gradient (down) |

Example :

```lua
hook.Add("HUDPaint", "AAS:Documentation:SimpleLinearGradient", function()
    AAS.SimpleLinearGradient(300, 200, 50, 100, Color(255, 255, 255), Color(0, 0, 0))
end)
```

### AAS.LinearGradient(x, y, w, h, offsets)
A linear gradient with custom offsets

{% hint style="info" %}
This function need to be declared in a render hook
{% endhint %}

| Types | Arguments | Descriptions |
| :--- | :--- | :--- |
| number | **x** | The X position of the linear gradient |
| number | **y** | The Y position of the linear gradient |
| number | **w** | The width of the linear gradient |
| number | **h** | The height of the linear gradient |
| table | **offsets** | List of offsets to be in the linear gradient |

Offset table structure :
| Types | Indexs | Descriptions |
| :--- | :--- | :--- |
| number | **offset** | In **range 0-1**, the position in the linear gradient |
| color | **color** | The color of the offset |

Example :

```lua
local offsets = {
    {offset = 0, color = Color(255, 255, 255)}, 
    {offset = 0.4, color = Color(255, 0, 255)}, 
    {offset = 1, color = Color(0, 0, 0)}
}

hook.Add("HUDPaint", "AAS:Documentation:LinearGradient", function()
    AAS.LinearGradient(800, 500, 75, 300, offsets)
end)
```