---
title: SetName method of the Win32_TSGatewayConnectionAuthorizationPolicy class
description: Sets a new name for this Remote Desktop connection authorization policy (RD \ 160;CAP).
ms.assetid: 4a3b71d4-9b1c-46ea-b14a-fcbe32af37b5
ms.tgt_platform: multiple
keywords:
- SetName method Remote Desktop Services
- SetName method Remote Desktop Services , Win32_TSGatewayConnectionAuthorizationPolicy class
- Win32_TSGatewayConnectionAuthorizationPolicy class Remote Desktop Services , SetName method
topic_type:
- apiref
api_name:
- Win32_TSGatewayConnectionAuthorizationPolicy.SetName
api_location:
- AagWmi.dll
api_type:
- COM
ms.topic: reference
ms.date: 05/31/2018
---

# SetName method of the Win32\_TSGatewayConnectionAuthorizationPolicy class

Sets a new name for this Remote Desktop connection authorization policy (RD CAP).

## Syntax


```mof
uint32 SetName(
  [in] string Name
);
```



## Parameters

<dl> <dt>

*Name* \[in\]
</dt> <dd>

Name of the RD CAP. The name must be 64 characters or less, unique (case is ignored), and cannot contain the following reserved characters:

<> : ; " / \\ \| ? \* \[TAB\]

</dd> </dl>

## Return value

If the method succeeds, it returns zero. If the method is unsuccessful, it returns a nonzero value. For a list of error codes, see [Remote Desktop Services WMI Provider Error Codes](terminal-services-wmi-provider-error-codes.md).

## Remarks

You must be a member of the Administrators group to call this method.

Managed Object Format (MOF) files contain the definitions for Windows Management Instrumentation (WMI) classes. MOF files are not installed as part of the Microsoft Windows Software Development Kit (SDK). They are installed on the server when you add the associated role by using the Server Manager. For more information about MOF files, see [Managed Object Format (MOF)](/windows/desktop/WmiSdk/managed-object-format--mof-).

## Requirements



| Requirement | Value |
|-------------------------------------|------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | None supported<br/>                                                                |
| Minimum supported server<br/> | Windows Server 2008<br/>                                                           |
| Namespace<br/>                | Root\\CIMv2\\TerminalServices<br/>                                                 |
| MOF<br/>                      | <dl> <dt>TSGateway.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>AagWmi.dll</dt> </dl>    |



## See also

<dl> <dt>

[**Win32\_TSGatewayConnectionAuthorizationPolicy**](win32-tsgatewayconnectionauthorizationpolicy.md)
</dt> </dl>

 

