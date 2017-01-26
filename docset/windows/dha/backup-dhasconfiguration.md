---
author: brianlic-msft
description: 
external help file: Microsoft.Windows.DeviceHealthAttestation.PowerShell.dll-Help.xml
keywords: powershell, cmdlet
manager: alanth
ms.date: 2016-12-20
ms.prod: powershell
ms.technology: powershell
ms.topic: reference
online version: 
schema: 2.0.0
title: Backup-DHASConfiguration
ms.assetid: EE22DE86-88C2-4B94-8A49-27CDC9A91555
---

# Backup-DHASConfiguration

## SYNOPSIS
Backs up the configuration.

## SYNTAX

```
Backup-DHASConfiguration [-Path] <String> [-Force] [<CommonParameters>]
```

## DESCRIPTION
The **Backup-DHASConfiguration** cmdlet backs up the Device Health Attestation service configuration from the web.config file.

You must have administrator rights to run this cmdlet.

## EXAMPLES

### Example 1: Back up the service configuration
```
PS C:\>Backup-DHASConfiguration -Path "c:\backup.xml"
```

This commands backs up the service configuration from the web.config file to the file specified by the *Path* parameter.

## PARAMETERS

### -Force
Forces the command to run without asking for user confirmation.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Path
Specifies the location in which to save the backup configuration file.

```yaml
Type: String
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

### String
This cmdlet returns a string with the backup file path.

## NOTES

## RELATED LINKS

[Restore-DHASConfiguration](./Restore-DHASConfiguration.md)
