---
author: jasonsandlin
title: "PFGroupsUpdateGroupGetResultSize"
description: "Get the size in bytes needed to store the result of a UpdateGroup call."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFGroupsUpdateGroupGetResultSize  

Get the size in bytes needed to store the result of a UpdateGroup call.  

## Syntax  
  
```cpp
HRESULT PFGroupsUpdateGroupGetResultSize(  
    XAsyncBlock* async,  
    size_t* bufferSize  
)  
```  
  
### Parameters  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
**`bufferSize`** &nbsp; size_t*  
*output*  
  
The buffer size in bytes required for the result.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation. If the service call is unsuccessful, the result will be E_PF_GROUP_NAME_NOT_AVAILABLE, E_PF_ROLE_DOES_NOT_EXIST or any of the global PlayFab Service errors. See doc page "Handling PlayFab Errors" for more details on error handling.
  
  
## Requirements  
  
**Header:** PFGroups.h
  
## See also  
[PFGroups members](../pfgroups_members.md)  

  
  
