---
external help file: NexuShell-help.xml
Module Name: NexuShell
online version: https://help.sonatype.com/en/tagging.html
schema: 2.0.0
---

# Add-NexusTagAssociation

## SYNOPSIS
Tags a component with the provided tag name based on the search query parameters

## SYNTAX

```
Add-NexusTagAssociation [-Tag] <String> [[-SearchQuery] <Hashtable>] [-ProgressAction <ActionPreference>]
 [<CommonParameters>]
```

## DESCRIPTION
Tags a component based on the Query terms based via hashtable to the API endpoint.

## EXAMPLES

### EXAMPLE 1
```
Add-NexusTag -Tag SampleTag -SearchQuery @{ format = 'nuget' ; repository = 'ChocolateyPackages'}
```

## PARAMETERS

### -Tag
The tag to apply to the component(s)

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SearchQuery
A hashtable of search parameters by which to tag components

```yaml
Type: Hashtable
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
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

[https://help.sonatype.com/en/tagging.html](https://help.sonatype.com/en/tagging.html)

