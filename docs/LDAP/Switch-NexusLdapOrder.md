---
external help file: NexuShell-help.xml
Module Name: NexuShell
online version:
schema: 2.0.0
---

# Switch-NexusLdapOrder

## SYNOPSIS
Reorders LDAP Server priority if there are multiple

## SYNTAX

```
Switch-NexusLdapOrder [-NewOrder] <Array> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## DESCRIPTION
Reorders LDAP Server priority if there are multiple

## EXAMPLES

### EXAMPLE 1
```
Switch-NexusLdapOrder -NewOrder ProductionLDAP,EuropeLDAP,AsiaLDAP
```

## PARAMETERS

### -NewOrder
The new order of LDAP Server Names.
You can't retrieve these via API, so you'll need to look in the web interface or know what they are

```yaml
Type: Array
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
