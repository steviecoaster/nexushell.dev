---
external help file: NexuShell-help.xml
Module Name: NexuShell
online version:
schema: 2.0.0
---

# New-NexusRawComponent

## SYNOPSIS
Uploads a file to a Raw repository

## SYNTAX

```
New-NexusRawComponent [-RepositoryName] <String> [-File] <String> [[-Directory] <String>] [[-Name] <String>]
 [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## DESCRIPTION
Uploads a file to a Raw repository

## EXAMPLES

### EXAMPLE 1
```
New-NexusRawComponent -RepositoryName GeneralFiles -File C:\temp\service.1234.log
```

### EXAMPLE 2
```
New-NexusRawComponent -RepositoryName GeneralFiles -File C:\temp\service.log -Directory logs
```

### EXAMPLE 3
```
New-NexusRawComponent -RepositoryName GeneralFile -File C:\temp\service.log -Directory logs -Name service.99999.log
```

## PARAMETERS

### -RepositoryName
The Raw repository to upload too

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

### -File
The file to upload

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Directory
The directory to store the file on the repo

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
The name of the file stored into the repo.
Can be different than the file name being uploaded.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 4
Default value: (Split-Path -Leaf $File)
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
