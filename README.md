# Jio Fiber Home Router Paths


- After login, you can use the `JS code` to get to that page. (Just open the console inside `Dev Tools` and paste the JS code & press `Enter` key to execute the code)
- Accessing that page directly with URL will get you 401 error because of the missing cookie in HTTP header.
- I have extracted these path from the router admin interface `Firmware Version: SRCMTF1_JCOW414_R2.41`.
- Some of these pages are not available in the menu but are required for advanced users to customise the router settings.




| Main Menu | Page Name / Second Level Menu | Disabled | Page URL | Breadcrumb | JS code |
| ------ | ------ | ------ | ------ | ------ | ------ |
| Status | System Information | false | http://192.168.29.1/platform.cgi?page=deviceStatus.html | `Status > Device Status > System Information` | `gotoLinks('deviceStatus.html')` |
| Status | LAN Information | false | http://192.168.29.1/platform.cgi?page=lanStatus.html | `Status > Device Status > LAN Information` | `gotoLinks('lanStatus.html')` |
| Status | WAN Information | false | http://192.168.29.1/platform.cgi?page=wanStatus.html | `Status > Device Status > WAN Information` | `gotoLinks('wanStatus.html')` |
| Status | Wireless Information | false | http://192.168.29.1/platform.cgi?page=wirelessStatus.html | `Status > Device Status > Wireless Information` | `gotoLinks('wirelessStatus.html')` |
| Status | Device Statistics | false | http://192.168.29.1/platform.cgi?page=deviceStatistics.html | `Status > Device Statistics` | `gotoLinks('deviceStatistics.html')` |
| Status | LAN Clients | false | http://192.168.29.1/platform.cgi?page=lanDhcpLeasedClients.html | `Status > LAN Clients` | `gotoLinks('lanDhcpLeasedClients.html')` |
| Status | WLAN Statistics | false | http://192.168.29.1/platform.cgi?page=wirelessStatistics.html | `Status > WLAN Statistics` | `gotoLinks('wirelessStatistics.html')` |
| Status | WLAN Clients | false | http://192.168.29.1/platform.cgi?page=wirelessClients.html | `Status > WLAN Clients` | `gotoLinks('wirelessClients.html')` |
| Network | LAN IPv4 Configuration | false | http://192.168.29.1/platform.cgi?page=lanIPv4Config.html | `Network > LAN > LAN IPv4 Configuration` | `gotoLinks('lanIPv4Config.html')` |
| Network | LAN IPv4 Reserved IPs | false | http://192.168.29.1/platform.cgi?page=lanIPv4ReservedIPs.html | `Network > LAN  > LAN IPv4 Reserved IPs` | `gotoLinks('lanIPv4ReservedIPs.html')` |
| Network | LAN IPv6 Configuration | false | http://192.168.29.1/platform.cgi?page=lanIPv6Config.html | `Network > LAN > LAN IPv6 Configuration` | `gotoLinks('lanIPv6Config.html')` |
| Network | LAN IPv6 Address Pools | false | http://192.168.29.1/platform.cgi?page=lanIPv6AddressPools.html | `Network > LAN > LAN IPv6 Address Pools` | `gotoLinks('lanIPv6AddressPools.html')` |
| Network | LAN IPv6 Prefix Length | false | http://192.168.29.1/platform.cgi?page=lanIPv6PrefixLength.html | `Network > LAN > LAN IPv6 Prefix Length` | `gotoLinks('lanIPv6PrefixLength.html')` |
| Network | WAN IPv4 Configuration | false | http://192.168.29.1/platform.cgi?page=wanIPv4Config.html | `Network > WAN > WAN IPv4 Configuration` | `gotoLinks('wanIPv4Config.html')` |
| Network | WAN IPv6 Configuration | false | http://192.168.29.1/platform.cgi?page=wanIpv6Config.html | `Network > WAN > WAN IPv6 Configuration` | `gotoLinks('wanIpv6Config.html')` |
| Network | IP Mode | false | http://192.168.29.1/platform.cgi?page=ipMode.html | `Network > IPv6 > IP Mode` | `gotoLinks('ipMode.html')` |
| Network | RADVD | false | http://192.168.29.1/platform.cgi?page=rdvd.html | `Network > IPv6 > RADVD` | `gotoLinks('rdvd.html')` |
| Network | Prefixes | false | http://192.168.29.1/platform.cgi?page=prefixList.html | `Network > IPv6 > Prefixes` | `gotoLinks('prefixList.html')` |
| Network | 6 to 4 Tunnels | false | http://192.168.29.1/platform.cgi?page=6to4TunnelIpv6.html | `Network > IPv6 > 6 to 4 Tunnels` | `gotoLinks('6to4TunnelIpv6.html')` |
| Network | ISATAP | false | http://192.168.29.1/platform.cgi?page=isatapTunnels.html | `Network > IPv6 > ISATAP` | `gotoLinks('isatapTunnels.html')` |
| Network | Tunnel Status | false | http://192.168.29.1/platform.cgi?page=tunnelStatusIpv6.html | `Network > IPv6 > Tunnel Status` | `gotoLinks('tunnelStatusIpv6.html')` |
| Network | Routing Mode | false | http://192.168.29.1/platform.cgi?page=routingMode.html | `Network > Routing > Routing Mode` | `gotoLinks('routingMode.html')` |
| Advanced | UPnP Configuration | false | http://192.168.29.1/platform.cgi?page=upnpConfig.html | `Advanced > Network > UPnP Configuration` | `gotoLinks('upnpConfig.html')` |
| Network | Access Points | false | http://192.168.29.1/platform.cgi?page=accessPoints.html | `Network > Wireless > Access Points` | `gotoLinks('accessPoints.html')` |
| Network | Profiles | false | http://192.168.29.1/platform.cgi?page=profiles.html | `Network > Wireless > Profiles` | `gotoLinks('profiles.html')` |
| Network | Basic Configuration 2.4GHz | false | http://192.168.29.1/platform.cgi?page=radioBasicConfig.html | `Network > Wireless > Basic Configuration 2.4GHz` | `gotoLinks('radioBasicConfig.html')` |
| Network | Advanced Configuration 2.4GHz | false | http://192.168.29.1/platform.cgi?page=radioadvancedConfig.html | `Network > Wireless > Advanced Configuration 2.4GHz` | `gotoLinks('radioadvancedConfig.html')` |
| Network | WPS | false | http://192.168.29.1/platform.cgi?page=wps.html | `Network > Wireless > WPS` | `gotoLinks('wps.html')` |
| Network | WMM | false | http://192.168.29.1/platform.cgi?page=wmm.html | `Network > Wireless > WMM` | `gotoLinks('wmm.html')` |
| Security | Default Policy | false | http://192.168.29.1/platform.cgi?page=defaultPolicy.html | `Security > Firewall > Default Policy` | `gotoLinks('defaultPolicy.html')` |
| Security | IPv4 Firewall Rules | false | http://192.168.29.1/platform.cgi?page=firewallRules.html | `Security > Firewall > IPv4 Firewall Rules` | `gotoLinks('firewallRules.html')` |
| Security | Custom Services | false | http://192.168.29.1/platform.cgi?page=customServices.html | `Security > Firewall > Custom Services` | `gotoLinks('customServices.html')` |
| Security | Port Forwarding | false | http://192.168.29.1/platform.cgi?page=portForwarding.html | `Security > Firewall > Port Forwarding` | `gotoLinks('portForwarding.html')` |
| Security | ALG | true | http://192.168.29.1/platform.cgi?page=alg.html | `Security > ALG` | `gotoLinks('alg.html')` |
| Security | Content Filtering | false | http://192.168.29.1/platform.cgi?page=contentFiltering.html | `Security > Content Filtering > Content Filtering` | `gotoLinks('contentFiltering.html')` |
| Security | Blocked Keywords | false | http://192.168.29.1/platform.cgi?page=blockedKeywords.html | `Security > Content Filtering > Blocked Keywords` | `gotoLinks('blockedKeywords.html')` |
| Security | Approved URLs | false | http://192.168.29.1/platform.cgi?page=approvedUrls.html | `Security > Content Filtering > Approved URLs` | `gotoLinks('approvedUrls.html')` |
| Security | Export Web Filter | false | http://192.168.29.1/platform.cgi?page=exportWebFilter.html | `Security > Content Filtering > Export Web Filter` | `gotoLinks('exportWebFilter.html')` |
| Administration | Users | false | http://192.168.29.1/platform.cgi?page=users.html | `Administration > Users` | `gotoLinks('users.html')` |
| Administration | Remote Management | true | http://192.168.29.1/platform.cgi?page=remoteManagement.html | `Administration > Remote Management` | `gotoLinks('remoteManagement.html')` |
| Advanced | TR-069 | true | http://192.168.29.1/platform.cgi?page=tr-069ClientConfig.html | `Advanced > TR-069` | `gotoLinks('tr-069ClientConfig.html')` |
| Advanced | Radius Server Configuration | false | http://192.168.29.1/platform.cgi?page=radiusConfig.html | `Advanced > Administration > Radius Server Configuration` | `gotoLinks('radiusConfig.html')` |
| Administration | Backup / Restore | false | http://192.168.29.1/platform.cgi?page=backupRestore.html | `Administration > Maintenance > Backup / Restore` | `gotoLinks('backupRestore.html')` |
| Administration | Firmware Upgrade | false | http://192.168.29.1/platform.cgi?page=upgradeViaNetwork.html | `Administration > Maintenance > Firmware Upgrade` | `gotoLinks('upgradeViaNetwork.html')` |
| Administration | Diagnostics | false | http://192.168.29.1/platform.cgi?page=diagnostics.html | `Administration > Diagnostics` | `gotoLinks('diagnostics.html')` |
| Administration | Date & Time Configuration | false | http://192.168.29.1/platform.cgi?page=dateAndTime.html | `Administration > Date & Time Configuration` | `gotoLinks('dateAndTime.html')` |
| Network | Dynamic Routing | true | http://192.168.29.1/platform.cgi?page=dynamicRouting.html | `Network > Routing > Dynamic Routing` | `gotoLinks('dynamicRouting.html')` |
| Network | IPv4 Static Routing | false | http://192.168.29.1/platform.cgi?page=staticRouting.html | `Network > Routing > IPv4 Static Routing` | `gotoLinks('staticRouting.html')` |
| Network | IPv6 Static Routing | false | http://192.168.29.1/platform.cgi?page=ipv6Routing.html | `Network > Routing > IPv6 Static Routing` | `gotoLinks('ipv6Routing.html')` |
| Network | Access Point MAC Filter | false | http://192.168.29.1/platform.cgi?page=accessPointsMacFilter.html | `Network > Wireless > Access Points > MAC Filter` | `gotoLinks('accessPointsMacFilter.html')` |
| Network | Access Point Connected Clients | false | http://192.168.29.1/platform.cgi?page=accessPointsStatus.html | `Network > Wireless > Access Points > Connected Clients` | `gotoLinks('accessPointsStatus.html')` |
| Network | IMS Domains | false | http://192.168.29.1/platform.cgi?page=imsDomains.html | `Network > LAN > IMS Domains` | `gotoLinks('imsDomains.html')` |
| Status | View Logs | true | http://192.168.29.1/platform.cgi?page=viewLogs.html | `Status > View Logs` | `gotoLinks('viewLogs.html')` |
| Network | MLD Tunnels | false | http://192.168.29.1/platform.cgi?page=mldSetup.html | `Network > IPv6 > MLD Tunnels` | `gotoLinks('mldSetup.html')` |
| Advanced | IGMP Proxy Setup | false | http://192.168.29.1/platform.cgi?page=igmpProxySetup.html | `Advanced > Network > IGMP Proxy Setup` | `gotoLinks('igmpProxySetup.html')` |
| Advanced | Remote Syslog Configuration | true | http://192.168.29.1/platform.cgi?page=remoteSysLogSetup.html | `Advanced > Administration > Remote SysLog Configuration` | `gotoLinks('remoteSysLogSetup.html')` |
| Security | VPN Passthrough | false | http://192.168.29.1/platform.cgi?page=vpnPassthrough.html | `Security > VPN Passthrough` | `gotoLinks('vpnPassthrough.html')` |
| Security | Specific Attacks | false | http://192.168.29.1/platform.cgi?page=specificAttacks.html | `Security > Attack Checks > Specific Attacks` | `gotoLinks('specificAttacks.html')` |
| Security | Dos / DDoS Preventions | false | http://192.168.29.1/platform.cgi?page=dosDDoSPrevention.html | `Security > Attack Checks > Dos / DDoS Preventions` | `gotoLinks('dosDDoSPrevention.html')` |
| Advanced | Schedules | false | http://192.168.29.1/platform.cgi?page=schedules.html | `Advanced > Schedules` | `gotoLinks('schedules.html')` |
| Advanced | MAP-T Configuration | false | http://192.168.29.1/platform.cgi?page=maptConfiguration.html | `Advanced > Network > MAP-T Configuration` | `gotoLinks('maptConfiguration.html')` |
| QoS | DSCP to Priority Mapping | false | http://192.168.29.1/platform.cgi?page=dscpMapping.html | `QoS > DSCP to Priority Mapping` | `gotoLinks('dscpMapping.html')` |
| Advanced | Storage Devices | false | http://192.168.29.1/platform.cgi?page=disks.html | `Advanced > Administration > Storage Devices` | `gotoLinks('disks.html')` |
| Advanced | User Access Portal Sessions | true | http://192.168.29.1/platform.cgi?page=userAccessPortalSession.html | `Advanced > Administration > User Access Portal Sessions` | `gotoLinks('userAccessPortalSession.html')` |
| Advanced | User Access Portal Setup | true | http://192.168.29.1/platform.cgi?page=userAccessPortalSetup.html | `Advanced > Administration > User Access Portal Setup` | `gotoLinks('userAccessPortalSetup.html')` |
| Advanced | Bandwidth Profiles | false | http://192.168.29.1/platform.cgi?page=bandwidthProfiles.html | `Advanced > Bandwidth Profiles` | `gotoLinks('bandwidthProfiles.html')` |
| Advanced | Traffic Selectors | false | http://192.168.29.1/platform.cgi?page=trafficSelectors.html | `Advanced > Traffic Selectors` | `gotoLinks('trafficSelectors.html')` |
| Network | Available VLANs | false | http://192.168.29.1/platform.cgi?page=vlanSettings.html | `Network > LAN > Available VLANs` | `gotoLinks('vlanSettings.html')` |
| Network | VLAN Membership | false | http://192.168.29.1/platform.cgi?page=portVlan.html | `Network > LAN > VLAN Membership` | `gotoLinks('portVlan.html')` |
| Advanced | VLAN Configuration | false | http://192.168.29.1/platform.cgi?page=vlanWan.html | `Advanced > Network > VLAN Configuration` | `gotoLinks('vlanWan.html')` |
| QoS | 802.1P to Priority Mapping | false | http://192.168.29.1/platform.cgi?page=cosMapping.html | `QoS > 802.1P to Priority Mapping` | `gotoLinks('cosMapping.html')` |
| Advanced | Bridge Mode | false | http://192.168.29.1/platform.cgi?page=bridgeMode.html | `Advanced > Network > Bridge Mode` | `gotoLinks('bridgeMode.html')` |
| Network | LAN IPv4 DHCP Vendor Class | false | http://192.168.29.1/platform.cgi?page=lanIPv4DhcpVendorClass.html | `Network > LAN > LAN IPv4 DHCP Vendor Class` | `gotoLinks('lanIPv4DhcpVendorClass.html')` |
| Advanced | Accounting Status | false | http://192.168.29.1/platform.cgi?page=accountingStatus.html | `Advanced > Status > Accounting Status` | `gotoLinks('accountingStatus.html')` |
| Advanced | Accounting | false | http://192.168.29.1/platform.cgi?page=accounting.html | `Advanced > Administration > Accounting` | `gotoLinks('accounting.html')` |
| Network | RIPng | true | http://192.168.29.1/platform.cgi?page=ripng.html | `Network > Routing > RIPng` | `gotoLinks('ripng.html')` |
| Advanced | Unauthorized Usage Prevention | false | http://192.168.29.1/platform.cgi?page=unauthorizedUsage.html | `Advanced > Security > Unauthorized Usage Prevention` | `gotoLinks('unauthorizedUsage.html')` |
| Security | P2P Session Limitation | true | http://192.168.29.1/platform.cgi?page=p2pSessionLimitation.html | `Security > Attack Checks > P2P Session Limitation` | `gotoLinks('p2pSessionLimitation.html')` |
| Advanced | FTP Server | true | http://192.168.29.1/platform.cgi?page=ftpServer.html | `Advanced > FTP Server` | `gotoLinks('ftpServer.html')` |
| Advanced | MAP-T Available Ports | false | http://192.168.29.1/platform.cgi?page=maptAvailablePorts.html | `Advanced > Status > MAP-T Available Ports` | `gotoLinks('maptAvailablePorts.html')` |
| Advanced | MAP-T Port Statistics | false | http://192.168.29.1/platform.cgi?page=maptPortStats.html | `Advanced > Status > MAP-T Port Statistics` | `gotoLinks('maptPortStats.html')` |
| Administration | Switch Firmware | false | http://192.168.29.1/platform.cgi?page=switchFirmware.html | `Administration > Maintenance > Switch Firmware` | `gotoLinks('switchFirmware.html')` |
| Advanced | DMZ IPv4 Host | false | http://192.168.29.1/platform.cgi?page=dmzHost.html | `Advanced > Network > DMZ IPv4 Host` | `gotoLinks('dmzHost.html')` |
| Administration | Web Management | false | http://192.168.29.1/platform.cgi?page=webManagement.html | `Administration > Web Management` | `gotoLinks('webManagement.html')` |
| Status | LAN IPv6 Clients | true | http://192.168.29.1/platform.cgi?page=lanDhcpV6LeasedClients.html | `Status > LAN Clients > LAN IPv6 Clients` | `gotoLinks('lanDhcpV6LeasedClients.html')` |
| Network | WAN Port Configuration | false | http://192.168.29.1/platform.cgi?page=wanPortType.html | `Network > WAN > WAN Port Configuration` | `gotoLinks('wanPortType.html')` |
| Advanced | ACS Password Generation | false | http://192.168.29.1/platform.cgi?page=acsPasswordGeneration.html | `Advanced > ACS Password Generation` | `gotoLinks('acsPasswordGeneration.html')` |
| Security | Client Access Control | false | http://192.168.29.1/platform.cgi?page=clientAccessControl.html | `Security > Firewall > Client Access Control` | `gotoLinks('clientAccessControl.html')` |
| Network | EoGRE Configuration | false | http://192.168.29.1/platform.cgi?page=eogre.html | `Network > EoGRE Configuration` | `gotoLinks('eogre.html')` |
| Advanced | DMS Server Settings | false | http://192.168.29.1/platform.cgi?page=serverSettings.html | `Advanced > DMS Server Settings` | `gotoLinks('serverSettings.html')` |
| Network | Basic Configuration 5GHz | false | http://192.168.29.1/platform.cgi?page=radioBasicConfig5GHz.html | `Network > Wireless > Basic Configuration 5GHz` | `gotoLinks('radioBasicConfig5GHz.html')` |
| Dashboard | Dashboard | false | http://192.168.29.1/platform.cgi?page=dashboard.html | `Dashboard` | `gotoLinks('dashboard.html')` |
| Network | Advanced Configuration 5GHz | false | http://192.168.29.1/platform.cgi?page=radioadvancedConfig5GHz.html | `Network > Wireless > Advanced Configuration 5GHz` | `gotoLinks('radioadvancedConfig5GHz.html')` |
| Network | Basic Configuration 2.4GHz | false | http://192.168.29.1/platform.cgi?page=radioBasicConfig24GHz.html | `Network > Wireless > Basic Configuration 2.4GHz` | `gotoLinks('radioBasicConfig24GHz.html')` |
| Network | Advanced Configuration 2.4GHz | false | http://192.168.29.1/platform.cgi?page=radioadvancedConfig24GHz.html | `Network > Wireless > Advanced Configuration 2.4GHz` | `gotoLinks('radioadvancedConfig24GHz.html')` |
| QoS | DSCP To 802.1P Mapping | false | http://192.168.29.1/platform.cgi?page=dscpToCosMapping.html | `QoS > DSCP To 802.1P Mapping` | `gotoLinks('dscpToCosMapping.html')` |
| Security | IPv6 Firewall Rules | false | http://192.168.29.1/platform.cgi?page=firewallRulesIPv6.html | `Security > Firewall > IPv6 Firewall Rules` | `gotoLinks('firewallRulesIPv6.html')` |
| Security | Drop Invalid Connections | false | http://192.168.29.1/platform.cgi?page=dropInvalidConnections.html | `Security > Drop Invalid Connections` | `gotoLinks('dropInvalidConnections.html')` |
| Administration | Capture Packets | false | http://192.168.29.1/platform.cgi?page=diagnosticsPtrace.html | `Administration > Diagnostics > Capture Packets` | `gotoLinks('diagnosticsPtrace.html')` |
| Network | AP Group Name | false | http://192.168.29.1/platform.cgi?page=apGroupName.html | `Network > Wireless > AP Group Name` | `gotoLinks('apGroupName.html')` |
| Advanced | Network Sharing [DLNA] | false | http://192.168.29.1/platform.cgi?page=networkSharing.html | `Advanced > Network Sharing [DLNA]` | `gotoLinks('networkSharing.html')` |
| Advanced | DMZ IPv6 Host | false | http://192.168.29.1/platform.cgi?page=dmzV6Host.html | `Advanced > Network > DMZ IPv6 Host` | `gotoLinks('dmzV6Host.html')` |
| Network | MAC Filter | false | http://192.168.29.1/platform.cgi?page=macFiltering.html | `Network > Wireless > MAC Filter` | `gotoLinks('macFiltering.html')` |
| Network | Allot | false | http://192.168.29.1/platform.cgi?page=allot.html | `Network > Wireless > Allot` | `gotoLinks('allot.html')` |
| Advanced | Easy Mesh | false | http://192.168.29.1/platform.cgi?page=easyMesh.html | `Advanced > Easy Mesh` | `gotoLinks('easyMesh.html')` |
| Advanced | IPsec VPN | false | http://192.168.29.1/platform.cgi?page=policies.html | `Advanced > IPsec VPN` | `gotoLinks('policies.html')` |
| Advanced | WiFi Configuration | false | http://192.168.29.1/platform.cgi?page=wifiOnOff.html | `Advanced > WIFI ONOFF` | `gotoLinks('wifiOnOff.html')` |
| Advanced | Mesh Topology  | true | http://192.168.29.1/platform.cgi?page=meshTopology.html | `Advanced > Mesh Topology` | `gotoLinks('meshTopology.html')` |
| Network | IEEE 1905 | true | http://192.168.29.1/platform.cgi?page=ieee1905.html | `Network > Wireless > IEEE1905` | `gotoLinks('ieee1905.html')` |
| Security | Device Access | true | http://192.168.29.1/platform.cgi?page=deviceAccess.html | `Security > Device Access` | `gotoLinks('deviceAccess.html')` |
