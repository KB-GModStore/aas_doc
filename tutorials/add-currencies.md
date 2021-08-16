---
description: Add a new currencies for the AAS.formatMoney()
---

# Add Currencies

{% hint style="info" %}
For add a currency you have to go into the sh\_config.lua
{% endhint %}

```lua
--[[ You can add more currency here ]]
AAS.Currencies = {
    ["$"] = function(money)
        return "$"..money
    end,
    ["€"] = function(money)
        return money.."€"
    end
    --["%"] = function(money)
        --return money.."%"
    --end
}
```

