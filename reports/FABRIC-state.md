# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed |
| ----------- | ------------------ | ------------------ |
| 238 | 228 | 10 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| DC1-LEAF1A |  48 | 46 | 2 | NTP, Interface State |
| DC1-LEAF1B |  48 | 46 | 2 | NTP, Interface State |
| DC1-LEAF2A |  48 | 46 | 2 | NTP, Interface State |
| DC1-LEAF2B |  48 | 46 | 2 | NTP, Interface State |
| DC1-SPINE1 |  23 | 22 | 1 | NTP |
| DC1-SPINE2 |  23 | 22 | 1 | NTP |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  6 | 0 | 6 |
| Interface State |  90 | 86 | 4 |
| LLDP Topology |  24 | 24 | 0 |
| MLAG |  4 | 4 | 0 |
| IP Reachability |  16 | 16 | 0 |
| BGP |  42 | 42 | 0 |
| Routing Table |  32 | 32 | 0 |
| Loopback0 Reachability |  24 | 24 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | DC1-LEAF1A | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 2 | DC1-LEAF1B | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 3 | DC1-LEAF2A | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 4 | DC1-LEAF2B | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 5 | DC1-SPINE1 | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 6 | DC1-SPINE2 | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 36 | DC1-LEAF1A | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel5 - dc1-leaf1-server1_PortChannel dc1-leaf1-server1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 38 | DC1-LEAF1B | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel5 - dc1-leaf1-server1_PortChannel dc1-leaf1-server1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 40 | DC1-LEAF2A | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel5 - dc1-leaf2-server1_PortChannel dc1-leaf2-server1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 42 | DC1-LEAF2B | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel5 - dc1-leaf2-server1_PortChannel dc1-leaf2-server1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | DC1-LEAF1A | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 2 | DC1-LEAF1B | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 3 | DC1-LEAF2A | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 4 | DC1-LEAF2B | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 5 | DC1-SPINE1 | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 6 | DC1-SPINE2 | NTP | Synchronised with NTP server | NTP | FAIL | Not synchronised to NTP server |
| 7 | DC1-LEAF1A | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_DC1-LEAF1B_Ethernet3 | PASS | - |
| 8 | DC1-LEAF1A | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_DC1-LEAF1B_Ethernet4 | PASS | - |
| 9 | DC1-LEAF1A | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_DC1-SPINE1_Ethernet1 | PASS | - |
| 10 | DC1-LEAF1A | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_DC1-SPINE2_Ethernet1 | PASS | - |
| 11 | DC1-LEAF1A | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - dc1-leaf1-server1_PCI1 | PASS | - |
| 12 | DC1-LEAF1B | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_DC1-LEAF1A_Ethernet3 | PASS | - |
| 13 | DC1-LEAF1B | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_DC1-LEAF1A_Ethernet4 | PASS | - |
| 14 | DC1-LEAF1B | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_DC1-SPINE1_Ethernet2 | PASS | - |
| 15 | DC1-LEAF1B | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_DC1-SPINE2_Ethernet2 | PASS | - |
| 16 | DC1-LEAF1B | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - dc1-leaf1-server1_PCI2 | PASS | - |
| 17 | DC1-LEAF2A | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_DC1-LEAF2B_Ethernet3 | PASS | - |
| 18 | DC1-LEAF2A | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_DC1-LEAF2B_Ethernet4 | PASS | - |
| 19 | DC1-LEAF2A | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_DC1-SPINE1_Ethernet3 | PASS | - |
| 20 | DC1-LEAF2A | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_DC1-SPINE2_Ethernet3 | PASS | - |
| 21 | DC1-LEAF2A | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - dc1-leaf2-server1_PCI1 | PASS | - |
| 22 | DC1-LEAF2B | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_DC1-LEAF2A_Ethernet3 | PASS | - |
| 23 | DC1-LEAF2B | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_DC1-LEAF2A_Ethernet4 | PASS | - |
| 24 | DC1-LEAF2B | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_DC1-SPINE1_Ethernet4 | PASS | - |
| 25 | DC1-LEAF2B | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_DC1-SPINE2_Ethernet4 | PASS | - |
| 26 | DC1-LEAF2B | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - dc1-leaf2-server1_PCI2 | PASS | - |
| 27 | DC1-SPINE1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_DC1-LEAF1A_Ethernet1 | PASS | - |
| 28 | DC1-SPINE1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_DC1-LEAF1B_Ethernet1 | PASS | - |
| 29 | DC1-SPINE1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_DC1-LEAF2A_Ethernet1 | PASS | - |
| 30 | DC1-SPINE1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_DC1-LEAF2B_Ethernet1 | PASS | - |
| 31 | DC1-SPINE2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_DC1-LEAF1A_Ethernet2 | PASS | - |
| 32 | DC1-SPINE2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_DC1-LEAF1B_Ethernet2 | PASS | - |
| 33 | DC1-SPINE2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_DC1-LEAF2A_Ethernet2 | PASS | - |
| 34 | DC1-SPINE2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_DC1-LEAF2B_Ethernet2 | PASS | - |
| 35 | DC1-LEAF1A | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_DC1-LEAF1B_Po3 | PASS | - |
| 36 | DC1-LEAF1A | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel5 - dc1-leaf1-server1_PortChannel dc1-leaf1-server1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 37 | DC1-LEAF1B | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_DC1-LEAF1A_Po3 | PASS | - |
| 38 | DC1-LEAF1B | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel5 - dc1-leaf1-server1_PortChannel dc1-leaf1-server1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 39 | DC1-LEAF2A | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_DC1-LEAF2B_Po3 | PASS | - |
| 40 | DC1-LEAF2A | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel5 - dc1-leaf2-server1_PortChannel dc1-leaf2-server1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 41 | DC1-LEAF2B | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_DC1-LEAF2A_Po3 | PASS | - |
| 42 | DC1-LEAF2B | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel5 - dc1-leaf2-server1_PortChannel dc1-leaf2-server1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 43 | DC1-LEAF1A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 44 | DC1-LEAF1A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 45 | DC1-LEAF1A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan11 - VRF10_VLAN11 | PASS | - |
| 46 | DC1-LEAF1A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan12 - VRF10_VLAN12 | PASS | - |
| 47 | DC1-LEAF1A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 | PASS | - |
| 48 | DC1-LEAF1A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan21 - VRF11_VLAN21 | PASS | - |
| 49 | DC1-LEAF1A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan22 - VRF11_VLAN22 | PASS | - |
| 50 | DC1-LEAF1A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 | PASS | - |
| 51 | DC1-LEAF1B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 52 | DC1-LEAF1B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 53 | DC1-LEAF1B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan11 - VRF10_VLAN11 | PASS | - |
| 54 | DC1-LEAF1B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan12 - VRF10_VLAN12 | PASS | - |
| 55 | DC1-LEAF1B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 | PASS | - |
| 56 | DC1-LEAF1B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan21 - VRF11_VLAN21 | PASS | - |
| 57 | DC1-LEAF1B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan22 - VRF11_VLAN22 | PASS | - |
| 58 | DC1-LEAF1B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 | PASS | - |
| 59 | DC1-LEAF2A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 60 | DC1-LEAF2A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 61 | DC1-LEAF2A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan11 - VRF10_VLAN11 | PASS | - |
| 62 | DC1-LEAF2A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan12 - VRF10_VLAN12 | PASS | - |
| 63 | DC1-LEAF2A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 | PASS | - |
| 64 | DC1-LEAF2A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan21 - VRF11_VLAN21 | PASS | - |
| 65 | DC1-LEAF2A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan22 - VRF11_VLAN22 | PASS | - |
| 66 | DC1-LEAF2A | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 | PASS | - |
| 67 | DC1-LEAF2B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 68 | DC1-LEAF2B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 69 | DC1-LEAF2B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan11 - VRF10_VLAN11 | PASS | - |
| 70 | DC1-LEAF2B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan12 - VRF10_VLAN12 | PASS | - |
| 71 | DC1-LEAF2B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 | PASS | - |
| 72 | DC1-LEAF2B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan21 - VRF11_VLAN21 | PASS | - |
| 73 | DC1-LEAF2B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan22 - VRF11_VLAN22 | PASS | - |
| 74 | DC1-LEAF2B | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 | PASS | - |
| 75 | DC1-LEAF1A | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 76 | DC1-LEAF1B | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 77 | DC1-LEAF2A | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 78 | DC1-LEAF2B | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 79 | DC1-LEAF1A | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 80 | DC1-LEAF1A | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 81 | DC1-LEAF1A | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback10 - VRF10_VTEP_DIAGNOSTICS | PASS | - |
| 82 | DC1-LEAF1A | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback11 - VRF11_VTEP_DIAGNOSTICS | PASS | - |
| 83 | DC1-LEAF1B | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 84 | DC1-LEAF1B | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 85 | DC1-LEAF1B | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback10 - VRF10_VTEP_DIAGNOSTICS | PASS | - |
| 86 | DC1-LEAF1B | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback11 - VRF11_VTEP_DIAGNOSTICS | PASS | - |
| 87 | DC1-LEAF2A | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 88 | DC1-LEAF2A | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 89 | DC1-LEAF2A | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback10 - VRF10_VTEP_DIAGNOSTICS | PASS | - |
| 90 | DC1-LEAF2A | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback11 - VRF11_VTEP_DIAGNOSTICS | PASS | - |
| 91 | DC1-LEAF2B | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 92 | DC1-LEAF2B | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 93 | DC1-LEAF2B | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback10 - VRF10_VTEP_DIAGNOSTICS | PASS | - |
| 94 | DC1-LEAF2B | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback11 - VRF11_VTEP_DIAGNOSTICS | PASS | - |
| 95 | DC1-SPINE1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 96 | DC1-SPINE2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 97 | DC1-LEAF1A | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: DC1-LEAF1B_Ethernet3 | PASS | - |
| 98 | DC1-LEAF1A | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: DC1-LEAF1B_Ethernet4 | PASS | - |
| 99 | DC1-LEAF1A | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: DC1-SPINE1_Ethernet1 | PASS | - |
| 100 | DC1-LEAF1A | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: DC1-SPINE2_Ethernet1 | PASS | - |
| 101 | DC1-LEAF1B | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: DC1-LEAF1A_Ethernet3 | PASS | - |
| 102 | DC1-LEAF1B | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: DC1-LEAF1A_Ethernet4 | PASS | - |
| 103 | DC1-LEAF1B | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: DC1-SPINE1_Ethernet2 | PASS | - |
| 104 | DC1-LEAF1B | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: DC1-SPINE2_Ethernet2 | PASS | - |
| 105 | DC1-LEAF2A | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: DC1-LEAF2B_Ethernet3 | PASS | - |
| 106 | DC1-LEAF2A | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: DC1-LEAF2B_Ethernet4 | PASS | - |
| 107 | DC1-LEAF2A | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: DC1-SPINE1_Ethernet3 | PASS | - |
| 108 | DC1-LEAF2A | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: DC1-SPINE2_Ethernet3 | PASS | - |
| 109 | DC1-LEAF2B | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: DC1-LEAF2A_Ethernet3 | PASS | - |
| 110 | DC1-LEAF2B | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: DC1-LEAF2A_Ethernet4 | PASS | - |
| 111 | DC1-LEAF2B | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: DC1-SPINE1_Ethernet4 | PASS | - |
| 112 | DC1-LEAF2B | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: DC1-SPINE2_Ethernet4 | PASS | - |
| 113 | DC1-SPINE1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: DC1-LEAF1A_Ethernet1 | PASS | - |
| 114 | DC1-SPINE1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: DC1-LEAF1B_Ethernet1 | PASS | - |
| 115 | DC1-SPINE1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: DC1-LEAF2A_Ethernet1 | PASS | - |
| 116 | DC1-SPINE1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: DC1-LEAF2B_Ethernet1 | PASS | - |
| 117 | DC1-SPINE2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: DC1-LEAF1A_Ethernet2 | PASS | - |
| 118 | DC1-SPINE2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: DC1-LEAF1B_Ethernet2 | PASS | - |
| 119 | DC1-SPINE2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: DC1-LEAF2A_Ethernet2 | PASS | - |
| 120 | DC1-SPINE2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: DC1-LEAF2B_Ethernet2 | PASS | - |
| 121 | DC1-LEAF1A | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 122 | DC1-LEAF1B | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 123 | DC1-LEAF2A | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 124 | DC1-LEAF2B | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 125 | DC1-LEAF1A | IP Reachability | ip reachability test p2p links | Source: DC1-LEAF1A_Ethernet1 - Destination: DC1-SPINE1_Ethernet1 | PASS | - |
| 126 | DC1-LEAF1A | IP Reachability | ip reachability test p2p links | Source: DC1-LEAF1A_Ethernet2 - Destination: DC1-SPINE2_Ethernet1 | PASS | - |
| 127 | DC1-LEAF1B | IP Reachability | ip reachability test p2p links | Source: DC1-LEAF1B_Ethernet1 - Destination: DC1-SPINE1_Ethernet2 | PASS | - |
| 128 | DC1-LEAF1B | IP Reachability | ip reachability test p2p links | Source: DC1-LEAF1B_Ethernet2 - Destination: DC1-SPINE2_Ethernet2 | PASS | - |
| 129 | DC1-LEAF2A | IP Reachability | ip reachability test p2p links | Source: DC1-LEAF2A_Ethernet1 - Destination: DC1-SPINE1_Ethernet3 | PASS | - |
| 130 | DC1-LEAF2A | IP Reachability | ip reachability test p2p links | Source: DC1-LEAF2A_Ethernet2 - Destination: DC1-SPINE2_Ethernet3 | PASS | - |
| 131 | DC1-LEAF2B | IP Reachability | ip reachability test p2p links | Source: DC1-LEAF2B_Ethernet1 - Destination: DC1-SPINE1_Ethernet4 | PASS | - |
| 132 | DC1-LEAF2B | IP Reachability | ip reachability test p2p links | Source: DC1-LEAF2B_Ethernet2 - Destination: DC1-SPINE2_Ethernet4 | PASS | - |
| 133 | DC1-SPINE1 | IP Reachability | ip reachability test p2p links | Source: DC1-SPINE1_Ethernet1 - Destination: DC1-LEAF1A_Ethernet1 | PASS | - |
| 134 | DC1-SPINE1 | IP Reachability | ip reachability test p2p links | Source: DC1-SPINE1_Ethernet2 - Destination: DC1-LEAF1B_Ethernet1 | PASS | - |
| 135 | DC1-SPINE1 | IP Reachability | ip reachability test p2p links | Source: DC1-SPINE1_Ethernet3 - Destination: DC1-LEAF2A_Ethernet1 | PASS | - |
| 136 | DC1-SPINE1 | IP Reachability | ip reachability test p2p links | Source: DC1-SPINE1_Ethernet4 - Destination: DC1-LEAF2B_Ethernet1 | PASS | - |
| 137 | DC1-SPINE2 | IP Reachability | ip reachability test p2p links | Source: DC1-SPINE2_Ethernet1 - Destination: DC1-LEAF1A_Ethernet2 | PASS | - |
| 138 | DC1-SPINE2 | IP Reachability | ip reachability test p2p links | Source: DC1-SPINE2_Ethernet2 - Destination: DC1-LEAF1B_Ethernet2 | PASS | - |
| 139 | DC1-SPINE2 | IP Reachability | ip reachability test p2p links | Source: DC1-SPINE2_Ethernet3 - Destination: DC1-LEAF2A_Ethernet2 | PASS | - |
| 140 | DC1-SPINE2 | IP Reachability | ip reachability test p2p links | Source: DC1-SPINE2_Ethernet4 - Destination: DC1-LEAF2B_Ethernet2 | PASS | - |
| 141 | DC1-LEAF1A | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 142 | DC1-LEAF1B | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 143 | DC1-LEAF2A | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 144 | DC1-LEAF2B | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 145 | DC1-SPINE1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 146 | DC1-SPINE2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 147 | DC1-LEAF1A | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.1.97 | PASS | - |
| 148 | DC1-LEAF1A | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.0 | PASS | - |
| 149 | DC1-LEAF1A | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.2 | PASS | - |
| 150 | DC1-LEAF1B | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.1.96 | PASS | - |
| 151 | DC1-LEAF1B | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.4 | PASS | - |
| 152 | DC1-LEAF1B | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.6 | PASS | - |
| 153 | DC1-LEAF2A | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.1.101 | PASS | - |
| 154 | DC1-LEAF2A | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.8 | PASS | - |
| 155 | DC1-LEAF2A | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.10 | PASS | - |
| 156 | DC1-LEAF2B | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.1.100 | PASS | - |
| 157 | DC1-LEAF2B | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.12 | PASS | - |
| 158 | DC1-LEAF2B | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.14 | PASS | - |
| 159 | DC1-SPINE1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.1 | PASS | - |
| 160 | DC1-SPINE1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.5 | PASS | - |
| 161 | DC1-SPINE1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.9 | PASS | - |
| 162 | DC1-SPINE1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.13 | PASS | - |
| 163 | DC1-SPINE2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.3 | PASS | - |
| 164 | DC1-SPINE2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.7 | PASS | - |
| 165 | DC1-SPINE2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.11 | PASS | - |
| 166 | DC1-SPINE2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.255.15 | PASS | - |
| 167 | DC1-LEAF1A | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.1 | PASS | - |
| 168 | DC1-LEAF1A | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.2 | PASS | - |
| 169 | DC1-LEAF1B | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.1 | PASS | - |
| 170 | DC1-LEAF1B | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.2 | PASS | - |
| 171 | DC1-LEAF2A | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.1 | PASS | - |
| 172 | DC1-LEAF2A | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.2 | PASS | - |
| 173 | DC1-LEAF2B | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.1 | PASS | - |
| 174 | DC1-LEAF2B | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.2 | PASS | - |
| 175 | DC1-SPINE1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.3 | PASS | - |
| 176 | DC1-SPINE1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.4 | PASS | - |
| 177 | DC1-SPINE1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.5 | PASS | - |
| 178 | DC1-SPINE1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.6 | PASS | - |
| 179 | DC1-SPINE2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.3 | PASS | - |
| 180 | DC1-SPINE2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.4 | PASS | - |
| 181 | DC1-SPINE2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.5 | PASS | - |
| 182 | DC1-SPINE2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.255.0.6 | PASS | - |
| 183 | DC1-LEAF1A | Routing Table | Remote VTEP address | 10.255.1.3 | PASS | - |
| 184 | DC1-LEAF1A | Routing Table | Remote VTEP address | 10.255.1.5 | PASS | - |
| 185 | DC1-LEAF1B | Routing Table | Remote VTEP address | 10.255.1.3 | PASS | - |
| 186 | DC1-LEAF1B | Routing Table | Remote VTEP address | 10.255.1.5 | PASS | - |
| 187 | DC1-LEAF2A | Routing Table | Remote VTEP address | 10.255.1.3 | PASS | - |
| 188 | DC1-LEAF2A | Routing Table | Remote VTEP address | 10.255.1.5 | PASS | - |
| 189 | DC1-LEAF2B | Routing Table | Remote VTEP address | 10.255.1.3 | PASS | - |
| 190 | DC1-LEAF2B | Routing Table | Remote VTEP address | 10.255.1.5 | PASS | - |
| 191 | DC1-LEAF1A | Routing Table | Remote Lo0 address | 10.255.0.3 | PASS | - |
| 192 | DC1-LEAF1A | Routing Table | Remote Lo0 address | 10.255.0.4 | PASS | - |
| 193 | DC1-LEAF1A | Routing Table | Remote Lo0 address | 10.255.0.5 | PASS | - |
| 194 | DC1-LEAF1A | Routing Table | Remote Lo0 address | 10.255.0.6 | PASS | - |
| 195 | DC1-LEAF1A | Routing Table | Remote Lo0 address | 10.255.0.1 | PASS | - |
| 196 | DC1-LEAF1A | Routing Table | Remote Lo0 address | 10.255.0.2 | PASS | - |
| 197 | DC1-LEAF1B | Routing Table | Remote Lo0 address | 10.255.0.3 | PASS | - |
| 198 | DC1-LEAF1B | Routing Table | Remote Lo0 address | 10.255.0.4 | PASS | - |
| 199 | DC1-LEAF1B | Routing Table | Remote Lo0 address | 10.255.0.5 | PASS | - |
| 200 | DC1-LEAF1B | Routing Table | Remote Lo0 address | 10.255.0.6 | PASS | - |
| 201 | DC1-LEAF1B | Routing Table | Remote Lo0 address | 10.255.0.1 | PASS | - |
| 202 | DC1-LEAF1B | Routing Table | Remote Lo0 address | 10.255.0.2 | PASS | - |
| 203 | DC1-LEAF2A | Routing Table | Remote Lo0 address | 10.255.0.3 | PASS | - |
| 204 | DC1-LEAF2A | Routing Table | Remote Lo0 address | 10.255.0.4 | PASS | - |
| 205 | DC1-LEAF2A | Routing Table | Remote Lo0 address | 10.255.0.5 | PASS | - |
| 206 | DC1-LEAF2A | Routing Table | Remote Lo0 address | 10.255.0.6 | PASS | - |
| 207 | DC1-LEAF2A | Routing Table | Remote Lo0 address | 10.255.0.1 | PASS | - |
| 208 | DC1-LEAF2A | Routing Table | Remote Lo0 address | 10.255.0.2 | PASS | - |
| 209 | DC1-LEAF2B | Routing Table | Remote Lo0 address | 10.255.0.3 | PASS | - |
| 210 | DC1-LEAF2B | Routing Table | Remote Lo0 address | 10.255.0.4 | PASS | - |
| 211 | DC1-LEAF2B | Routing Table | Remote Lo0 address | 10.255.0.5 | PASS | - |
| 212 | DC1-LEAF2B | Routing Table | Remote Lo0 address | 10.255.0.6 | PASS | - |
| 213 | DC1-LEAF2B | Routing Table | Remote Lo0 address | 10.255.0.1 | PASS | - |
| 214 | DC1-LEAF2B | Routing Table | Remote Lo0 address | 10.255.0.2 | PASS | - |
| 215 | DC1-LEAF1A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1A - 10.255.0.3 Destination: 10.255.0.3 | PASS | - |
| 216 | DC1-LEAF1A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1A - 10.255.0.3 Destination: 10.255.0.4 | PASS | - |
| 217 | DC1-LEAF1A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1A - 10.255.0.3 Destination: 10.255.0.5 | PASS | - |
| 218 | DC1-LEAF1A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1A - 10.255.0.3 Destination: 10.255.0.6 | PASS | - |
| 219 | DC1-LEAF1A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1A - 10.255.0.3 Destination: 10.255.0.1 | PASS | - |
| 220 | DC1-LEAF1A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1A - 10.255.0.3 Destination: 10.255.0.2 | PASS | - |
| 221 | DC1-LEAF1B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1B - 10.255.0.4 Destination: 10.255.0.3 | PASS | - |
| 222 | DC1-LEAF1B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1B - 10.255.0.4 Destination: 10.255.0.4 | PASS | - |
| 223 | DC1-LEAF1B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1B - 10.255.0.4 Destination: 10.255.0.5 | PASS | - |
| 224 | DC1-LEAF1B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1B - 10.255.0.4 Destination: 10.255.0.6 | PASS | - |
| 225 | DC1-LEAF1B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1B - 10.255.0.4 Destination: 10.255.0.1 | PASS | - |
| 226 | DC1-LEAF1B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF1B - 10.255.0.4 Destination: 10.255.0.2 | PASS | - |
| 227 | DC1-LEAF2A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2A - 10.255.0.5 Destination: 10.255.0.3 | PASS | - |
| 228 | DC1-LEAF2A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2A - 10.255.0.5 Destination: 10.255.0.4 | PASS | - |
| 229 | DC1-LEAF2A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2A - 10.255.0.5 Destination: 10.255.0.5 | PASS | - |
| 230 | DC1-LEAF2A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2A - 10.255.0.5 Destination: 10.255.0.6 | PASS | - |
| 231 | DC1-LEAF2A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2A - 10.255.0.5 Destination: 10.255.0.1 | PASS | - |
| 232 | DC1-LEAF2A | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2A - 10.255.0.5 Destination: 10.255.0.2 | PASS | - |
| 233 | DC1-LEAF2B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2B - 10.255.0.6 Destination: 10.255.0.3 | PASS | - |
| 234 | DC1-LEAF2B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2B - 10.255.0.6 Destination: 10.255.0.4 | PASS | - |
| 235 | DC1-LEAF2B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2B - 10.255.0.6 Destination: 10.255.0.5 | PASS | - |
| 236 | DC1-LEAF2B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2B - 10.255.0.6 Destination: 10.255.0.6 | PASS | - |
| 237 | DC1-LEAF2B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2B - 10.255.0.6 Destination: 10.255.0.1 | PASS | - |
| 238 | DC1-LEAF2B | Loopback0 Reachability | Loopback0 Reachability | Source: DC1-LEAF2B - 10.255.0.6 Destination: 10.255.0.2 | PASS | - |
