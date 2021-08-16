---
description: How to add a new category on the items menu
---

# Create a new category

{% hint style="danger" %}
If you change the material of the category you have to add it into the materials/aas\_materials
{% endhint %}

{% hint style="info" %}
For add a new category you have to go into the file sh\__advanced\_config.lua_
{% endhint %}

```lua
["mainMenu"] = {
    [1] = {
        ["uniqueName"] = "All",
        ["material"] = Material("aas_materials/ass_icon_all.png", "smooth"),
        ["all"] = true,
        ["margin"] = 0,
        ["bone"] = "ValveBiped.Bip01_Head1",
    },
    [2] = {
        ["uniqueName"] = "Hat",
        ["material"] = Material("aas_materials/ass_icon_hat.png", "smooth"),
        ["margin"] = 0.006,
        ["bone"] = "ValveBiped.Bip01_Head1",
    }, 
    [3] = {
        ["uniqueName"] = "Glasses",
        ["material"] = Material("aas_materials/ass_icon_glasses.png", "smooth"),
        ["margin"] = 0.005,
        ["bone"] = "ValveBiped.Bip01_Neck1",
    },
    [4] = {
        ["uniqueName"] = "Face Mask",
        ["material"] = Material("aas_materials/aas_mask_2.png", "smooth"),
        ["margin"] = 0.008,
        ["bone"] = "ValveBiped.Bip01_Head1",
    },
    [5] = {
        ["uniqueName"] = "Mouse Mask",
        ["material"] = Material("aas_materials/ass_mask_1.png", "smooth"),
        ["margin"] = 0.008,
        ["bone"] = "ValveBiped.Bip01_Head1",
    },
    [6] = {
        ["uniqueName"] = "BackPack",
        ["material"] = Material("aas_materials/ass_icon_bag.png", "smooth"),
        ["margin"] = 0.01,
        ["bone"] = "ValveBiped.Bip01_Spine",
    },
    -- https://wiki.facepunch.com/gmod/ValveBiped_Bones
    
    -- [7] = {
    --  ["uniqueName"] = "Test Name",
    --  ["material"] = Material("aas_materials/ass_icon_test.png", "smooth"),
    --  ["margin"] = 0.01,
    --  ["bone"] = "ValveBiped.Bip01_Spine",
    },
},
```



