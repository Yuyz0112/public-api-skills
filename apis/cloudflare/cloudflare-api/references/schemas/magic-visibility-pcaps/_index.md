# magic-visibility-pcaps Schemas

36 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [magic-visibility-pcaps_api-response-collection](magic-visibility-pcaps-api-response-collection.md) | allOf |  |
| [magic-visibility-pcaps_api-response-common](magic-visibility-pcaps-api-response-common.md) | object |  |
| [magic-visibility-pcaps_api-response-common-failure](magic-visibility-pcaps-api-response-common-failure.md) | object |  |
| [magic-visibility-pcaps_api-response-single](magic-visibility-pcaps-api-response-single.md) | allOf |  |
| [magic-visibility-pcaps_identifier](magic-visibility-pcaps-identifier.md) | primitive | Identifier. |
| [magic-visibility-pcaps_messages](magic-visibility-pcaps-messages.md) | array |  |
| [magic-visibility-pcaps_pcaps_byte_limit](magic-visibility-pcaps-pcaps-byte-limit.md) | primitive | The maximum number of bytes to capture. This field |
| [magic-visibility-pcaps_pcaps_collection_response](magic-visibility-pcaps-pcaps-collection-response.md) | allOf |  |
| [magic-visibility-pcaps_pcaps_colo_name](magic-visibility-pcaps-pcaps-colo-name.md) | primitive | The name of the data center used for the packet ca |
| [magic-visibility-pcaps_pcaps_destination_conf](magic-visibility-pcaps-pcaps-destination-conf.md) | primitive | The full URI for the bucket. This field only appli |
| [magic-visibility-pcaps_pcaps_error_message](magic-visibility-pcaps-pcaps-error-message.md) | primitive | An error message that describes why the packet cap |
| [magic-visibility-pcaps_pcaps_filter_v1](magic-visibility-pcaps-pcaps-filter-v1.md) | object | The packet capture filter. When this field is empt |
| [magic-visibility-pcaps_pcaps_id](magic-visibility-pcaps-pcaps-id.md) | primitive | The ID for the packet capture. |
| [magic-visibility-pcaps_pcaps_offset_time](magic-visibility-pcaps-pcaps-offset-time.md) | primitive | The RFC 3339 offset timestamp from which to query  |
| [magic-visibility-pcaps_pcaps_ownership_challenge](magic-visibility-pcaps-pcaps-ownership-challenge.md) | primitive | The ownership challenge filename stored in the buc |
| [magic-visibility-pcaps_pcaps_ownership_collection](magic-visibility-pcaps-pcaps-ownership-collection.md) | allOf |  |
| [magic-visibility-pcaps_pcaps_ownership_request](magic-visibility-pcaps-pcaps-ownership-request.md) | object |  |
| [magic-visibility-pcaps_pcaps_ownership_response](magic-visibility-pcaps-pcaps-ownership-response.md) | object |  |
| [magic-visibility-pcaps_pcaps_ownership_single_response](magic-visibility-pcaps-pcaps-ownership-single-response.md) | allOf |  |
| [magic-visibility-pcaps_pcaps_ownership_validate_request](magic-visibility-pcaps-pcaps-ownership-validate-request.md) | object |  |
| [magic-visibility-pcaps_pcaps_packet_limit](magic-visibility-pcaps-pcaps-packet-limit.md) | primitive | The limit of packets contained in a packet capture |
| [magic-visibility-pcaps_pcaps_packets_captured](magic-visibility-pcaps-pcaps-packets-captured.md) | primitive | The number of packets captured. |
| [magic-visibility-pcaps_pcaps_request_full](magic-visibility-pcaps-pcaps-request-full.md) | object |  |
| [magic-visibility-pcaps_pcaps_request_pcap](magic-visibility-pcaps-pcaps-request-pcap.md) | anyOf |  |
| [magic-visibility-pcaps_pcaps_request_simple](magic-visibility-pcaps-pcaps-request-simple.md) | object |  |
| [magic-visibility-pcaps_pcaps_response_full](magic-visibility-pcaps-pcaps-response-full.md) | object |  |
| [magic-visibility-pcaps_pcaps_response_simple](magic-visibility-pcaps-pcaps-response-simple.md) | object |  |
| [magic-visibility-pcaps_pcaps_single_response](magic-visibility-pcaps-pcaps-single-response.md) | allOf |  |
| [magic-visibility-pcaps_pcaps_status](magic-visibility-pcaps-pcaps-status.md) | enum | The status of the packet capture request. |
| [magic-visibility-pcaps_pcaps_stop_requested](magic-visibility-pcaps-pcaps-stop-requested.md) | primitive | The RFC 3339 timestamp when stopping the packet ca |
| [magic-visibility-pcaps_pcaps_submitted](magic-visibility-pcaps-pcaps-submitted.md) | primitive | The RFC 3339 timestamp when the packet capture was |
| [magic-visibility-pcaps_pcaps_system](magic-visibility-pcaps-pcaps-system.md) | enum | The system used to collect packet captures. |
| [magic-visibility-pcaps_pcaps_time_limit_full](magic-visibility-pcaps-pcaps-time-limit-full.md) | primitive | The packet capture duration in seconds. |
| [magic-visibility-pcaps_pcaps_time_limit_sampled](magic-visibility-pcaps-pcaps-time-limit-sampled.md) | primitive | The packet capture duration in seconds. |
| [magic-visibility-pcaps_pcaps_type](magic-visibility-pcaps-pcaps-type.md) | enum | The type of packet capture. `Simple` captures samp |
| [magic-visibility-pcaps_result_info](magic-visibility-pcaps-result-info.md) | object |  |
