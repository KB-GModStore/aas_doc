---
description: How to add a language
---

# Add a language

{% hint style="info" %}
Firstly you need to take the english file on gmodstore
{% endhint %}

![Secondly you need to create a file into **advanced\_accessories/languages/** folder](../.gitbook/assets/unknown.png)

```lua
-- Thirdly you need to copy/past the entire english file into your language file
-- Next that you just have to translate all sentence.

AAS.Language["example"] = {
    ["cancel"] = "Cancel",
    ["save"] = "Save Item",
    ["name"] = "Name",
    ["model"] = "Model",
    ...   
}
```

