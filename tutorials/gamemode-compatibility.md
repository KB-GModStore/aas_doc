---
description: How to add a compatibility with your gamemode.
---

# Gamemode Compatibility

​

{% hint style="info" %}
You can modify this function into the file **advanced\__accessories/shared/sh\_functions.lua_**
{% endhint %}

```lua
function PLAYER:AASGetMoney()
    if DarkRP then -- This is the table of your gamemode 
        return self:getDarkRPVar("money") -- This is the function for get the money
    elseif MyGamemode then
        return self:getMyGamemodeMoney()
    end

    return 0
end
```

{% hint style="info" %}
You can modify this function into the **advanced\_accessories/server/sv\_functions.lua**
{% endhint %}

```lua
function PLAYER:AASAddMoney(price)
    if DarkRP then
        self:addMoney(price)
    elseif ix then
        if self:GetCharacter() != nil then
            local money = self:AASGetMoney()
            self:GetCharacter():SetMoney(money + price)
        end
    elseif nut then
        if self:getChar() != nil then
            local money = self:AASGetMoney()
            self:getChar():setMoney(money + price)
        end
    end
end
```



