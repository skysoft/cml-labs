# cml-labs

Cisco Modeling Labs (CML) labs voor **CCNA 200-301 v2.0** (Implementing and Administering Cisco Solutions).
De mappen volgen de structuur van de officiële exam topics.

## Structuur

```
<domein>/<leerdoel>/<labnummer>_<Titel>/<labnummer>_<titel>.yaml
```

Voorbeeld: `1.0_Network_Infrastructure_and_Connectivity/1.3_IPv4_Addressing/1.3.1_Storing_kantoor_en_magazijn/1.3.1_storing_kantoor_en_magazijn.yaml`

- **Domein**: de vijf examendomeinen (1.0 t/m 5.0).
- **Leerdoel**: het nummer uit de exam topics (bijv. 1.3). Elke map heeft een README met de officiële omschrijving en een overzicht van de labs.
- **Lab**: `<leerdoel>.<volgnummer>` met een neutrale titel die de oplossing niet verraadt. De studentinstructies staan in de Lab Notes van de topologie.

## Een lab gebruiken

1. Download het `.yaml`-bestand.
2. Importeer het in CML via **Import Lab**.
3. Open de **Notes** van het lab voor de opdracht.

Gebruikte node-types: `iol-xe`, `ioll2-xe`, `unmanaged_switch` en `alpine`.

## Overzicht

### [1.0 Network Infrastructure and Connectivity](1.0_Network_Infrastructure_and_Connectivity/) (25%)

| Leerdoel | Labs |
|---|---|
| [1.1 Interface and Cable Issues](1.0_Network_Infrastructure_and_Connectivity/1.1_Interface_and_Cable_Issues/) | - |
| [1.2 Virtualization](1.0_Network_Infrastructure_and_Connectivity/1.2_Virtualization/) | - |
| [1.3 IPv4 Addressing](1.0_Network_Infrastructure_and_Connectivity/1.3_IPv4_Addressing/) | 10 |
| [1.4 IPv6 Addressing](1.0_Network_Infrastructure_and_Connectivity/1.4_IPv6_Addressing/) | 10 |
| [1.5 Wireless Principles](1.0_Network_Infrastructure_and_Connectivity/1.5_Wireless_Principles/) | - |
| [1.6 Client Connectivity](1.0_Network_Infrastructure_and_Connectivity/1.6_Client_Connectivity/) | - |
| [1.7 DHCPv4](1.0_Network_Infrastructure_and_Connectivity/1.7_DHCPv4/) | - |

### [2.0 Switching and Network Access](2.0_Switching_and_Network_Access/) (25%)

| Leerdoel | Labs |
|---|---|
| [2.1 Infrastructure Connectivity](2.0_Switching_and_Network_Access/2.1_Infrastructure_Connectivity/) | - |
| [2.2 Edge Host Connectivity](2.0_Switching_and_Network_Access/2.2_Edge_Host_Connectivity/) | - |
| [2.3 CDP and LLDP](2.0_Switching_and_Network_Access/2.3_CDP_and_LLDP/) | - |
| [2.4 L2 L3 Troubleshooting](2.0_Switching_and_Network_Access/2.4_L2_L3_Troubleshooting/) | - |
| [2.5 Rapid PVST](2.0_Switching_and_Network_Access/2.5_Rapid_PVST/) | - |

### [3.0 IP Routing](3.0_IP_Routing/) (20%)

| Leerdoel | Labs |
|---|---|
| [3.1 Routing Table](3.0_IP_Routing/3.1_Routing_Table/) | - |
| [3.2 Static Routing](3.0_IP_Routing/3.2_Static_Routing/) | - |
| [3.3 OSPF](3.0_IP_Routing/3.3_OSPF/) | - |
| [3.4 FHRP](3.0_IP_Routing/3.4_FHRP/) | - |

### [4.0 Network Services and Security](4.0_Network_Services_and_Security/) (20%)

| Leerdoel | Labs |
|---|---|
| [4.1 AAA and Local Users](4.0_Network_Services_and_Security/4.1_AAA_and_Local_Users/) | - |
| [4.2 SFTP and SCP](4.0_Network_Services_and_Security/4.2_SFTP_and_SCP/) | - |
| [4.3 NAT and PAT](4.0_Network_Services_and_Security/4.3_NAT_and_PAT/) | - |
| [4.4 DNS Records](4.0_Network_Services_and_Security/4.4_DNS_Records/) | - |
| [4.5 IPsec VPN](4.0_Network_Services_and_Security/4.5_IPsec_VPN/) | - |
| [4.6 IPv4 ACLs](4.0_Network_Services_and_Security/4.6_IPv4_ACLs/) | - |
| [4.7 Layer2 Security](4.0_Network_Services_and_Security/4.7_Layer2_Security/) | - |

### [5.0 AI, and Network Operations and Management](5.0_AI_Network_Operations_and_Management/) (10%)

| Leerdoel | Labs |
|---|---|
| [5.1 Agentic AI](5.0_AI_Network_Operations_and_Management/5.1_Agentic_AI/) | - |
| [5.2 Prompting Generative AI](5.0_AI_Network_Operations_and_Management/5.2_Prompting_Generative_AI/) | - |
| [5.3 Network Management Approaches](5.0_AI_Network_Operations_and_Management/5.3_Network_Management_Approaches/) | - |
| [5.4 SNMP](5.0_AI_Network_Operations_and_Management/5.4_SNMP/) | - |
| [5.5 Ansible](5.0_AI_Network_Operations_and_Management/5.5_Ansible/) | - |
| [5.6 Syslog](5.0_AI_Network_Operations_and_Management/5.6_Syslog/) | - |
