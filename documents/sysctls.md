# Network Sysctls

| sysctl             | Kernel var | Description |
| ------------------ | ---------- | ----------- |
| bpf_jit_enable     |
| bpf_jit_harden     |
| bpf_jit_kallsyms   |
| busy_poll          |
| busy_read          |
| default_qdisc      | 
| dev_weight         |
| dev_weight_rx_bias |
| dev_weight_tx_bias |
| flow_limit_cpu_bitmap | 
| flow_limit_table_len  | 
| max_skb_frags      | 
| message_burst      | 
| message_cost       | 
| netdev_budget      |
| netdev_budget_usecs|
| netdev_max_backlog |
| netdev_rss_key     |
| netdev_tstamp_prequeue |
| optmem_max         | 
| rmem_default       |
| rmem_max           |
| rps_sock_flow_entries | 
| somaxconn          | 
| tstamp_allow_data  | 
| warnings           | 
| wmem_default       | 
| wmem_max           | 
| xfrm_acq_expires   | 
| xfrm_aevent_etime  | 
| xfrm_aevent_rseqth | 
| xfrm_larval_drop   | 
| **net.ipv4 (cipso v4)**
| cipso_cache_bucket_size |
| cipso_cache_enable |
| cipso_rbm_optfmt   |
| cipso_rbm_strictvalid |
| **net.ipv4 (icmp)**
| icmp_echo_ignore_all  |
| icmp_echo_ignore_broadcasts       |
| icmp_errors_use_inbound_ifaddr    |
| icmp_ignore_bogus_error_responses |
| icmp_msgs_burst    |
| icmp_msgs_per_sec  |
| icmp_ratelimit     |
| icmp_ratemask      |
| **net.ipv4 (igmp)**
| igmp_link_local_mcast_reports | 
| igmp_max_memberships | 
| igmp_max_msf         | 
| igmp_qrv             | 
| **net.ipv4 (core ip)**
| ip_default_ttl   | 
| ip_dynaddr       | 
| ip_early_demux   | 
| ip_forward       | 
| ip_forward_use_pmtu | 
| ip_local_port_range | 
| ip_local_reserved_ports |
| ip_no_pmtu_disc  | 
| ip_nonlocal_bind | 
| ip_unprivileged_port_start | 
| ipfrag_high_thresh | 
| ipfrag_low_thresh  | 
| ipfrag_max_dist    | 
| ipfrag_secret_interval | 
| ipfrag_time        | 
| **net.ipv4 (neigh)**
| neigh.default.anycast_delay | 
| neigh.default.app_solicit   | 
| neigh.default.base_reachable_time_ms | 
| neigh.default.delay_first_probe_time | 
| neigh.default.gc_interval   | 
| neigh.default.gc_stale_time | 
| neigh.default.gc_thresh1    | 
| neigh.default.gc_thresh2    | 
| neigh.default.gc_thresh3    | 
| neigh.default.locktime      | 
| neigh.default.mcast_resolicit | 
| neigh.default.mcast_solicit | 
| neigh.default.proxy_delay   | 
| neigh.default.proxy_qlen    | 
| neigh.default.retrans_time_ms | 
| neigh.default.ucast_solicit | 
| neigh.default.unres_qlen    | 
| neigh.default.unres_qlen_bytes | 
| **net.ipv4 (route)**
| route.error_burst   | 
| route.error_cost    | 
| route.gc_elasticity | 
| route.gc_interval   | 
| route.gc_min_interval | 
| route.gc_min_interval_ms | 
| route.gc_thresh     | 
| route.gc_timeout    | 
| route.max_size      | 
| route.min_adv_mss   | 
| route.min_pmtu      | 
| route.mtu_expires   | 
| route.redirect_load | 
| route.redirect_number  | 
| route.redirect_silence | 
| **net.ipv4 (tcp)**
| tcp_abort_on_overflow | 
| tcp_adv_win_scale     | 
| tcp_allowed_congestion_control | 
| tcp_app_win           |  
| tcp_autocorking       |
| tcp_available_congestion_control | 
| tcp_available_ulp     |
| tcp_base_mss          | 
| tcp_challenge_ack_limit | 
| tcp_congestion_control | 
| tcp_dsack             | 
| tcp_early_demux       | 
| tcp_early_retrans     | 
| tcp_ecn               | 
| tcp_ecn_fallback      | 
| tcp_fack              | 
| tcp_fastopen          | 
| tcp_fastopen_blackhole_timeout_sec | 
| tcp_fastopen_key      | 
| tcp_fin_timeout       | 
| tcp_frto              | 
| tcp_fwmark_accept     | 
| tcp_invalid_ratelimit | 
| tcp_keepalive_intvl   | 
| tcp_keepalive_probes  | 
| tcp_keepalive_time    | 
| tcp_l3mdev_accept     | 
| tcp_limit_output_bytes | 
| tcp_low_latency       | 
| tcp_max_orphans       | 
| tcp_max_reordering    | 
| tcp_max_syn_backlog   | 
| tcp_max_tw_buckets    | 
| tcp_mem               | 
| tcp_min_rtt_wlen      | 
| tcp_min_tso_segs      | 
| tcp_moderate_rcvbuf   | 
| tcp_mtu_probing       | 
| tcp_no_metrics_save   | 
| tcp_notsent_lowat     | 
| tcp_orphan_retries    | 
| tcp_pacing_ca_ratio   | 
| tcp_pacing_ss_ratio   | 
| tcp_probe_interval    | 
| tcp_probe_threshold   | 
| tcp_recovery          | 
| tcp_reordering        | 
| tcp_retrans_collapse  | 
| tcp_retries1          | 
| tcp_retries2          | 
| tcp_rfc1337           | 
| tcp_rmem              | 
| tcp_sack              | 
| tcp_slow_start_after_idle | 
| tcp_stdurg            | 
| tcp_syn_retries       | 
| tcp_synack_retries    | 
| tcp_syncookies        | 
| tcp_thin_linear_timeouts | 
| tcp_timestamps        | 
| tcp_tso_win_divisor   | 
| tcp_tw_reuse          | 
| tcp_window_scaling    | 
| tcp_wmem              | 
| tcp_workaround_signed_windows | 
| **net.ipv4 (udp)**
| udp_early_demux   | 
| udp_l3mdev_accept | 
| udp_mem           | 
| udp_rmem_min      | 
| udp_wmem_min      | 
| **conf.all / conf.default / conf.$iface**
| accept_local     | 
| accept_redirects | 
| accept_source_route | 
| arp_accept       | 
| arp_announce     | 
| arp_filter | 
| arp_ignore | 
| arp_notify | 
| bootp_relay | 
| disable_policy | 
| disable_xfrm | 
| drop_gratuitous_arp | 
| drop_unicast_in_l2_multicast | 
| force_igmp_version | 
| forwarding | 
| igmpv2_unsolicited_report_interval | 
| igmpv3_unsolicited_report_interval | 
| ignore_routes_with_linkdown | 
| log_martians | 
| mc_forwarding | 
| medium_id | 
| promote_secondaries | 
| proxy_arp | 
| proxy_arp_pvlan | 
| route_localnet | 
| rp_filter | 
| secure_redirects | 
| send_redirects | 
| shared_media | 
| src_valid_mark | 
| tag | 

