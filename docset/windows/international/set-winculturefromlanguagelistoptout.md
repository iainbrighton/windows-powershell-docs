---
author: brianlic-msft
description: 
external help file: Microsoft.InternationalSettings.Commands.dll-Help.xml
keywords: powershell, cmdlet
manager: alanth
ms.date: 2016-12-20
ms.prod: powershell
ms.technology: powershell
ms.topic: reference
online version: 
schema: 2.0.0
title: Set-WinCultureFromLanguageListOptOut
ms.assetid: 3383B8A3-16DF-45A9-848F-B6A76FFAB900
---

# Set-WinCultureFromLanguageListOptOut

## SYNOPSIS
Sets the Culture from language list opt out setting for the current user account.

## SYNTAX

```
Set-WinCultureFromLanguageListOptOut [-OptOut] <Boolean> [<CommonParameters>]
```

## DESCRIPTION
The **Set-WinCultureFromLanguageListOptOut** cmdlet sets the Culture, or User Locale, opt-out setting for the current user account.
Setting this option to $True disables the action of dynamically setting the Culture for the current user based on changes to the Windows display language.
Setting this option to $False activates the dynamic setting behavior.
The default setting is $False.

## EXAMPLES

### Example 1: Block dynamic setting
```
PS C:\>Set-WinCultureFromLanguageListOptOut -OptOut $True
```

This command blocks the dynamic setting behavior.

## PARAMETERS

### -OptOut
Specifies the opt-out value.

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-WinCultureFromLanguageListOptOut](./Get-WinCultureFromLanguageListOptOut.md)
