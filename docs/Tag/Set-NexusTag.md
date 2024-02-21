---
external help file: NexuShell-help.xml
Module Name: NexuShell
online version: https://help.sonatype.com/en/tagging.html
schema: 2.0.0
---

# Set-NexusTag

## SYNOPSIS
Sets tag metadata for an existing tag

## SYNTAX

```
Set-NexusTag [-Tag] <String> [-Attributes] <Hashtable> [-ProgressAction <ActionPreference>]
 [<CommonParameters>]
```

## DESCRIPTION
This command provides a mechanism to update tag metadata for existing tags within a Sonatype Nexus installation

## EXAMPLES

### EXAMPLE 1
```
Set-NexusTag -Name 'Example' -Attributes @{ foo = 'bar' ; bazz = 'bizz'}
```

## PARAMETERS

### -Tag
The tag to update

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

### -Attributes
A hashtable of attributes to apply to the tag

```yaml
Type: Hashtable
Parameter Sets: (All)
Aliases:

Required: True
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

