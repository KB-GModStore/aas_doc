---
description: You can see some functions used for materials
---
# Materials Functions

### AAS.SimpleLinearGradient(number x, number y, number w, number h, color startColor, color endColor)

#### A simple linear gradient with just two offset (0: startColor, 1: endColor)

number **x**: The X position of the linear gradient
number **y**: The Y position of the linear gradient
number **w**: The width of the linear gradient
number **h**: The height of the linear gradient
color **startColor**: The start color of the gradient (up)
color **endColor**: The end color of the gradient (down)

Example :

```lua
hook.Add("HUDPaint", "AAS:Documentation:SimpleLinearGradient", function()
    AAS.SimpleLinearGradient(500, 200, 100, 200, Color(255, 255, 255), Color(0, 0, 0))
end)
```