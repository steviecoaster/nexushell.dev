---
external help file: NexuShell-help.xml
Module Name: NexuShell
online version:
schema: 2.0.0
---

# Get-NexusRepository

## SYNOPSIS
Returns info about configured Nexus repository

## SYNTAX

### default (Default)
```
Get-NexusRepository [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

### Format
```
Get-NexusRepository -Format <String> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

### Type
```
Get-NexusRepository -Type <String> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

### Name
```
Get-NexusRepository -Name <String> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## DESCRIPTION
Returns details for currently configured repositories on your Nexus server

## EXAMPLES

### EXAMPLE 1
```
Get-NexusRepository
```

### EXAMPLE 2
```
Get-NexusRepository -Format nuget
```

### EXAMPLE 3
```
Get-NexusRepository -Name CompanyNugetPkgs
```

## PARAMETERS

### -Format
Query for only a specific repository format.
E.g.
nuget, maven2, or docker

```yaml
Type: String
Parameter Sets: Format
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Type
{{ Fill Type Description }}

```yaml
Type: String
Parameter Sets: Type
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
Query for a specific repository by name

```yaml
Type: String
Parameter Sets: Name
Aliases:

Required: True
Position: Named
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
