---
description: You can see some utils functions
---

# Utils

## AAS.CheckCategory\(category\)

Return if the category exists

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | **category** | The category name to check | ❌ |

## AAS.formatMoney\(money\)

Format the money to [string](https://www.lua.org/pil/2.4.html) and add the currency

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **money** | The money to format | ❌ |

Return :

| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| [string](https://www.lua.org/pil/2.4.html) | money | The formated money |

## PLAYER:AASGetMoney\(\)

Return the player money

Return :

| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | money | The player money |

## PLAYER:AASAddMoney\(\)

Add or remove to player some money

{% hint style="info" %}
If you want to remove to player money, you have to set a **negative number**
{% endhint %}

| Types | Arguments | Descriptions | Optional |
| :--- | :--- | :--- | :--- |
| [number](https://www.lua.org/pil/2.3.html) | **money** | The money to add or remove | ❌ |

