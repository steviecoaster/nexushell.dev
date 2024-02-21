---
external help file: NexuShell-help.xml
Module Name: NexuShell
online version:
schema: 2.0.0
---

# Test-NexusEmailConfig

## SYNOPSIS
Verifies Nexus Smtp configuration

## SYNTAX

```
Test-NexusEmailConfig [-Recipient] <String> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## DESCRIPTION
Verifies Nexus Smtp configuration

## EXAMPLES

### EXAMPLE 1
```
Test-NexusEmailConfig -Recipient tim@foo.org
```

## PARAMETERS

### -Recipient
Email address to send test message too

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
