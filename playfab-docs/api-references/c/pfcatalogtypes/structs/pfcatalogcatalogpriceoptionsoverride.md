---
author: jasonsandlin
title: "PFCatalogCatalogPriceOptionsOverride"
description: "PFCatalogCatalogPriceOptionsOverride data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFCatalogCatalogPriceOptionsOverride  

PFCatalogCatalogPriceOptionsOverride data model.  

## Syntax  
  
```cpp
typedef struct PFCatalogCatalogPriceOptionsOverride {  
    PFCatalogCatalogPriceOverride const* prices;  
    uint32_t pricesCount;  
} PFCatalogCatalogPriceOptionsOverride;  
```
  
### Members  
  
**`prices`** &nbsp; [PFCatalogCatalogPriceOverride](pfcatalogcatalogpriceoverride.md) const*  
*may be nullptr*  
  
(Optional) The prices utilized in the override.
  
**`pricesCount`** &nbsp; uint32_t  
  
Count of prices
  
  
## Requirements  
  
**Header:** PFCatalogTypes.h
  
## See also  
[PFCatalogTypes members](../pfcatalogtypes_members.md)  

  
  
