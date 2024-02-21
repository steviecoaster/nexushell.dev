---
external help file: NexuShell-help.xml
Module Name: NexuShell
online version:
schema: 2.0.0
---

# Get-NexusCleanupPolicy

## SYNOPSIS
Gets Nexus Cleanup Policy information

## SYNTAX

```
Get-NexusCleanupPolicy [[-Name] <String[]>] [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## DESCRIPTION
Gets Nexus Cleanup Policy information

## EXAMPLES

### EXAMPLE 1
```
Get-NexusCleanupPolicy
```

### EXAMPLE 2
```
Get-NexusCleanupPolicy -Name TestPol
```

### EXAMPLE 3
```
Get-NexusCleanupPolicy -Name TestPol,ProdPol
```

## PARAMETERS

### -Name
The specific policy to retrieve

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Policy, CleanupPolicy

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProgressAction
{{ Fill ProgressAction Description }}

```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: proga

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS
