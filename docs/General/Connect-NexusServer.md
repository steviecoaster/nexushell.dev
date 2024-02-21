---
external help file: NexuShell-help.xml
Module Name: NexuShell
online version:
schema: 2.0.0
---

# Connect-NexusServer

## SYNOPSIS
Creates the authentication header needed for REST calls to your Nexus server

## SYNTAX

```
Connect-NexusServer [-Hostname] <String> [-Credential] <PSCredential> [-Path <String>] [-UseSSL]
 [-Sslport <String>] [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## DESCRIPTION
Creates the authentication header needed for REST calls to your Nexus server

## EXAMPLES

### EXAMPLE 1
```
Connect-NexusServer -Hostname nexus.fabrikam.com -Credential (Get-Credential)
```

### EXAMPLE 2
```
Connect-NexusServer -Hostname nexus.fabrikam.com -Credential (Get-Credential) -UseSSL
```

### EXAMPLE 3
```
Connect-NexusServer -Hostname nexus.fabrikam.com -Credential $Cred -UseSSL -Sslport 443
```

## PARAMETERS

### -Hostname
The hostname or ip address of your Nexus server

```yaml
Type: String
Parameter Sets: (All)
Aliases: Server

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Credential
The credentials to authenticate to your Nexus server

```yaml
Type: PSCredential
Parameter Sets: (All)
Aliases:

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Path
The optional context path used by the Nexus server

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: /
Accept pipeline input: False
Accept wildcard characters: False
```

### -UseSSL
Use https instead of http for REST calls.
Defaults to 8443.

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

### -Sslport
If not the default 8443 provide the current SSL port your Nexus server uses

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: 8443
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
