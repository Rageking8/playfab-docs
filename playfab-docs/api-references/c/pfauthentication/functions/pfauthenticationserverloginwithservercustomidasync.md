---
author: jasonsandlin
title: "PFAuthenticationServerLoginWithServerCustomIdAsync"
description: "Securely login a game client from an external server backend using a custom identifier for that player. Server Custom ID and Client Custom ID are mutually exclusive and cannot be used to retrieve the same player account."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 09/25/2023
---

# PFAuthenticationServerLoginWithServerCustomIdAsync  

Securely login a game client from an external server backend using a custom identifier for that player. Server Custom ID and Client Custom ID are mutually exclusive and cannot be used to retrieve the same player account.  

## Syntax  
  
```cpp
HRESULT PFAuthenticationServerLoginWithServerCustomIdAsync(  
    PFServiceConfigHandle serviceConfigHandle,  
    const char* secretKey,  
    const PFAuthenticationLoginWithServerCustomIdRequest* request,  
    XAsyncBlock* async  
)  
```  
  
### Parameters  
  
**`serviceConfigHandle`** &nbsp; PFServiceConfigHandle  
  
PFServiceConfigHandle returned from PFServiceConfigCreateHandle call.  
  
**`secretKey`** &nbsp; char*  
*_In_z_*  
  
Title Secret Key used to authenticate the service request.  
  
**`request`** &nbsp; [PFAuthenticationLoginWithServerCustomIdRequest*](../../pfauthenticationtypes/structs/pfauthenticationloginwithservercustomidrequest.md)  
  
Populated request object.  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation.
  
## Remarks  
  
This API is available on Win32. When the asynchronous task is complete, call [PFAuthenticationServerLoginWithServerCustomIdGetResult](pfauthenticationserverloginwithservercustomidgetresult.md) to get the result.
  
## Requirements  
  
**Header:** PFAuthentication.h
  
## See also  
[PFAuthentication members](../pfauthentication_members.md)  

  
  
