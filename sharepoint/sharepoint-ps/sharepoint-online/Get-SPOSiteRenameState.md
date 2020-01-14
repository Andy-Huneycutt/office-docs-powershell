---
external help file: sharepointonline.xml
applicable: SharePoint Online
title: Get-SPOSiteRenameState
schema: 2.0.0
author: 
ms.author: 
ms.reviewer:
---

# Get-SPOSiteRenameState

## SYNOPSIS

.

## SYNTAX

### SourceSiteUrl
```powershell
Get-SPOSiteRenameState -Identity <SpoSitePipeBind> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### RenameReport
```powershell
Get-SPOSiteRenameState [-State <RenameState>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION

Use this cmdlet to .

## EXAMPLES

### Example 1

```powershell
Get-SPOSiteRenameState -Identity
```

This example .

## PARAMETERS

### -Identity

The urls of the site to be renamed.

```yaml
Type: SpoSitePipeBind
Parameter Sets: SourceSiteUrl
Aliases: 
Applicable: SharePoint Online
Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -State

The urls of the site to be renamed.

```yaml
Type: RenameState
Parameter Sets: RenameReport, ParentId
Aliases: 
Applicable: SharePoint Online
Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm

Prompts you for confirmation before executing the command.
For more information, type the following command: `get-help about_commonparameters`

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf
Applicable: SharePoint Online
Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf

Displays a message that describes the effect of the command instead of executing the command.
For more information, type the following command: `get-help about_commonparameters`

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi
Applicable: SharePoint Online
Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/p/?LinkID=113216).

## NOTES
