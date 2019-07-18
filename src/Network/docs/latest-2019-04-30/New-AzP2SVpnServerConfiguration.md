---
external help file:
Module Name: Az.Network
online version: https://docs.microsoft.com/en-us/powershell/module/az.network/new-azp2svpnserverconfiguration
schema: 2.0.0
---

# New-AzP2SVpnServerConfiguration

## SYNOPSIS
Creates a P2SVpnServerConfiguration to associate with a VirtualWan if it doesn't exist else updates the existing P2SVpnServerConfiguration.

## SYNTAX

### Create (Default)
```
New-AzP2SVpnServerConfiguration -ResourceGroupName <String> -SubscriptionId <String> -VirtualWanName <String>
 [-Name <String>] [-P2SVpnServerConfigurationParameter <IP2SVpnServerConfiguration>]
 [-DefaultProfile <PSObject>] [-AsJob] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-AzP2SVpnServerConfiguration -InputObject <INetworkIdentity> [-Name <String>] [-Id <String>]
 [-P2SVpnServerConfigRadiusClientRootCertificate <IP2SVpnServerConfigRadiusClientRootCertificate[]>]
 [-P2SVpnServerConfigRadiusServerRootCertificate <IP2SVpnServerConfigRadiusServerRootCertificate[]>]
 [-P2SVpnServerConfigVpnClientRevokedCertificate <IP2SVpnServerConfigVpnClientRevokedCertificate[]>]
 [-P2SVpnServerConfigVpnClientRootCertificate <IP2SVpnServerConfigVpnClientRootCertificate[]>]
 [-PropertiesEtag <String>] [-PropertiesName <String>] [-RadiusServerAddress <String>]
 [-RadiusServerSecret <String>] [-VpnClientIPsecPolicy <IIpsecPolicy[]>]
 [-VpnProtocol <VpnGatewayTunnelingProtocol[]>] [-DefaultProfile <PSObject>] [-AsJob] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### CreateExpanded
```
New-AzP2SVpnServerConfiguration -ResourceGroupName <String> -SubscriptionId <String> -VirtualWanName <String>
 -P2SVpnServerConfigurationName <String> [-Name <String>] [-Id <String>]
 [-P2SVpnServerConfigRadiusClientRootCertificate <IP2SVpnServerConfigRadiusClientRootCertificate[]>]
 [-P2SVpnServerConfigRadiusServerRootCertificate <IP2SVpnServerConfigRadiusServerRootCertificate[]>]
 [-P2SVpnServerConfigVpnClientRevokedCertificate <IP2SVpnServerConfigVpnClientRevokedCertificate[]>]
 [-P2SVpnServerConfigVpnClientRootCertificate <IP2SVpnServerConfigVpnClientRootCertificate[]>]
 [-PropertiesEtag <String>] [-PropertiesName <String>] [-RadiusServerAddress <String>]
 [-RadiusServerSecret <String>] [-VpnClientIPsecPolicy <IIpsecPolicy[]>]
 [-VpnProtocol <VpnGatewayTunnelingProtocol[]>] [-DefaultProfile <PSObject>] [-AsJob] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### CreateViaIdentity
```
New-AzP2SVpnServerConfiguration -InputObject <INetworkIdentity>
 [-P2SVpnServerConfigurationParameter <IP2SVpnServerConfiguration>] [-DefaultProfile <PSObject>] [-AsJob]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Creates a P2SVpnServerConfiguration to associate with a VirtualWan if it doesn't exist else updates the existing P2SVpnServerConfiguration.

## EXAMPLES

### Example 1: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

### Example 2: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

## PARAMETERS

### -AsJob
Run the command as a job

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: System.Management.Automation.PSObject
Parameter Sets: (All)
Aliases: AzureRMContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Id
Resource ID.

```yaml
Type: System.String
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -InputObject
Identity Parameter

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.INetworkIdentity
Parameter Sets: CreateViaIdentityExpanded, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
Dynamic: False
```

### -Name
The name of the P2SVpnServerConfiguration.

```yaml
Type: System.String
Parameter Sets: Create, CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -P2SVpnServerConfigRadiusClientRootCertificate
Radius client root certificate of P2SVpnServerConfiguration.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IP2SVpnServerConfigRadiusClientRootCertificate[]
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -P2SVpnServerConfigRadiusServerRootCertificate
Radius Server root certificate of P2SVpnServerConfiguration.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IP2SVpnServerConfigRadiusServerRootCertificate[]
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -P2SVpnServerConfigurationName
The name of the P2SVpnServerConfiguration.

```yaml
Type: System.String
Parameter Sets: CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -P2SVpnServerConfigurationParameter
P2SVpnServerConfiguration Resource.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IP2SVpnServerConfiguration
Parameter Sets: Create, CreateViaIdentity
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
Dynamic: False
```

### -P2SVpnServerConfigVpnClientRevokedCertificate
VPN client revoked certificate of P2SVpnServerConfiguration.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IP2SVpnServerConfigVpnClientRevokedCertificate[]
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -P2SVpnServerConfigVpnClientRootCertificate
VPN client root certificate of P2SVpnServerConfiguration.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IP2SVpnServerConfigVpnClientRootCertificate[]
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -PropertiesEtag
A unique read-only string that changes whenever the resource is updated.

```yaml
Type: System.String
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -PropertiesName
The name of the P2SVpnServerConfiguration that is unique within a VirtualWan in a resource group.
This name can be used to access the resource along with Paren VirtualWan resource name.

```yaml
Type: System.String
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -RadiusServerAddress
The radius server address property of the P2SVpnServerConfiguration resource for point to site client connection.

```yaml
Type: System.String
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -RadiusServerSecret
The radius secret property of the P2SVpnServerConfiguration resource for point to site client connection.

```yaml
Type: System.String
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -ResourceGroupName
The resource group name of the VirtualWan.

```yaml
Type: System.String
Parameter Sets: Create, CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -SubscriptionId
The subscription credentials which uniquely identify the Microsoft Azure subscription.
The subscription ID forms part of the URI for every service call.

```yaml
Type: System.String
Parameter Sets: Create, CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -VirtualWanName
The name of the VirtualWan.

```yaml
Type: System.String
Parameter Sets: Create, CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -VpnClientIPsecPolicy
VpnClientIpsecPolicies for P2SVpnServerConfiguration.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IIpsecPolicy[]
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -VpnProtocol
VPN protocols for the P2SVpnServerConfiguration.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Support.VpnGatewayTunnelingProtocol[]
Parameter Sets: CreateViaIdentityExpanded, CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Azure.PowerShell.Cmdlets.Network.Models.INetworkIdentity

### Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IP2SVpnServerConfiguration

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IP2SVpnServerConfiguration

## ALIASES

## RELATED LINKS
