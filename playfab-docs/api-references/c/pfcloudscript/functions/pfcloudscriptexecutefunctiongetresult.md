---
author: jasonsandlin
title: "PFCloudScriptExecuteFunctionGetResult"
description: "Gets the result of a successful PFCloudScriptExecuteFunctionAsync call."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFCloudScriptExecuteFunctionGetResult  

Gets the result of a successful PFCloudScriptExecuteFunctionAsync call.  

## Syntax  
  
```cpp
HRESULT PFCloudScriptExecuteFunctionGetResult(  
    XAsyncBlock* async,  
    size_t bufferSize,  
    void* buffer,  
    PFCloudScriptExecuteFunctionResult** result,  
    size_t* bufferUsed  
)  
```  
  
### Parameters  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
**`bufferSize`** &nbsp; size_t  
  
The size of the buffer for the result object.  
  
**`buffer`** &nbsp; void*  
*_Out_writes_bytes_to_(bufferSize,*bufferUsed)*  
  
Byte buffer used for the result value and its fields.  
  
**`result`** &nbsp; [PFCloudScriptExecuteFunctionResult**](../../pfcloudscripttypes/structs/pfcloudscriptexecutefunctionresult.md)  
*library-allocated output*  
  
Pointer to the result object.  
  
**`bufferUsed`** &nbsp; size_t*  
*optional output*  
  
The number of bytes in the provided buffer that were used.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation. If the service call is unsuccessful, the result will be E_PF_CLOUD_SCRIPT_AZURE_FUNCTIONS_ARGUMENT_SIZE_EXCEEDED, E_PF_CLOUD_SCRIPT_AZURE_FUNCTIONS_EXECUTION_TIME_LIMIT_EXCEEDED, E_PF_CLOUD_SCRIPT_AZURE_FUNCTIONS_HTTP_REQUEST_ERROR, E_PF_CLOUD_SCRIPT_AZURE_FUNCTIONS_QUEUE_REQUEST_ERROR, E_PF_CLOUD_SCRIPT_AZURE_FUNCTIONS_RETURN_SIZE_EXCEEDED, E_PF_INVALID_ENTITY_TYPE or any of the global PlayFab Service errors. See doc page "Handling PlayFab Errors" for more details on error handling.
  
## Remarks  
  
result is a pointer within buffer and does not need to be freed separately.
  
## Requirements  
  
**Header:** PFCloudScript.h
  
## See also  
[PFCloudScript members](../pfcloudscript_members.md)  

  
  
