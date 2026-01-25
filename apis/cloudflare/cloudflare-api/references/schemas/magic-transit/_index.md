# magic-transit Schemas

42 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [magic-transit_api-response-common](magic-transit-api-response-common.md) | object |  |
| [magic-transit_api-response-common-failure](magic-transit-api-response-common-failure.md) | object |  |
| [magic-transit_asn](magic-transit-asn.md) | primitive | AS number associated with the node object. |
| [magic-transit_check_type](magic-transit-check-type.md) | enum | type of check to perform |
| [magic-transit_colo](magic-transit-colo.md) | object |  |
| [magic-transit_colo_city](magic-transit-colo-city.md) | primitive | Source colo city. |
| [magic-transit_colo_name](magic-transit-colo-name.md) | primitive | Source colo name. |
| [magic-transit_colo_result](magic-transit-colo-result.md) | object |  |
| [magic-transit_colos](magic-transit-colos.md) | array | If no source colo names specified, all colos will  |
| [magic-transit_endpoint_health_check](magic-transit-endpoint-health-check.md) | object |  |
| [magic-transit_endpoint_health_check_response](magic-transit-endpoint-health-check-response.md) | allOf |  |
| [magic-transit_endpoint_health_check_response_collection](magic-transit-endpoint-health-check-response-collection.md) | allOf |  |
| [magic-transit_endpoint_health_check_response_single](magic-transit-endpoint-health-check-response-single.md) | allOf |  |
| [magic-transit_error](magic-transit-error.md) | enum | Errors resulting from collecting traceroute from c |
| [magic-transit_hop_result](magic-transit-hop-result.md) | object |  |
| [magic-transit_identifier](magic-transit-identifier.md) | primitive | Identifier |
| [magic-transit_ip](magic-transit-ip.md) | primitive | IP address of the node. |
| [magic-transit_labels](magic-transit-labels.md) | array | Field appears if there is an additional annotation |
| [magic-transit_max_rtt_ms](magic-transit-max-rtt-ms.md) | primitive | Maximum RTT in ms. |
| [magic-transit_max_ttl](magic-transit-max-ttl.md) | primitive | Max TTL. |
| [magic-transit_mean_rtt_ms](magic-transit-mean-rtt-ms.md) | primitive | Mean RTT in ms. |
| [magic-transit_messages](magic-transit-messages.md) | array |  |
| [magic-transit_min_rtt_ms](magic-transit-min-rtt-ms.md) | primitive | Minimum RTT in ms. |
| [magic-transit_name](magic-transit-name.md) | primitive | Host name of the address, this may be the same as  |
| [magic-transit_node_result](magic-transit-node-result.md) | object |  |
| [magic-transit_options](magic-transit-options.md) | object |  |
| [magic-transit_packet_count](magic-transit-packet-count.md) | primitive | Number of packets with a response from this node. |
| [magic-transit_packet_type](magic-transit-packet-type.md) | enum | Type of packet sent. |
| [magic-transit_packets_lost](magic-transit-packets-lost.md) | primitive | Number of packets where no response was received. |
| [magic-transit_packets_per_ttl](magic-transit-packets-per-ttl.md) | primitive | Number of packets sent at each TTL. |
| [magic-transit_packets_sent](magic-transit-packets-sent.md) | primitive | Number of packets sent with specified TTL. |
| [magic-transit_packets_ttl](magic-transit-packets-ttl.md) | primitive | The time to live (TTL). |
| [magic-transit_port](magic-transit-port.md) | primitive | For UDP and TCP, specifies the destination port. F |
| [magic-transit_std_dev_rtt_ms](magic-transit-std-dev-rtt-ms.md) | primitive | Standard deviation of the RTTs in ms. |
| [magic-transit_target](magic-transit-target.md) | primitive | The target hostname, IPv6, or IPv6 address. |
| [magic-transit_target_result](magic-transit-target-result.md) | object |  |
| [magic-transit_target_summary](magic-transit-target-summary.md) | object | Aggregated statistics from all hops about the targ |
| [magic-transit_targets](magic-transit-targets.md) | array |  |
| [magic-transit_traceroute_response_collection](magic-transit-traceroute-response-collection.md) | allOf |  |
| [magic-transit_traceroute_time_ms](magic-transit-traceroute-time-ms.md) | primitive | Total time of traceroute in ms. |
| [magic-transit_uuid](magic-transit-uuid.md) | primitive | UUID. |
| [magic-transit_wait_time](magic-transit-wait-time.md) | primitive | Set the time (in seconds) to wait for a response t |
