---
author: jasonsandlin
title: "PFCatalogCatalogPriceAmount"
description: "PFCatalogCatalogPriceAmount data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 03/09/2023
---

# PFCatalogCatalogPriceAmount  

PFCatalogCatalogPriceAmount data model.  

## Syntax  
  
```cpp
typedef struct PFCatalogCatalogPriceAmount {  
    int32_t amount;  
    const char* itemId;  
} PFCatalogCatalogPriceAmount;  
```
  
### Members  
  
**`amount`** &nbsp; int32_t  
  
The amount of the price.
  
**`itemId`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) The Item Id of the price.
  
  
## Requirements  
  
**Header:** PFCatalogTypes.h
  
## See also  
[PFCatalogTypes members](../pfcatalogtypes_members.md)  

  
  
