---
external help file: NexuShell-help.xml
Module Name: NexuShell
online version:
schema: 2.0.0
---

# Set-NexusUserPassword

## SYNOPSIS
Change a user's password.

## SYNTAX

```
Set-NexusUserPassword [-Username] <String> [-NewPassword] <SecureString> [-ProgressAction <ActionPreference>]
 [<CommonParameters>]
```

## DESCRIPTION
Change a user's password.

## EXAMPLES

### EXAMPLE 1
```
Set-NexusUserPassword -Username jimmy -NewPassword ("Sausage2021" | ConvertTo-SecureString -AsPlainText -Force)
```

## PARAMETERS

### -Username
The userid the request should apply to

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

### -NewPassword
The new password to use.

```yaml
Type: SecureString
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
