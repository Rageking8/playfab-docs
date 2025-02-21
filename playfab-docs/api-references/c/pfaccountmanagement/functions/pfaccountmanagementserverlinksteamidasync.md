---
author: jasonsandlin
title: "PFAccountManagementServerLinkSteamIdAsync"
description: "Links the Steam account associated with the provided Steam ID to the user's PlayFab account"
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 09/25/2023
---

# PFAccountManagementServerLinkSteamIdAsync  

Links the Steam account associated with the provided Steam ID to the user's PlayFab account  

## Syntax  
  
```cpp
HRESULT PFAccountManagementServerLinkSteamIdAsync(  
    PFEntityHandle titleEntityHandle,  
    const PFAccountManagementLinkSteamIdRequest* request,  
    XAsyncBlock* async  
)  
```  
  
### Parameters  
  
**`titleEntityHandle`** &nbsp; PFEntityHandle  
  
PFEntityHandle for a title Entity obtained using PFAuthenticationGetEntityWithSecretKeyAsync.  
  
**`request`** &nbsp; [PFAccountManagementLinkSteamIdRequest*](../../pfaccountmanagementtypes/structs/pfaccountmanagementlinksteamidrequest.md)  
  
Populated request object.  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation.
  
## Remarks  
  
This API is available on Win32. See also ServerLoginWithSteamIdAsync, ServerUnlinkSteamIdAsync. Call XAsyncGetStatus to get the status of the operation. If the service call is unsuccessful, the async result will be E_PF_ACCOUNT_ALREADY_LINKED, E_PF_INVALID_STEAM_TICKET, E_PF_LINKED_ACCOUNT_ALREADY_CLAIMED, E_PF_STEAM_NOT_ENABLED_FOR_TITLE, E_PF_STEAM_USER_NOT_FOUND or any of the global PlayFab Service errors. See doc page "Handling PlayFab Errors" for more details on error handling.
  
## Requirements  
  
**Header:** PFAccountManagement.h
  
## See also  
[PFAccountManagement members](../pfaccountmanagement_members.md)  

  
  
