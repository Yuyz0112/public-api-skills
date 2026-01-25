# tunnel Schemas

112 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [tunnel_account_id](tunnel-account-id.md) | primitive | Cloudflare account ID |
| [tunnel_address_family](tunnel-address-family.md) | enum | IP address family, either `v4` (IPv4) or `v6` (IPv |
| [tunnel_api-response-collection](tunnel-api-response-collection.md) | allOf |  |
| [tunnel_api-response-common](tunnel-api-response-common.md) | object |  |
| [tunnel_api-response-common-failure](tunnel-api-response-common-failure.md) | object |  |
| [tunnel_api-response-single](tunnel-api-response-single.md) | object | Reference: #/components/schemas/tunnel_api-respons |
| [tunnel_arch](tunnel-arch.md) | primitive | The cloudflared OS architecture used to establish  |
| [tunnel_argo-tunnel](tunnel-argo-tunnel.md) | object |  |
| [tunnel_cfd-tunnel-response-collection](tunnel-cfd-tunnel-response-collection.md) | allOf |  |
| [tunnel_cfd-tunnel-response-single](tunnel-cfd-tunnel-response-single.md) | allOf |  |
| [tunnel_cfd_tunnel](tunnel-cfd-tunnel.md) | object | A Cloudflare Tunnel that connects your origin to C |
| [tunnel_client_id](tunnel-client-id.md) | primitive | UUID of the Cloudflare Tunnel connector. |
| [tunnel_colo_name](tunnel-colo-name.md) | primitive | The Cloudflare data center used for this connectio |
| [tunnel_components-schemas-tunnel_id](tunnel-components-schemas-tunnel-id.md) | primitive | UUID of the tunnel. |
| [tunnel_config](tunnel-config.md) | object | The tunnel configuration and ingress rules. |
| [tunnel_config_src](tunnel-config-src.md) | enum | Indicates if this is a locally or remotely configu |
| [tunnel_config_version](tunnel-config-version.md) | primitive | The version of the remote tunnel configuration. Us |
| [tunnel_configuration](tunnel-configuration.md) | object | Cloudflare Tunnel configuration |
| [tunnel_configuration_response](tunnel-configuration-response.md) | allOf |  |
| [tunnel_connection](tunnel-connection.md) | object |  |
| [tunnel_connection_id](tunnel-connection-id.md) | primitive | UUID of the Cloudflare Tunnel connection. |
| [tunnel_connections](tunnel-connections.md) | array | The Cloudflare Tunnel connections between your ori |
| [tunnel_connections_deprecated](tunnel-connections-deprecated.md) | array | The Cloudflare Tunnel connections between your ori |
| [tunnel_conns_active_at](tunnel-conns-active-at.md) | primitive | Timestamp of when the tunnel established at least  |
| [tunnel_conns_inactive_at](tunnel-conns-inactive-at.md) | primitive | Timestamp of when the tunnel became inactive (no c |
| [tunnel_created_at](tunnel-created-at.md) | primitive | Timestamp of when the resource was created. |
| [tunnel_deleted_at](tunnel-deleted-at.md) | primitive | Timestamp of when the resource was deleted. If `nu |
| [tunnel_empty_response](tunnel-empty-response.md) | allOf |  |
| [tunnel_existed_at](tunnel-existed-at.md) | primitive | If provided, include only resources that were crea |
| [tunnel_features](tunnel-features.md) | array | Features enabled for the Cloudflare Tunnel. |
| [tunnel_hostname](tunnel-hostname.md) | primitive | The hostname of the route. |
| [tunnel_hostname_comment](tunnel-hostname-comment.md) | primitive | An optional description of the hostname route. |
| [tunnel_hostname_query_comment](tunnel-hostname-query-comment.md) | primitive | If set, only list hostname routes with the given c |
| [tunnel_hostname_route](tunnel-hostname-route.md) | object |  |
| [tunnel_hostname_route_id](tunnel-hostname-route-id.md) | primitive | The hostname route ID. |
| [tunnel_hostname_route_response_collection](tunnel-hostname-route-response-collection.md) | allOf |  |
| [tunnel_hostname_route_response_single](tunnel-hostname-route-response-single.md) | allOf |  |
| [tunnel_icmp_proxy_enabled](tunnel-icmp-proxy-enabled.md) | primitive | A flag to enable the ICMP proxy for the account ne |
| [tunnel_identifier](tunnel-identifier.md) | primitive | Identifier. |
| [tunnel_ingressRule](tunnel-ingressRule.md) | object | Public hostname |
| [tunnel_ip](tunnel-ip.md) | primitive |  |
| [tunnel_ip_network](tunnel-ip-network.md) | primitive | The private IPv4 or IPv6 range connected by the ro |
| [tunnel_ip_network_encoded](tunnel-ip-network-encoded.md) | primitive | IP/CIDR range in URL-encoded format |
| [tunnel_is_default_network](tunnel-is-default-network.md) | primitive | If `true`, this virtual network is the default for |
| [tunnel_is_default_network_optional](tunnel-is-default-network-optional.md) | primitive | If `true`, this virtual network is the default for |
| [tunnel_is_pending_reconnect](tunnel-is-pending-reconnect.md) | primitive | Cloudflare continues to track connections for seve |
| [tunnel_legacy-tunnel-response-collection](tunnel-legacy-tunnel-response-collection.md) | allOf |  |
| [tunnel_legacy-tunnel-response-single](tunnel-legacy-tunnel-response-single.md) | allOf |  |
| [tunnel_management-resources](tunnel-management-resources.md) | enum | Management resources the token will have access to |
| [tunnel_messages](tunnel-messages.md) | array |  |
| [tunnel_metadata](tunnel-metadata.md) | object | Metadata associated with the tunnel. |
| [tunnel_offramp_warp_enabled](tunnel-offramp-warp-enabled.md) | primitive | A flag to enable WARP to WARP traffic. |
| [tunnel_originRequest](tunnel-originRequest.md) | object | Configuration parameters for the public hostname s |
| [tunnel_page_number](tunnel-page-number.md) | primitive | Page number of paginated results. |
| [tunnel_per_page](tunnel-per-page.md) | primitive | Number of results to display. |
| [tunnel_remote_config](tunnel-remote-config.md) | primitive | If `true`, the tunnel can be configured remotely f |
| [tunnel_result_info](tunnel-result-info.md) | object |  |
| [tunnel_route](tunnel-route.md) | object |  |
| [tunnel_route_comment](tunnel-route-comment.md) | primitive | Optional remark describing the route. |
| [tunnel_route_id](tunnel-route-id.md) | primitive | UUID of the route. |
| [tunnel_route_response_single](tunnel-route-response-single.md) | allOf |  |
| [tunnel_run_at](tunnel-run-at.md) | primitive | Timestamp of when the tunnel connection was starte |
| [tunnel_schemas-api-response-common](tunnel-schemas-api-response-common.md) | object |  |
| [tunnel_schemas-api-response-common-failure](tunnel-schemas-api-response-common-failure.md) | object |  |
| [tunnel_schemas-api-response-single](tunnel-schemas-api-response-single.md) | allOf |  |
| [tunnel_schemas-config_src](tunnel-schemas-config-src.md) | enum | Indicates if this is a locally or remotely configu |
| [tunnel_schemas-config_version](tunnel-schemas-config-version.md) | primitive | The version of the Tunnel Configuration. |
| [tunnel_schemas-connection](tunnel-schemas-connection.md) | object |  |
| [tunnel_schemas-messages](tunnel-schemas-messages.md) | array |  |
| [tunnel_schemas-tunnel_id](tunnel-schemas-tunnel-id.md) | primitive | UUID of the tunnel. |
| [tunnel_schemas-tunnel_name](tunnel-schemas-tunnel-name.md) | primitive | A user-friendly name for a tunnel. |
| [tunnel_status](tunnel-status.md) | enum | The status of the tunnel. Valid values are `inacti |
| [tunnel_subnet](tunnel-subnet.md) | object |  |
| [tunnel_subnet_comment](tunnel-subnet-comment.md) | primitive | An optional description of the subnet. |
| [tunnel_subnet_id](tunnel-subnet-id.md) | primitive | The UUID of the subnet. |
| [tunnel_subnet_ip_network](tunnel-subnet-ip-network.md) | primitive | The private IPv4 or IPv6 range defining the subnet |
| [tunnel_subnet_is_default_network](tunnel-subnet-is-default-network.md) | primitive | If `true`, this is the default subnet for the acco |
| [tunnel_subnet_name](tunnel-subnet-name.md) | primitive | A user-friendly name for the subnet. |
| [tunnel_subnet_query_comment](tunnel-subnet-query-comment.md) | primitive | If set, only list subnets with the given comment. |
| [tunnel_subnet_query_name](tunnel-subnet-query-name.md) | primitive | If set, only list subnets with the given name |
| [tunnel_subnet_response_collection](tunnel-subnet-response-collection.md) | allOf |  |
| [tunnel_subnet_response_single](tunnel-subnet-response-single.md) | allOf |  |
| [tunnel_subnet_type](tunnel-subnet-type.md) | enum | The type of subnet. |
| [tunnel_teamnet](tunnel-teamnet.md) | object |  |
| [tunnel_teamnet_response_collection](tunnel-teamnet-response-collection.md) | allOf |  |
| [tunnel_teamnet_response_single](tunnel-teamnet-response-single.md) | allOf |  |
| [tunnel_timestamp](tunnel-timestamp.md) | primitive |  |
| [tunnel_tunnel-response-collection](tunnel-tunnel-response-collection.md) | allOf |  |
| [tunnel_tunnel_client](tunnel-tunnel-client.md) | object | A client (typically cloudflared) that maintains co |
| [tunnel_tunnel_client_response](tunnel-tunnel-client-response.md) | allOf |  |
| [tunnel_tunnel_connections_response](tunnel-tunnel-connections-response.md) | allOf |  |
| [tunnel_tunnel_id](tunnel-tunnel-id.md) | primitive | UUID of the tunnel. |
| [tunnel_tunnel_link](tunnel-tunnel-link.md) | object | The id of the tunnel linked and the date that link |
| [tunnel_tunnel_links_response](tunnel-tunnel-links-response.md) | allOf |  |
| [tunnel_tunnel_name](tunnel-tunnel-name.md) | primitive | A user-friendly name for a tunnel. |
| [tunnel_tunnel_response_token](tunnel-tunnel-response-token.md) | allOf |  |
| [tunnel_tunnel_secret](tunnel-tunnel-secret.md) | primitive | Sets the password required to run a locally-manage |
| [tunnel_tunnel_token](tunnel-tunnel-token.md) | primitive | The Tunnel Token is used as a mechanism to authent |
| [tunnel_tunnel_type](tunnel-tunnel-type.md) | enum | The type of tunnel. |
| [tunnel_tunnel_types](tunnel-tunnel-types.md) | array | The types of tunnels to filter by, separated by co |
| [tunnel_version](tunnel-version.md) | primitive | The cloudflared version used to establish this con |
| [tunnel_virtual-network](tunnel-virtual-network.md) | object |  |
| [tunnel_virtual_network_comment](tunnel-virtual-network-comment.md) | primitive | Optional remark describing the virtual network. |
| [tunnel_virtual_network_id](tunnel-virtual-network-id.md) | primitive | UUID of the virtual network. |
| [tunnel_virtual_network_id_computed_optional](tunnel-virtual-network-id-computed-optional.md) | primitive | UUID of the virtual network. |
| [tunnel_virtual_network_name](tunnel-virtual-network-name.md) | primitive | A user-friendly name for the virtual network. |
| [tunnel_vnet_response_collection](tunnel-vnet-response-collection.md) | allOf |  |
| [tunnel_vnet_response_single](tunnel-vnet-response-single.md) | allOf |  |
| [tunnel_warp-connector-response-collection](tunnel-warp-connector-response-collection.md) | allOf |  |
| [tunnel_warp-connector-response-single](tunnel-warp-connector-response-single.md) | allOf |  |
| [tunnel_warp_connector_tunnel](tunnel-warp-connector-tunnel.md) | object | A Warp Connector Tunnel that connects your origin  |
| [tunnel_zero_trust_connectivity_settings_response](tunnel-zero-trust-connectivity-settings-response.md) | allOf |  |
