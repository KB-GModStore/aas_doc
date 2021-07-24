---
description: You can see some functions used for some things
---
# Utils Functions

### AAS.BreakText(text, max)
Break with \n the text after x characters in the line

| Types | Arguments | Descriptions |
| :--- | :--- | :--- |
| string | **text** | The text to break |
| number | **max** | The max of characters by line |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| string | newText | The broken text |

### AAS.ConvertVector(pos, offset, ang)
Convert the vector with the offset

| Types | Arguments | Descriptions |
| :--- | :--- | :--- |
| vector | **pos** | The vector to convert |
| vector | **offset** | The offset |
| angle | **ang** | The angle |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| vector | newVector | The converted vector |

### AAS.ConvertAngle(ang, offset)
Convert the angle with the offset

| Types | Arguments | Descriptions |
| :--- | :--- | :--- |
| angle | **ang** | The angle to convert |
| vector | **offset** | The offset |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| angle | newAng | The converted angle |

### AAS.GetTableById(uniqueId)
Get the item table from the uniqueId

| Types | Arguments | Descriptions |
| :--- | :--- | :--- |
| number | **uniqueId** | The uniqueId where you want to get the item table |

Return :
| Types | Parameters | Descriptions |
| :--- | :--- | :--- |
| table | [itemTable](./data/itemTable.md) | The item table (or **{}** if not found) |