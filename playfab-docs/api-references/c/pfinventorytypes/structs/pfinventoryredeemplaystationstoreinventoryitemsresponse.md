---
author: jasonsandlin
title: "PFInventoryRedeemPlayStationStoreInventoryItemsResponse"
description: "PFInventoryRedeemPlayStationStoreInventoryItemsResponse data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 06/26/2023
---

# PFInventoryRedeemPlayStationStoreInventoryItemsResponse  

PFInventoryRedeemPlayStationStoreInventoryItemsResponse data model.  

## Syntax  
  
```cpp
typedef struct PFInventoryRedeemPlayStationStoreInventoryItemsResponse {  
    PFInventoryRedemptionFailure const* failed;  
    uint32_t failedCount;  
    PFInventoryRedemptionSuccess const* succeeded;  
    uint32_t succeededCount;  
    const char* const* transactionIds;  
    uint32_t transactionIdsCount;  
} PFInventoryRedeemPlayStationStoreInventoryItemsResponse;  
```
  
### Members  
  
**`failed`** &nbsp; [PFInventoryRedemptionFailure](pfinventoryredemptionfailure.md) const*  
*may be nullptr*  
  
(Optional) The list of failed redemptions from the external marketplace.
  
**`failedCount`** &nbsp; uint32_t  
  
Count of failed
  
**`succeeded`** &nbsp; [PFInventoryRedemptionSuccess](pfinventoryredemptionsuccess.md) const*  
*may be nullptr*  
  
(Optional) The list of successful redemptions from the external marketplace.
  
**`succeededCount`** &nbsp; uint32_t  
  
Count of succeeded
  
**`transactionIds`** &nbsp; const char* const*  
*may be nullptr*  
  
(Optional) The Transaction IDs associated with the inventory modifications.
  
**`transactionIdsCount`** &nbsp; uint32_t  
  
Count of transactionIds
  
  
## Requirements  
  
**Header:** PFInventoryTypes.h
  
## See also  
[PFInventoryTypes members](../pfinventorytypes_members.md)  

  
  
