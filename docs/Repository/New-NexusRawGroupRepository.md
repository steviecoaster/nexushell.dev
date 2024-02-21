---
external help file: NexuShell-help.xml
Module Name: NexuShell
online version:
schema: 2.0.0
---

# New-NexusRawGroupRepository

## SYNOPSIS
Creates a Raw Group repository

## SYNTAX

```
New-NexusRawGroupRepository [-Name] <String> [-GroupMembers] <String[]> [-Online] [[-BlobStore] <String>]
 [-UseStrictContentTypeValidation] [-ContentDisposition] <String> [-DeploymentPolicy] <String>
 [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## DESCRIPTION
Creates a Raw Group repository

## EXAMPLES

### EXAMPLE 1
```
New-NexusRawGroupRepository -Name AllArtifacts -GroupMembers BinaryArtifacts,Documentation -DeploymentPolicy Allow
```

## PARAMETERS

### -Name
The name of the repository

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

### -GroupMembers
The Raw Repositories to add as group members

```yaml
Type: String[]
Parameter Sets: (All)
Aliases:

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Online
Marks the repository as online

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: True
Accept pipeline input: False
Accept wildcard characters: False
```

### -BlobStore
The blob store to attach to the repository

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: Default
Accept pipeline input: False
Accept wildcard characters: False
```

### -UseStrictContentTypeValidation
Validate that all content uploaded to this repository is of a MIME type appropriate for the repository format

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -ContentDisposition
Add Content-Disposition header as 'Attachment' to disable some content from being inline in a browser

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeploymentPolicy
Required by the API, but thrown away by the underlying system.
Use whatever you want here from the set

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 5
Default value: Allow_Once
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
