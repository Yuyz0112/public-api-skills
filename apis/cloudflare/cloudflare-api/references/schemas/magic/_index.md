# magic Schemas

163 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [magic_account_app](magic-account-app.md) | object | Custom app defined for an account. |
| [magic_account_app_id](magic-account-app-id.md) | primitive | Magic account app ID. |
| [magic_acl](magic-acl.md) | object | Bidirectional ACL policy for network traffic withi |
| [magic_acl-port-range](magic-acl-port-range.md) | primitive | A valid port range value. |
| [magic_acl-subnet](magic-acl-subnet.md) | oneOf |  |
| [magic_acl_deleted_response](magic-acl-deleted-response.md) | allOf |  |
| [magic_acl_modified_response](magic-acl-modified-response.md) | allOf |  |
| [magic_acl_single_response](magic-acl-single-response.md) | allOf |  |
| [magic_acl_update_request](magic-acl-update-request.md) | object |  |
| [magic_acls_add_single_request](magic-acls-add-single-request.md) | object | Bidirectional ACL policy for local network traffic |
| [magic_acls_collection_response](magic-acls-collection-response.md) | allOf |  |
| [magic_allow_null_cipher](magic-allow-null-cipher.md) | primitive | When `true`, the tunnel can use a null-cipher (`EN |
| [magic_api-response-common](magic-api-response-common.md) | object |  |
| [magic_api-response-common-failure](magic-api-response-common-failure.md) | object |  |
| [magic_api-response-single](magic-api-response-single.md) | allOf |  |
| [magic_app](magic-app.md) | oneOf | Collection of Hostnames and/or IP Subnets to assoc |
| [magic_app_add_single_request](magic-app-add-single-request.md) | anyOf |  |
| [magic_app_breakout](magic-app-breakout.md) | primitive | Whether to breakout traffic to the app's endpoints |
| [magic_app_breakout_preferred_wans](magic-app-breakout-preferred-wans.md) | array | WAN interfaces to prefer over default WANs, highes |
| [magic_app_config](magic-app-config.md) | allOf | Traffic decision configuration for an app. |
| [magic_app_config_add_single_request](magic-app-config-add-single-request.md) | allOf |  |
| [magic_app_config_single_response](magic-app-config-single-response.md) | allOf |  |
| [magic_app_config_update_request](magic-app-config-update-request.md) | object |  |
| [magic_app_configs_collection_response](magic-app-configs-collection-response.md) | allOf |  |
| [magic_app_hostnames](magic-app-hostnames.md) | array | FQDNs to associate with traffic decisions. |
| [magic_app_name](magic-app-name.md) | primitive | Display name for the app. |
| [magic_app_priority](magic-app-priority.md) | primitive | Priority of traffic. 0 is default, anything greate |
| [magic_app_single_response](magic-app-single-response.md) | allOf |  |
| [magic_app_subnets](magic-app-subnets.md) | array | IPv4 CIDRs to associate with traffic decisions. (I |
| [magic_app_type](magic-app-type.md) | primitive | Category of the app. |
| [magic_app_update_request](magic-app-update-request.md) | anyOf |  |
| [magic_apps-response-array](magic-apps-response-array.md) | object |  |
| [magic_apps-response-object](magic-apps-response-object.md) | object |  |
| [magic_apps_collection_response](magic-apps-collection-response.md) | allOf |  |
| [magic_automatic_return_routing](magic-automatic-return-routing.md) | primitive | True if automatic stateful return routing should b |
| [magic_bgp_config](magic-bgp-config.md) | object |  |
| [magic_bgp_status_with_state](magic-bgp-status-with-state.md) | object |  |
| [magic_cidr](magic-cidr.md) | primitive | A valid CIDR notation representing an IP range. |
| [magic_cloudflare_gre_endpoint](magic-cloudflare-gre-endpoint.md) | primitive | The IP address assigned to the Cloudflare side of  |
| [magic_cloudflare_ipsec_endpoint](magic-cloudflare-ipsec-endpoint.md) | primitive | The IP address assigned to the Cloudflare side of  |
| [magic_colo_name](magic-colo-name.md) | primitive | Scope colo name. |
| [magic_colo_names](magic-colo-names.md) | array | List of colo names for the ECMP scope. |
| [magic_colo_region](magic-colo-region.md) | primitive | Scope colo region. |
| [magic_colo_regions](magic-colo-regions.md) | array | List of colo regions for the ECMP scope. |
| [magic_components-schemas-description](magic-components-schemas-description.md) | primitive | An optional description forthe IPsec tunnel. |
| [magic_components-schemas-modified_tunnels_collection_response](magic-components-schemas-modified-tunnels-collection-response.md) | allOf |  |
| [magic_components-schemas-name](magic-components-schemas-name.md) | primitive | The name of the interconnect. The name cannot shar |
| [magic_components-schemas-tunnel_modified_response](magic-components-schemas-tunnel-modified-response.md) | allOf |  |
| [magic_components-schemas-tunnel_single_response](magic-components-schemas-tunnel-single-response.md) | allOf |  |
| [magic_components-schemas-tunnels_collection_response](magic-components-schemas-tunnels-collection-response.md) | allOf |  |
| [magic_connector-id](magic-connector-id.md) | primitive | Magic Connector identifier tag. |
| [magic_create_gre_tunnel_request](magic-create-gre-tunnel-request.md) | object |  |
| [magic_create_gre_tunnel_response](magic-create-gre-tunnel-response.md) | allOf |  |
| [magic_create_route_request](magic-create-route-request.md) | object |  |
| [magic_create_route_response](magic-create-route-response.md) | allOf |  |
| [magic_created_on](magic-created-on.md) | primitive | When the route was created. |
| [magic_custom_remote_identities](magic-custom-remote-identities.md) | object |  |
| [magic_customer_gre_endpoint](magic-customer-gre-endpoint.md) | primitive | The IP address assigned to the customer side of th |
| [magic_customer_ipsec_endpoint](magic-customer-ipsec-endpoint.md) | primitive | The IP address assigned to the customer side of th |
| [magic_description](magic-description.md) | primitive | An optional human provided description of the stat |
| [magic_forward_locally](magic-forward-locally.md) | primitive | The desired forwarding action for this ACL policy. |
| [magic_gre](magic-gre.md) | object | The configuration specific to GRE interconnects. |
| [magic_gre-tunnel](magic-gre-tunnel.md) | object |  |
| [magic_gre_tunnel_add_single_request](magic-gre-tunnel-add-single-request.md) | object |  |
| [magic_gre_tunnel_name](magic-gre-tunnel-name.md) | primitive | The name of the tunnel. The name cannot contain sp |
| [magic_gre_tunnel_update_request](magic-gre-tunnel-update-request.md) | allOf |  |
| [magic_health_check_base](magic-health-check-base.md) | object |  |
| [magic_health_check_target](magic-health-check-target.md) | object | The destination address in a request type health c |
| [magic_identifier](magic-identifier.md) | primitive | Identifier |
| [magic_interconnect](magic-interconnect.md) | object |  |
| [magic_interconnect_components-schemas-description](magic-interconnect-components-schemas-description.md) | primitive | An optional description of the interconnect. |
| [magic_interconnect_health_check](magic-interconnect-health-check.md) | object | Reference: #/components/schemas/magic_health_check |
| [magic_interconnect_tunnel_update_request](magic-interconnect-tunnel-update-request.md) | object |  |
| [magic_interface_address](magic-interface-address.md) | primitive | A 31-bit prefix (/31 in CIDR notation) supporting  |
| [magic_interface_address6](magic-interface-address6.md) | primitive | A 127 bit IPV6 prefix from within the virtual_subn |
| [magic_ip-address](magic-ip-address.md) | primitive | A valid IPv4 address. |
| [magic_ipsec-tunnel](magic-ipsec-tunnel.md) | object |  |
| [magic_ipsec_tunnel_add_request](magic-ipsec-tunnel-add-request.md) | allOf |  |
| [magic_ipsec_tunnel_add_single_request](magic-ipsec-tunnel-add-single-request.md) | object |  |
| [magic_ipsec_tunnel_name](magic-ipsec-tunnel-name.md) | primitive | The name of the IPsec tunnel. The name cannot shar |
| [magic_ipsec_tunnel_update_request](magic-ipsec-tunnel-update-request.md) | allOf |  |
| [magic_lan](magic-lan.md) | object |  |
| [magic_lan-acl-configuration](magic-lan-acl-configuration.md) | object |  |
| [magic_lan_deleted_response](magic-lan-deleted-response.md) | allOf |  |
| [magic_lan_dhcp_relay](magic-lan-dhcp-relay.md) | object |  |
| [magic_lan_dhcp_server](magic-lan-dhcp-server.md) | object |  |
| [magic_lan_modified_response](magic-lan-modified-response.md) | allOf |  |
| [magic_lan_single_response](magic-lan-single-response.md) | allOf |  |
| [magic_lan_static_addressing](magic-lan-static-addressing.md) | object | If the site is not configured in high availability |
| [magic_lan_update_request](magic-lan-update-request.md) | object |  |
| [magic_lans_add_single_request](magic-lans-add-single-request.md) | object |  |
| [magic_lans_collection_response](magic-lans-collection-response.md) | allOf |  |
| [magic_managed_app](magic-managed-app.md) | object | Managed app defined by Cloudflare. |
| [magic_managed_app_id](magic-managed-app-id.md) | primitive | Managed app ID. |
| [magic_messages](magic-messages.md) | array |  |
| [magic_modified_on](magic-modified-on.md) | primitive | When the route was last modified. |
| [magic_modified_tunnels_collection_response](magic-modified-tunnels-collection-response.md) | allOf |  |
| [magic_mtu](magic-mtu.md) | primitive | Maximum Transmission Unit (MTU) in bytes for the G |
| [magic_multiple_route_delete_response](magic-multiple-route-delete-response.md) | allOf |  |
| [magic_multiple_route_modified_response](magic-multiple-route-modified-response.md) | allOf |  |
| [magic_nat](magic-nat.md) | object |  |
| [magic_netflow_config](magic-netflow-config.md) | object | NetFlow configuration for a site. |
| [magic_netflow_config_request](magic-netflow-config-request.md) | object |  |
| [magic_netflow_config_single_response](magic-netflow-config-single-response.md) | allOf |  |
| [magic_nexthop](magic-nexthop.md) | primitive | The next-hop IP Address for the static route. |
| [magic_port](magic-port.md) | primitive |  |
| [magic_prefix](magic-prefix.md) | primitive | IP Prefix in Classless Inter-Domain Routing format |
| [magic_priority](magic-priority.md) | primitive | Priority of the static route. |
| [magic_psk](magic-psk.md) | primitive | A randomly generated or provided string for use in |
| [magic_psk_generation_response](magic-psk-generation-response.md) | allOf |  |
| [magic_psk_metadata](magic-psk-metadata.md) | object | The PSK metadata that includes when the PSK was ge |
| [magic_replay_protection](magic-replay-protection.md) | primitive | If `true`, then IPsec replay protection will be su |
| [magic_route](magic-route.md) | object |  |
| [magic_route_add_single_request](magic-route-add-single-request.md) | object |  |
| [magic_route_delete_id](magic-route-delete-id.md) | allOf |  |
| [magic_route_delete_many_request](magic-route-delete-many-request.md) | object |  |
| [magic_route_deleted_response](magic-route-deleted-response.md) | allOf |  |
| [magic_route_modified_response](magic-route-modified-response.md) | allOf |  |
| [magic_route_single_response](magic-route-single-response.md) | allOf |  |
| [magic_route_update_many_request](magic-route-update-many-request.md) | object |  |
| [magic_route_update_request](magic-route-update-request.md) | allOf |  |
| [magic_route_update_single_request](magic-route-update-single-request.md) | allOf |  |
| [magic_routed_subnet](magic-routed-subnet.md) | object |  |
| [magic_routes_collection_response](magic-routes-collection-response.md) | allOf |  |
| [magic_schemas-create_ipsec_tunnel_response](magic-schemas-create-ipsec-tunnel-response.md) | allOf |  |
| [magic_schemas-created_on](magic-schemas-created-on.md) | primitive | The date and time the tunnel was created. |
| [magic_schemas-description](magic-schemas-description.md) | primitive | An optional description of the GRE tunnel. |
| [magic_schemas-identifier](magic-schemas-identifier.md) | primitive | Identifier |
| [magic_schemas-modified_on](magic-schemas-modified-on.md) | primitive | The date and time the tunnel was last modified. |
| [magic_schemas-modified_tunnels_collection_response](magic-schemas-modified-tunnels-collection-response.md) | allOf |  |
| [magic_schemas-mtu](magic-schemas-mtu.md) | primitive | The Maximum Transmission Unit (MTU) in bytes for t |
| [magic_schemas-tunnel_deleted_response](magic-schemas-tunnel-deleted-response.md) | allOf |  |
| [magic_schemas-tunnel_modified_response](magic-schemas-tunnel-modified-response.md) | allOf |  |
| [magic_schemas-tunnel_single_response](magic-schemas-tunnel-single-response.md) | allOf |  |
| [magic_schemas-tunnels_collection_response](magic-schemas-tunnels-collection-response.md) | allOf |  |
| [magic_scope](magic-scope.md) | object | Used only for ECMP routes. |
| [magic_secondary-connector-id](magic-secondary-connector-id.md) | primitive | Magic Connector identifier tag. Used when high ava |
| [magic_site](magic-site.md) | object |  |
| [magic_site-location](magic-site-location.md) | object | Location of site in latitude and longitude. |
| [magic_site-name](magic-site-name.md) | primitive | The name of the site. |
| [magic_site_deleted_response](magic-site-deleted-response.md) | allOf |  |
| [magic_site_modified_response](magic-site-modified-response.md) | allOf |  |
| [magic_site_single_response](magic-site-single-response.md) | allOf |  |
| [magic_site_update_request](magic-site-update-request.md) | object |  |
| [magic_sites_add_single_request](magic-sites-add-single-request.md) | object |  |
| [magic_sites_collection_response](magic-sites-collection-response.md) | allOf |  |
| [magic_ttl](magic-ttl.md) | primitive | Time To Live (TTL) in number of hops of the GRE tu |
| [magic_tunnel_deleted_response](magic-tunnel-deleted-response.md) | allOf |  |
| [magic_tunnel_health_check](magic-tunnel-health-check.md) | allOf |  |
| [magic_tunnel_modified_response](magic-tunnel-modified-response.md) | allOf |  |
| [magic_tunnel_single_response](magic-tunnel-single-response.md) | allOf |  |
| [magic_tunnels_collection_response](magic-tunnels-collection-response.md) | allOf |  |
| [magic_unidirectional](magic-unidirectional.md) | primitive | The desired traffic direction for this ACL policy. |
| [magic_vlan_tag](magic-vlan-tag.md) | primitive | VLAN ID. Use zero for untagged. |
| [magic_wan](magic-wan.md) | object |  |
| [magic_wan_deleted_response](magic-wan-deleted-response.md) | allOf |  |
| [magic_wan_modified_response](magic-wan-modified-response.md) | allOf |  |
| [magic_wan_single_response](magic-wan-single-response.md) | allOf |  |
| [magic_wan_static_addressing](magic-wan-static-addressing.md) | object | (optional) if omitted, use DHCP. Submit secondary_ |
| [magic_wan_update_request](magic-wan-update-request.md) | object |  |
| [magic_wans_add_single_request](magic-wans-add-single-request.md) | object |  |
| [magic_wans_collection_response](magic-wans-collection-response.md) | allOf |  |
| [magic_weight](magic-weight.md) | primitive | Optional weight of the ECMP scope - if provided. |
