---
author: jasonsandlin
title: "PFAccountManagementGetPlayFabIDsFromFacebookInstantGamesIdsRequest"
description: "PFAccountManagementGetPlayFabIDsFromFacebookInstantGamesIdsRequest data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 06/26/2023
---

# PFAccountManagementGetPlayFabIDsFromFacebookInstantGamesIdsRequest  

PFAccountManagementGetPlayFabIDsFromFacebookInstantGamesIdsRequest data model.  

## Syntax  
  
```cpp
typedef struct PFAccountManagementGetPlayFabIDsFromFacebookInstantGamesIdsRequest {  
    const char* const* facebookInstantGamesIds;  
    uint32_t facebookInstantGamesIdsCount;  
} PFAccountManagementGetPlayFabIDsFromFacebookInstantGamesIdsRequest;  
```
  
### Members  
  
**`facebookInstantGamesIds`** &nbsp; const char* const*  
  
Array of unique Facebook Instant Games identifiers for which the title needs to get PlayFab identifiers. The array cannot exceed 25 in length.
  
**`facebookInstantGamesIdsCount`** &nbsp; uint32_t  
  
Count of facebookInstantGamesIds
  
  
## Requirements  
  
**Header:** PFAccountManagementTypes.h
  
## See also  
[PFAccountManagementTypes members](../pfaccountmanagementtypes_members.md)  

  
  
