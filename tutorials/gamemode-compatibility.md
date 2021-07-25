---
description: How to add a compatibility with your gamemode.
---

# Gamemode Compatibility

​

{% hint style="info" %}
You can modify there functions into the folder advanced\__accessories/shared/sh\_functions_
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

function PLAYER:AASAddMoney(price)
    if DarkRP then
        return self:addMoney(price)
    elseif MyGamemode then -- This is the table of your gamemode 
        return self:setMyGamemodeMoney(price) -- This is the function for get the money
    end
end
```



