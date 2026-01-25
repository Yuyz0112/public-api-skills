# mconn_snapshot

Snapshot

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bonds` | mconn_snapshot_bond[] | No |  |
| `count_reclaim_failures` | number | Yes | Count of failures to reclaim space |
| `count_reclaimed_paths` | number | Yes | Count of reclaimed paths |
| `count_record_failed` | number | Yes | Count of failed snapshot recordings |
| `count_transmit_failures` | number | Yes | Count of failed snapshot transmissions |
| `cpu_count` | number | No | Count of processors/cores |
| `cpu_pressure_10s` | number | No | Percentage of time over a 10 second window that tasks were stalled |
| `cpu_pressure_300s` | number | No | Percentage of time over a 5 minute window that tasks were stalled |
| `cpu_pressure_60s` | number | No | Percentage of time over a 1 minute window that tasks were stalled |
| `cpu_pressure_total_us` | number | No | Total stall time (microseconds) |
| `cpu_time_guest_ms` | number | No | Time spent running a virtual CPU or guest OS (milliseconds) |
| `cpu_time_guest_nice_ms` | number | No | Time spent running a niced guest (milliseconds) |
| `cpu_time_idle_ms` | number | No | Time spent in idle state (milliseconds) |
| `cpu_time_iowait_ms` | number | No | Time spent wait for I/O to complete (milliseconds) |
| `cpu_time_irq_ms` | number | No | Time spent servicing interrupts (milliseconds) |
| `cpu_time_nice_ms` | number | No | Time spent in low-priority user mode (milliseconds) |
| `cpu_time_softirq_ms` | number | No | Time spent servicing softirqs (milliseconds) |
| `cpu_time_steal_ms` | number | No | Time stolen (milliseconds) |
| `cpu_time_system_ms` | number | No | Time spent in system mode (milliseconds) |
| `cpu_time_user_ms` | number | No | Time spent in user mode (milliseconds) |
| `dhcp_leases` | mconn_snapshot_dhcp_lease[] | No |  |
| `disks` | mconn_snapshot_disk[] | No |  |
| `ha_state` | string | No | Name of high availability state |
| `ha_value` | number | No | Numeric value associated with high availability state (0 = disabled, 1 = active, 2 = standby, 3 = stopped, 4 = fault) |
| `interfaces` | mconn_snapshot_interface[] | No |  |
| `io_pressure_full_10s` | number | No | Percentage of time over a 10 second window that all tasks were stalled |
| `io_pressure_full_300s` | number | No | Percentage of time over a 5 minute window that all tasks were stalled |
| `io_pressure_full_60s` | number | No | Percentage of time over a 1 minute window that all tasks were stalled |
| `io_pressure_full_total_us` | number | No | Total stall time (microseconds) |
| `io_pressure_some_10s` | number | No | Percentage of time over a 10 second window that some tasks were stalled |
| `io_pressure_some_300s` | number | No | Percentage of time over a 3 minute window that some tasks were stalled |
| `io_pressure_some_60s` | number | No | Percentage of time over a 1 minute window that some tasks were stalled |
| `io_pressure_some_total_us` | number | No | Total stall time (microseconds) |
| `kernel_btime` | number | No | Boot time (seconds since Unix epoch) |
| `kernel_ctxt` | number | No | Number of context switches that the system underwent |
| `kernel_processes` | number | No | Number of forks since boot |
| `kernel_processes_blocked` | number | No | Number of processes blocked waiting for I/O |
| `kernel_processes_running` | number | No | Number of processes in runnable state |
| `load_average_15m` | number | No | The fifteen-minute load average |
| `load_average_1m` | number | No | The one-minute load average |
| `load_average_5m` | number | No | The five-minute load average |
| `load_average_cur` | number | No | Number of currently runnable kernel scheduling entities |
| `load_average_max` | number | No | Number of kernel scheduling entities that currently exist on the system |
| `memory_active_bytes` | number | No | Memory that has been used more recently |
| `memory_anon_hugepages_bytes` | number | No | Non-file backed huge pages mapped into user-space page tables |
| `memory_anon_pages_bytes` | number | No | Non-file backed pages mapped into user-space page tables |
| `memory_available_bytes` | number | No | Estimate of how much memory is available for starting new applications |
| `memory_bounce_bytes` | number | No | Memory used for block device bounce buffers |
| `memory_buffers_bytes` | number | No | Relatively temporary storage for raw disk blocks |
| `memory_cached_bytes` | number | No | In-memory cache for files read from the disk |
| `memory_cma_free_bytes` | number | No | Free CMA (Contiguous Memory Allocator) pages |
| `memory_cma_total_bytes` | number | No | Total CMA (Contiguous Memory Allocator) pages |
| `memory_commit_limit_bytes` | number | No | Total amount of memory currently available to be allocated on the system |
| `memory_committed_as_bytes` | number | No | Amount of memory presently allocated on the system |
| `memory_dirty_bytes` | number | No | Memory which is waiting to get written back to the disk |
| `memory_free_bytes` | number | No | The sum of LowFree and HighFree |
| `memory_high_free_bytes` | number | No | Amount of free highmem |
| `memory_high_total_bytes` | number | No | Total amount of highmem |
| `memory_hugepages_free` | number | No | The number of huge pages in the pool that are not yet allocated |
| `memory_hugepages_rsvd` | number | No | Number of huge pages for which a commitment has been made, but no allocation has yet been made |
| `memory_hugepages_surp` | number | No | Number of huge pages in the pool above the threshold |
| `memory_hugepages_total` | number | No | The size of the pool of huge pages |
| `memory_hugepagesize_bytes` | number | No | The size of huge pages |
| `memory_inactive_bytes` | number | No | Memory which has been less recently used |
| `memory_k_reclaimable_bytes` | number | No | Kernel allocations that the kernel will attempt to reclaim under memory pressure |
| `memory_kernel_stack_bytes` | number | No | Amount of memory allocated to kernel stacks |
| `memory_low_free_bytes` | number | No | Amount of free lowmem |
| `memory_low_total_bytes` | number | No | Total amount of lowmem |
| `memory_mapped_bytes` | number | No | Files which have been mapped into memory |
| `memory_page_tables_bytes` | number | No | Amount of memory dedicated to the lowest level of page tables |
| `memory_per_cpu_bytes` | number | No | Memory allocated to the per-cpu alloctor used to back per-cpu allocations |
| `memory_pressure_full_10s` | number | No | Percentage of time over a 10 second window that all tasks were stalled |
| `memory_pressure_full_300s` | number | No | Percentage of time over a 5 minute window that all tasks were stalled |
| `memory_pressure_full_60s` | number | No | Percentage of time over a 1 minute window that all tasks were stalled |
| `memory_pressure_full_total_us` | number | No | Total stall time (microseconds) |
| `memory_pressure_some_10s` | number | No | Percentage of time over a 10 second window that some tasks were stalled |
| `memory_pressure_some_300s` | number | No | Percentage of time over a 5 minute window that some tasks were stalled |
| `memory_pressure_some_60s` | number | No | Percentage of time over a 1 minute window that some tasks were stalled |
| `memory_pressure_some_total_us` | number | No | Total stall time (microseconds) |
| `memory_s_reclaimable_bytes` | number | No | Part of slab that can be reclaimed on memory pressure |
| `memory_s_unreclaim_bytes` | number | No | Part of slab that cannot be reclaimed on memory pressure |
| `memory_secondary_page_tables_bytes` | number | No | Amount of memory dedicated to the lowest level of page tables |
| `memory_shmem_bytes` | number | No | Amount of memory consumed by tmpfs |
| `memory_shmem_hugepages_bytes` | number | No | Memory used by shmem and tmpfs, allocated with huge pages |
| `memory_shmem_pmd_mapped_bytes` | number | No | Shared memory mapped into user space with huge pages |
| `memory_slab_bytes` | number | No | In-kernel data structures cache |
| `memory_swap_cached_bytes` | number | No | Memory swapped out and back in while still in swap file |
| `memory_swap_free_bytes` | number | No | Amount of swap space that is currently unused |
| `memory_swap_total_bytes` | number | No | Total amount of swap space available |
| `memory_total_bytes` | number | No | Total usable RAM |
| `memory_vmalloc_chunk_bytes` | number | No | Largest contiguous block of vmalloc area which is free |
| `memory_vmalloc_total_bytes` | number | No | Total size of vmalloc memory area |
| `memory_vmalloc_used_bytes` | number | No | Amount of vmalloc area which is used |
| `memory_writeback_bytes` | number | No | Memory which is actively being written back to the disk |
| `memory_writeback_tmp_bytes` | number | No | Memory used by FUSE for temporary writeback buffers |
| `memory_z_swap_bytes` | number | No | Memory consumed by the zswap backend, compressed |
| `memory_z_swapped_bytes` | number | No | Amount of anonymous memory stored in zswap, uncompressed |
| `mounts` | mconn_snapshot_mount[] | No |  |
| `netdevs` | mconn_snapshot_netdev[] | No |  |
| `snmp_icmp_in_addr_mask_reps` | number | No | Number of ICMP Address Mask Reply messages received |
| `snmp_icmp_in_addr_masks` | number | No | Number of ICMP Address Mask Request messages received |
| `snmp_icmp_in_csum_errors` | number | No | Number of ICMP messages received with bad checksums |
| `snmp_icmp_in_dest_unreachs` | number | No | Number of ICMP Destination Unreachable messages received |
| `snmp_icmp_in_echo_reps` | number | No | Number of ICMP Echo Reply messages received |
| `snmp_icmp_in_echos` | number | No | Number of ICMP Echo (request) messages received |
| `snmp_icmp_in_errors` | number | No | Number of ICMP messages received with ICMP-specific errors |
| `snmp_icmp_in_msgs` | number | No | Number of ICMP messages received |
| `snmp_icmp_in_parm_probs` | number | No | Number of ICMP Parameter Problem messages received |
| `snmp_icmp_in_redirects` | number | No | Number of ICMP Redirect messages received |
| `snmp_icmp_in_src_quenchs` | number | No | Number of ICMP Source Quench messages received |
| `snmp_icmp_in_time_excds` | number | No | Number of ICMP Time Exceeded messages received |
| `snmp_icmp_in_timestamp_reps` | number | No | Number of ICMP Address Mask Request messages received |
| `snmp_icmp_in_timestamps` | number | No | Number of ICMP Timestamp (request) messages received |
| `snmp_icmp_out_addr_mask_reps` | number | No | Number of ICMP Address Mask Reply messages sent |
| `snmp_icmp_out_addr_masks` | number | No | Number of ICMP Address Mask Request messages sent |
| `snmp_icmp_out_dest_unreachs` | number | No | Number of ICMP Destination Unreachable messages sent |
| `snmp_icmp_out_echo_reps` | number | No | Number of ICMP Echo Reply messages sent |
| `snmp_icmp_out_echos` | number | No | Number of ICMP Echo (request) messages sent |
| `snmp_icmp_out_errors` | number | No | Number of ICMP messages which this entity did not send due to ICMP-specific errors |
| `snmp_icmp_out_msgs` | number | No | Number of ICMP messages attempted to send |
| `snmp_icmp_out_parm_probs` | number | No | Number of ICMP Parameter Problem messages sent |
| `snmp_icmp_out_redirects` | number | No | Number of ICMP Redirect messages sent |
| `snmp_icmp_out_src_quenchs` | number | No | Number of ICMP Source Quench messages sent |
| `snmp_icmp_out_time_excds` | number | No | Number of ICMP Time Exceeded messages sent |
| `snmp_icmp_out_timestamp_reps` | number | No | Number of ICMP Timestamp Reply messages sent |
| `snmp_icmp_out_timestamps` | number | No | Number of ICMP Timestamp (request) messages sent |
| `snmp_ip_default_ttl` | number | No | Default value of the Time-To-Live field of the IP header |
| `snmp_ip_forw_datagrams` | number | No | Number of datagrams forwarded to their final destination |
| `snmp_ip_forwarding_enabled` | boolean | No | Set when acting as an IP gateway |
| `snmp_ip_frag_creates` | number | No | Number of datagrams generated by fragmentation |
| `snmp_ip_frag_fails` | number | No | Number of datagrams discarded because fragmentation failed |
| `snmp_ip_frag_oks` | number | No | Number of datagrams successfully fragmented |
| `snmp_ip_in_addr_errors` | number | No | Number of input datagrams discarded due to errors in the IP address |
| `snmp_ip_in_delivers` | number | No | Number of input datagrams successfully delivered to IP user-protocols |
| `snmp_ip_in_discards` | number | No | Number of input datagrams otherwise discarded |
| `snmp_ip_in_hdr_errors` | number | No | Number of input datagrams discarded due to errors in the IP header |
| `snmp_ip_in_receives` | number | No | Number of input datagrams received from interfaces |
| `snmp_ip_in_unknown_protos` | number | No | Number of input datagrams discarded due unknown or unsupported protocol |
| `snmp_ip_out_discards` | number | No | Number of output datagrams otherwise discarded |
| `snmp_ip_out_no_routes` | number | No | Number of output datagrams discarded because no route matched |
| `snmp_ip_out_requests` | number | No | Number of datagrams supplied for transmission |
| `snmp_ip_reasm_fails` | number | No | Number of failures detected by the reassembly algorithm |
| `snmp_ip_reasm_oks` | number | No | Number of datagrams successfully reassembled |
| `snmp_ip_reasm_reqds` | number | No | Number of fragments received which needed to be reassembled |
| `snmp_ip_reasm_timeout` | number | No | Number of seconds fragments are held while awaiting reassembly |
| `snmp_tcp_active_opens` | number | No | Number of times TCP transitions to SYN-SENT from CLOSED |
| `snmp_tcp_attempt_fails` | number | No | Number of times TCP transitions to CLOSED from SYN-SENT or SYN-RCVD, plus transitions to LISTEN from SYN-RCVD |
| `snmp_tcp_curr_estab` | number | No | Number of TCP connections in ESTABLISHED or CLOSE-WAIT |
| `snmp_tcp_estab_resets` | number | No | Number of times TCP transitions to CLOSED from ESTABLISHED or CLOSE-WAIT |
| `snmp_tcp_in_csum_errors` | number | No | Number of TCP segments received with checksum errors |
| `snmp_tcp_in_errs` | number | No | Number of TCP segments received in error |
| `snmp_tcp_in_segs` | number | No | Number of TCP segments received |
| `snmp_tcp_max_conn` | number | No | Limit on the total number of TCP connections |
| `snmp_tcp_out_rsts` | number | No | Number of TCP segments sent with RST flag |
| `snmp_tcp_out_segs` | number | No | Number of TCP segments sent |
| `snmp_tcp_passive_opens` | number | No | Number of times TCP transitions to SYN-RCVD from LISTEN |
| `snmp_tcp_retrans_segs` | number | No | Number of TCP segments retransmitted |
| `snmp_tcp_rto_max` | number | No | Maximum value permitted by a TCP implementation for the retransmission timeout (milliseconds) |
| `snmp_tcp_rto_min` | number | No | Minimum value permitted by a TCP implementation for the retransmission timeout (milliseconds) |
| `snmp_udp_in_datagrams` | number | No | Number of UDP datagrams delivered to UDP applications |
| `snmp_udp_in_errors` | number | No | Number of UDP datagrams failed to be delivered for reasons other than lack of application at the destination port |
| `snmp_udp_no_ports` | number | No | Number of UDP datagrams received for which there was not application at the destination port |
| `snmp_udp_out_datagrams` | number | No | Number of UDP datagrams sent |
| `system_boot_time_s` | number | No | Boottime of the system (seconds since the Unix epoch) |
| `t` | number | Yes | Time the Snapshot was recorded (seconds since the Unix epoch) |
| `thermals` | mconn_snapshot_thermal[] | No |  |
| `tunnels` | mconn_snapshot_tunnel[] | No |  |
| `uptime_idle_ms` | number | No | Sum of how much time each core has spent idle |
| `uptime_total_ms` | number | No | Uptime of the system, including time spent in suspend |
| `v` | string | Yes | Version |

