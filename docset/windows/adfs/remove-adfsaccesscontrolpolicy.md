---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: brianlic
author: brianlic-msft
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
external help file: Microsoft.IdentityServer.Management.dll-Help.xml
keywords: powershell, cmdlet
manager: alanth
ms.date: 2016-12-20
ms.prod: w10
ms.technology: powershell-windows
ms.topic: reference
online version: 
schema: 2.0.0
title: Remove-AdfsAccessControlPolicy
ms.assetid: 1F39B0B7-4329-4F6C-9ABB-9CAEEBC03965
---

# Remove-AdfsAccessControlPolicy

## SYNOPSIS
Removes an AD FS access control policy.

## SYNTAX

### IdentifierName
```
Remove-AdfsAccessControlPolicy [-TargetName] <String> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Identifier
```
Remove-AdfsAccessControlPolicy [-TargetIdentifier] <String> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### IdentifierObject
```
Remove-AdfsAccessControlPolicy [-TargetAccessControlPolicy] <AdfsAccessControlPolicy> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AdfsAccessControlPolicy** cmdlet removes an Active Directory Federation Services (AD FS) access control policy.

## EXAMPLES


## PARAMETERS

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -TargetAccessControlPolicy
Specifies the access control policy to remove.

```yaml
Type: AdfsAccessControlPolicy
Parameter Sets: IdentifierObject
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -TargetIdentifier
Specifies a target ID.

```yaml
Type: String
Parameter Sets: Identifier
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -TargetName
Specifies the name of the target.

```yaml
Type: String
Parameter Sets: IdentifierName
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AdfsAccessControlPolicy](./Get-AdfsAccessControlPolicy.md)

[New-AdfsAccessControlPolicy](./New-AdfsAccessControlPolicy.md)

[Set-AdfsAccessControlPolicy](./Set-AdfsAccessControlPolicy.md)
