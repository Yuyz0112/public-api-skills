# secondary-dns Schemas

48 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [secondary-dns_account_identifier](secondary-dns-account-identifier.md) | primitive |  |
| [secondary-dns_acl](secondary-dns-acl.md) | object |  |
| [secondary-dns_acl_components-schemas-name](secondary-dns-acl-components-schemas-name.md) | primitive | The name of the acl. |
| [secondary-dns_algo](secondary-dns-algo.md) | primitive | TSIG algorithm. |
| [secondary-dns_api-response-collection](secondary-dns-api-response-collection.md) | allOf |  |
| [secondary-dns_api-response-common](secondary-dns-api-response-common.md) | object |  |
| [secondary-dns_api-response-common-failure](secondary-dns-api-response-common-failure.md) | object |  |
| [secondary-dns_api-response-single](secondary-dns-api-response-single.md) | allOf |  |
| [secondary-dns_auto_refresh_seconds](secondary-dns-auto-refresh-seconds.md) | primitive | How often should a secondary zone auto refresh reg |
| [secondary-dns_components-schemas-id_response](secondary-dns-components-schemas-id-response.md) | allOf |  |
| [secondary-dns_components-schemas-identifier](secondary-dns-components-schemas-identifier.md) | primitive |  |
| [secondary-dns_components-schemas-name](secondary-dns-components-schemas-name.md) | primitive | The name of the peer. |
| [secondary-dns_components-schemas-response_collection](secondary-dns-components-schemas-response-collection.md) | allOf |  |
| [secondary-dns_components-schemas-single_response](secondary-dns-components-schemas-single-response.md) | allOf |  |
| [secondary-dns_disable_transfer_response](secondary-dns-disable-transfer-response.md) | allOf |  |
| [secondary-dns_disable_transfer_result](secondary-dns-disable-transfer-result.md) | primitive | The zone transfer status of a primary zone. |
| [secondary-dns_dns-secondary-secondary-zone](secondary-dns-dns-secondary-secondary-zone.md) | object |  |
| [secondary-dns_enable_transfer_response](secondary-dns-enable-transfer-response.md) | allOf |  |
| [secondary-dns_enable_transfer_result](secondary-dns-enable-transfer-result.md) | primitive | The zone transfer status of a primary zone. |
| [secondary-dns_force_response](secondary-dns-force-response.md) | allOf |  |
| [secondary-dns_force_result](secondary-dns-force-result.md) | primitive | When force_axfr query parameter is set to true, th |
| [secondary-dns_id_response](secondary-dns-id-response.md) | allOf |  |
| [secondary-dns_identifier](secondary-dns-identifier.md) | primitive |  |
| [secondary-dns_ip](secondary-dns-ip.md) | primitive | IPv4/IPv6 address of primary or secondary nameserv |
| [secondary-dns_ip_range](secondary-dns-ip-range.md) | primitive | Allowed IPv4/IPv6 address range of primary or seco |
| [secondary-dns_ixfr_enable](secondary-dns-ixfr-enable.md) | primitive | Enable IXFR transfer protocol, default is AXFR. On |
| [secondary-dns_messages](secondary-dns-messages.md) | array |  |
| [secondary-dns_name](secondary-dns-name.md) | primitive | Zone name. |
| [secondary-dns_peer](secondary-dns-peer.md) | object |  |
| [secondary-dns_peers](secondary-dns-peers.md) | array | A list of peer tags. |
| [secondary-dns_port](secondary-dns-port.md) | primitive | DNS port of primary or secondary nameserver, depen |
| [secondary-dns_response_collection](secondary-dns-response-collection.md) | allOf |  |
| [secondary-dns_schemas-force_response](secondary-dns-schemas-force-response.md) | allOf |  |
| [secondary-dns_schemas-force_result](secondary-dns-schemas-force-result.md) | primitive | When force_notify query parameter is set to true,  |
| [secondary-dns_schemas-id_response](secondary-dns-schemas-id-response.md) | allOf |  |
| [secondary-dns_schemas-identifier](secondary-dns-schemas-identifier.md) | primitive |  |
| [secondary-dns_schemas-name](secondary-dns-schemas-name.md) | primitive | TSIG key name. |
| [secondary-dns_schemas-response_collection](secondary-dns-schemas-response-collection.md) | allOf |  |
| [secondary-dns_schemas-single_response](secondary-dns-schemas-single-response.md) | allOf |  |
| [secondary-dns_secret](secondary-dns-secret.md) | primitive | TSIG secret. |
| [secondary-dns_single_request_outgoing](secondary-dns-single-request-outgoing.md) | object |  |
| [secondary-dns_single_response](secondary-dns-single-response.md) | allOf |  |
| [secondary-dns_single_response_incoming](secondary-dns-single-response-incoming.md) | allOf |  |
| [secondary-dns_single_response_outgoing](secondary-dns-single-response-outgoing.md) | allOf |  |
| [secondary-dns_soa_serial](secondary-dns-soa-serial.md) | primitive | The serial number of the SOA for the given zone. |
| [secondary-dns_time](secondary-dns-time.md) | primitive | The time for a specific event. |
| [secondary-dns_tsig](secondary-dns-tsig.md) | object |  |
| [secondary-dns_tsig_id](secondary-dns-tsig-id.md) | primitive | TSIG authentication will be used for zone transfer |
