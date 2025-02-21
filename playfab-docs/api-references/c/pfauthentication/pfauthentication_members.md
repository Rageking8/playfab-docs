---
author: jasonsandlin
title: "Services C API overview - PFAuthentication.h"
description: "Services C API overview - PFAuthentication.h"
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 09/25/2023
---

# Services C API overview - PFAuthentication.h

  
## Functions  

| Function | Description |  
| --- | --- |  
| [PFAuthenticationAuthenticateGameServerWithCustomIdAsync](functions/pfauthenticationauthenticategameserverwithcustomidasync.md) | Create a game_server entity token and return a new or existing game_server entity. |  
| [PFAuthenticationAuthenticateGameServerWithCustomIdGetResult](functions/pfauthenticationauthenticategameserverwithcustomidgetresult.md) | Gets the result of a successful PFAuthenticationAuthenticateGameServerWithCustomIdAsync call. |  
| [PFAuthenticationAuthenticateGameServerWithCustomIdGetResultSize](functions/pfauthenticationauthenticategameserverwithcustomidgetresultsize.md) | Get the size in bytes needed to store the result of a AuthenticateGameServerWithCustomId call. |  
| [PFAuthenticationDeleteAsync](functions/pfauthenticationdeleteasync.md) | Delete a game_server entity. |  
| [PFAuthenticationGetEntityAsync](functions/pfauthenticationgetentityasync.md) | Method to exchange a legacy AuthenticationTicket or title SecretKey for an Entity Token or to refresh a still valid Entity Token. |  
| [PFAuthenticationGetEntityGetResult](functions/pfauthenticationgetentitygetresult.md) | Gets the result of a successful PFAuthenticationGetEntityAsync call. |  
| [PFAuthenticationGetEntityWithSecretKeyAsync](functions/pfauthenticationgetentitywithsecretkeyasync.md) | Method to exchange a legacy AuthenticationTicket or title SecretKey for an Entity Token or to refresh a still valid Entity Token. |  
| [PFAuthenticationGetEntityWithSecretKeyGetResult](functions/pfauthenticationgetentitywithsecretkeygetresult.md) | Gets the result of a successful PFAuthenticationGetEntityWithSecretKeyAsync call. |  
| [PFAuthenticationLoginWithCustomIDAsync](functions/pfauthenticationloginwithcustomidasync.md) | Signs the user in using a custom unique identifier generated by the title, returning a session identifier that can subsequently be used for API calls which require an authenticated user |  
| [PFAuthenticationLoginWithCustomIDGetResult](functions/pfauthenticationloginwithcustomidgetresult.md) | Get the result from a PFAuthenticationLoginWithCustomIDAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationLoginWithCustomIDGetResultSize](functions/pfauthenticationloginwithcustomidgetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationLoginWithCustomIDAsync call. |  
| [PFAuthenticationLoginWithNintendoServiceAccountAsync](functions/pfauthenticationloginwithnintendoserviceaccountasync.md) | Signs in the user with a Nintendo service account token. |  
| [PFAuthenticationLoginWithNintendoServiceAccountGetResult](functions/pfauthenticationloginwithnintendoserviceaccountgetresult.md) | Get the result from a PFAuthenticationLoginWithNintendoServiceAccountAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationLoginWithNintendoServiceAccountGetResultSize](functions/pfauthenticationloginwithnintendoserviceaccountgetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationLoginWithNintendoServiceAccountAsync call. |  
| [PFAuthenticationLoginWithOpenIdConnectAsync](functions/pfauthenticationloginwithopenidconnectasync.md) | Logs in a user with an Open ID Connect JWT created by an existing relationship between a title and an Open ID Connect provider. |  
| [PFAuthenticationLoginWithOpenIdConnectGetResult](functions/pfauthenticationloginwithopenidconnectgetresult.md) | Get the result from a PFAuthenticationLoginWithOpenIdConnectAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationLoginWithOpenIdConnectGetResultSize](functions/pfauthenticationloginwithopenidconnectgetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationLoginWithOpenIdConnectAsync call. |  
| [PFAuthenticationLoginWithPSNAsync](functions/pfauthenticationloginwithpsnasync.md) | Signs the user in using a PlayStation :tm: Network authentication code, returning a session identifier that can subsequently be used for API calls which require an authenticated user |  
| [PFAuthenticationLoginWithPSNGetResult](functions/pfauthenticationloginwithpsngetresult.md) | Get the result from a PFAuthenticationLoginWithPSNAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationLoginWithPSNGetResultSize](functions/pfauthenticationloginwithpsngetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationLoginWithPSNAsync call. |  
| [PFAuthenticationLoginWithSteamAsync](functions/pfauthenticationloginwithsteamasync.md) | Signs the user in using a Steam authentication ticket, returning a session identifier that can subsequently be used for API calls which require an authenticated user |  
| [PFAuthenticationLoginWithSteamGetResult](functions/pfauthenticationloginwithsteamgetresult.md) | Get the result from a PFAuthenticationLoginWithSteamAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationLoginWithSteamGetResultSize](functions/pfauthenticationloginwithsteamgetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationLoginWithSteamAsync call. |  
| [PFAuthenticationLoginWithXboxAsync](functions/pfauthenticationloginwithxboxasync.md) | Signs the user in using a Xbox Live Token, returning a session identifier that can subsequently be used for API calls which require an authenticated user |  
| [PFAuthenticationLoginWithXboxGetResult](functions/pfauthenticationloginwithxboxgetresult.md) | Get the result from a PFAuthenticationLoginWithXboxAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationLoginWithXboxGetResultSize](functions/pfauthenticationloginwithxboxgetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationLoginWithXboxAsync call. |  
| [PFAuthenticationLoginWithXUserAsync](functions/pfauthenticationloginwithxuserasync.md) | Signs the user in using an XUserHandle, returning a session identifier that can subsequently be used for API calls which require an authenticated user |  
| [PFAuthenticationLoginWithXUserGetResult](functions/pfauthenticationloginwithxusergetresult.md) | Get the result from a PFAuthenticationLoginWithXUserAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationLoginWithXUserGetResultSize](functions/pfauthenticationloginwithxusergetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationLoginWithXUserAsync call. |  
| [PFAuthenticationReLoginWithCustomIDAsync](functions/pfauthenticationreloginwithcustomidasync.md) | Reauthenticates an existing PFEntityHandle. Used to address situations where the EntityToken expired and the PlayFab SDK is unable to refresh it. |  
| [PFAuthenticationReLoginWithNintendoServiceAccountAsync](functions/pfauthenticationreloginwithnintendoserviceaccountasync.md) | Reauthenticates an existing PFEntityHandle. Used to address situations where the EntityToken expired and the PlayFab SDK is unable to refresh it. |  
| [PFAuthenticationReLoginWithOpenIdConnectAsync](functions/pfauthenticationreloginwithopenidconnectasync.md) | Reauthenticates an existing PFEntityHandle. Used to address situations where the EntityToken expired and the PlayFab SDK is unable to refresh it. |  
| [PFAuthenticationReLoginWithPSNAsync](functions/pfauthenticationreloginwithpsnasync.md) | Reauthenticates an existing PFEntityHandle. Used to address situations where the EntityToken expired and the PlayFab SDK is unable to refresh it. |  
| [PFAuthenticationReLoginWithSteamAsync](functions/pfauthenticationreloginwithsteamasync.md) | Reauthenticates an existing PFEntityHandle. Used to address situations where the EntityToken expired and the PlayFab SDK is unable to refresh it. |  
| [PFAuthenticationReLoginWithXboxAsync](functions/pfauthenticationreloginwithxboxasync.md) | Reauthenticates an existing PFEntityHandle. Used to address situations where the EntityToken expired and the PlayFab SDK is unable to refresh it. |  
| [PFAuthenticationReLoginWithXUserAsync](functions/pfauthenticationreloginwithxuserasync.md) | Reauthenticates an existing PFEntityHandle using an XUserHandle. Used to address situations where the EntityToken expired and the PlayFab SDK is unable to refresh it. |  
| [PFAuthenticationServerLoginWithServerCustomIdAsync](functions/pfauthenticationserverloginwithservercustomidasync.md) | Securely login a game client from an external server backend using a custom identifier for that player. Server Custom ID and Client Custom ID are mutually exclusive and cannot be used to retrieve the same player account. |  
| [PFAuthenticationServerLoginWithServerCustomIdGetResult](functions/pfauthenticationserverloginwithservercustomidgetresult.md) | Get the result from a PFAuthenticationServerLoginWithServerCustomIdAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationServerLoginWithServerCustomIdGetResultSize](functions/pfauthenticationserverloginwithservercustomidgetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationServerLoginWithServerCustomIdAsync call. |  
| [PFAuthenticationServerLoginWithSteamIdAsync](functions/pfauthenticationserverloginwithsteamidasync.md) | Signs the user in using an Steam ID, returning a session identifier that can subsequently be used for API calls which require an authenticated user |  
| [PFAuthenticationServerLoginWithSteamIdGetResult](functions/pfauthenticationserverloginwithsteamidgetresult.md) | Get the result from a PFAuthenticationServerLoginWithSteamIdAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationServerLoginWithSteamIdGetResultSize](functions/pfauthenticationserverloginwithsteamidgetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationServerLoginWithSteamIdAsync call. |  
| [PFAuthenticationServerLoginWithXboxAsync](functions/pfauthenticationserverloginwithxboxasync.md) | Signs the user in using a Xbox Live Token from an external server backend, returning a session identifier that can subsequently be used for API calls which require an authenticated user |  
| [PFAuthenticationServerLoginWithXboxGetResult](functions/pfauthenticationserverloginwithxboxgetresult.md) | Get the result from a PFAuthenticationServerLoginWithXboxAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationServerLoginWithXboxGetResultSize](functions/pfauthenticationserverloginwithxboxgetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationServerLoginWithXboxAsync call. |  
| [PFAuthenticationServerLoginWithXboxIdAsync](functions/pfauthenticationserverloginwithxboxidasync.md) | Signs the user in using an Xbox ID and Sandbox ID, returning a session identifier that can subsequently be used for API calls which require an authenticated user |  
| [PFAuthenticationServerLoginWithXboxIdGetResult](functions/pfauthenticationserverloginwithxboxidgetresult.md) | Get the result from a PFAuthenticationServerLoginWithXboxIdAsync call. The PFEntityHandle will always be returned, but the additional info in the PFAuthenticationLoginResult is only returned if a buffer is provided. |  
| [PFAuthenticationServerLoginWithXboxIdGetResultSize](functions/pfauthenticationserverloginwithxboxidgetresultsize.md) | Get the size in bytes needed to store the result of a PFAuthenticationServerLoginWithXboxIdAsync call. |  
| [PFAuthenticationValidateEntityTokenAsync](functions/pfauthenticationvalidateentitytokenasync.md) | Method for a server to validate a client provided EntityToken. Only callable by the title entity. |  
| [PFAuthenticationValidateEntityTokenGetResult](functions/pfauthenticationvalidateentitytokengetresult.md) | Gets the result of a successful PFAuthenticationValidateEntityTokenAsync call. |  
| [PFAuthenticationValidateEntityTokenGetResultSize](functions/pfauthenticationvalidateentitytokengetresultsize.md) | Get the size in bytes needed to store the result of a ValidateEntityToken call. |  
