---
author: jasonsandlin
title: "PFAccountManagementUnlinkCustomIDRequest"
description: "PFAccountManagementUnlinkCustomIDRequest data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFAccountManagementUnlinkCustomIDRequest  

PFAccountManagementUnlinkCustomIDRequest data model.  

## Syntax  
  
```cpp
typedef struct PFAccountManagementUnlinkCustomIDRequest {  
    const char* customId;  
    PFStringDictionaryEntry const* customTags;  
    uint32_t customTagsCount;  
} PFAccountManagementUnlinkCustomIDRequest;  
```
  
### Members  
  
**`customId`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) Custom unique identifier for the user, generated by the title. If not specified, the most recently signed in Custom ID will be used.
  
**`customTags`** &nbsp; [PFStringDictionaryEntry](../../pftypes/structs/pfstringdictionaryentry.md) const*  
*may be nullptr*  
  
(Optional) The optional custom tags associated with the request (e.g. build number, external trace identifiers, etc.).
  
**`customTagsCount`** &nbsp; uint32_t  
  
Count of customTags
  
  
## Requirements  
  
**Header:** PFAccountManagementTypes.h
  
## See also  
[PFAccountManagementTypes members](../pfaccountmanagementtypes_members.md)  

  
  
