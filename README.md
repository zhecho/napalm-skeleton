# napalm-hp-comware


Development Status
==================

Table of implemented methods:

    * get_arp_table                 ✅
    * get_bgp_config                ❌
    * get_bgp_neighbors             ❌
    * get_bgp_neighbors_detail      ❌
    * get_config                    ❌
    * get_environment               ❌
    * get_facts                     ✅
    * get_firewall_policies         ❌
    * get_interfaces                ✅
    * get_interfaces_counters       ❌
    * get_interfaces_ip             ❌
    * get_ipv6_neighbors_table      ❌
    * get_lldp_neighbors            ✅
    * get_lldp_neighbors_detail     ✅
    * get_mac_address_table         ✅
    * get_network_instances         ❌
    * get_ntp_peers                 ❌
    * get_ntp_servers               ❌
    * get_ntp_stats                 ❌
    * get_optics                    ❌
    * get_probes_config             ❌
    * get_probes_results            ❌
    * get_route_to                  ❌
    * get_snmp_information          ❌
    * get_users                     ❌
    * is_alive                      ❌
    * ping                          ❌
    * traceroute                    ❌
                                    
Additional Methods:
    * _generate_ssh_proxy_file      ✅
    * priviledge_escalation         ✅
    * format_mac_cisco_way          ✅
    * normalize_port_name           ✅
    * hp_mac_format                 ✅
    * get_active_physical_ports     ✅
    * trace_mac_address             ✅
    * get_version                   ✅

Installation
============

  ```
    $ pip install https://github.com/zhecho/napalm-hp-comware.git
  ```    

