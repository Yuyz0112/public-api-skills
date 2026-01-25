# addressing Schemas

90 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [addressing_account_identifier](addressing-account-identifier.md) | primitive | Identifier of a Cloudflare account. |
| [addressing_address-maps](addressing-address-maps.md) | object |  |
| [addressing_address-maps-ip](addressing-address-maps-ip.md) | object |  |
| [addressing_address-maps-membership](addressing-address-maps-membership.md) | object |  |
| [addressing_address-maps-membership-request](addressing-address-maps-membership-request.md) | object |  |
| [addressing_address_map_identifier](addressing-address-map-identifier.md) | primitive | Identifier of an Address Map. |
| [addressing_advertised](addressing-advertised.md) | primitive | Prefix advertisement status to the Internet. This  |
| [addressing_advertised_modified_at_nullable](addressing-advertised-modified-at-nullable.md) | primitive | Last time the advertisement status was changed. Th |
| [addressing_advertised_response](addressing-advertised-response.md) | allOf |  |
| [addressing_api-response-collection](addressing-api-response-collection.md) | allOf |  |
| [addressing_api-response-common](addressing-api-response-common.md) | object |  |
| [addressing_api-response-common-failure](addressing-api-response-common-failure.md) | object |  |
| [addressing_api-response-single](addressing-api-response-single.md) | allOf |  |
| [addressing_approved](addressing-approved.md) | primitive | Approval state of the prefix (P = pending, V = act |
| [addressing_asn](addressing-asn.md) | primitive | Autonomous System Number (ASN) the prefix will be  |
| [addressing_asn_prepend_count](addressing-asn-prepend-count.md) | primitive | Number of times to prepend the Cloudflare ASN to t |
| [addressing_auto_advertise_withdraw](addressing-auto-advertise-withdraw.md) | primitive | Determines if Cloudflare advertises a BYOIP BGP pr |
| [addressing_auto_generated](addressing-auto-generated.md) | primitive | Whether the LOA has been auto-generated for the pr |
| [addressing_bgp_on_demand](addressing-bgp-on-demand.md) | object |  |
| [addressing_bgp_prefix_create](addressing-bgp-prefix-create.md) | object |  |
| [addressing_bgp_prefix_identifier](addressing-bgp-prefix-identifier.md) | primitive | Identifier of BGP Prefix. |
| [addressing_bgp_prefix_update_advertisement](addressing-bgp-prefix-update-advertisement.md) | object |  |
| [addressing_bgp_signal_opts](addressing-bgp-signal-opts.md) | object |  |
| [addressing_bgp_signaling_enabled](addressing-bgp-signaling-enabled.md) | primitive | Whether control of advertisement of the prefix to  |
| [addressing_bgp_signaling_modified_at](addressing-bgp-signaling-modified-at.md) | primitive | Last time BGP signaling control was toggled. This  |
| [addressing_can_delete](addressing-can-delete.md) | primitive | If set to false, then the Address Map cannot be de |
| [addressing_can_modify_ips](addressing-can-modify-ips.md) | primitive | If set to false, then the IPs on the Address Map c |
| [addressing_cidr](addressing-cidr.md) | primitive | IP Prefix in Classless Inter-Domain Routing format |
| [addressing_components-schemas-advertised](addressing-components-schemas-advertised.md) | primitive | Advertisement status of the prefix. If `true`, the |
| [addressing_components-schemas-response_collection](addressing-components-schemas-response-collection.md) | allOf |  |
| [addressing_components-schemas-single_response](addressing-components-schemas-single-response.md) | allOf |  |
| [addressing_create_binding_request](addressing-create-binding-request.md) | object |  |
| [addressing_created_at](addressing-created-at.md) | primitive | Timestamp of the moment the object was created. |
| [addressing_default_sni](addressing-default-sni.md) | primitive | If you have legacy TLS clients which do not send t |
| [addressing_delegate_loa_creation](addressing-delegate-loa-creation.md) | primitive | Whether Cloudflare is allowed to generate the LOA  |
| [addressing_delegated_account_identifier](addressing-delegated-account-identifier.md) | primitive | Account identifier for the account to which prefix |
| [addressing_delegation_identifier](addressing-delegation-identifier.md) | primitive | Identifier of a Delegation. |
| [addressing_description](addressing-description.md) | primitive | Description of the prefix. |
| [addressing_enabled](addressing-enabled.md) | primitive | Whether the Address Map is enabled or not. Cloudfl |
| [addressing_filename](addressing-filename.md) | primitive | Name of LOA document. Max file size 10MB, and supp |
| [addressing_full_response](addressing-full-response.md) | allOf |  |
| [addressing_id_response](addressing-id-response.md) | allOf |  |
| [addressing_identifier](addressing-identifier.md) | primitive | The identifier for the membership (eg. a zone or a |
| [addressing_ip](addressing-ip.md) | primitive | An IPv4 or IPv6 address. |
| [addressing_ip_address](addressing-ip-address.md) | primitive | An IPv4 or IPv6 address. |
| [addressing_ipam-bgp-prefixes](addressing-ipam-bgp-prefixes.md) | object |  |
| [addressing_ipam-delegations](addressing-ipam-delegations.md) | object |  |
| [addressing_ipam-prefixes](addressing-ipam-prefixes.md) | object |  |
| [addressing_ips](addressing-ips.md) | array | The set of IPs on the Address Map. |
| [addressing_kind](addressing-kind.md) | enum | The type of the membership. |
| [addressing_lease](addressing-lease.md) | object |  |
| [addressing_lease_id](addressing-lease-id.md) | primitive | Identifier for the lease |
| [addressing_lease_owner_id](addressing-lease-owner-id.md) | primitive | Cloudflare account ID of the account owning the le |
| [addressing_leases_components-schemas-response_collection](addressing-leases-components-schemas-response-collection.md) | allOf |  |
| [addressing_loa_document_identifier](addressing-loa-document-identifier.md) | primitive | Identifier for the uploaded LOA document. |
| [addressing_loa_upload_response](addressing-loa-upload-response.md) | allOf |  |
| [addressing_membership_requests](addressing-membership-requests.md) | array | Zones and Accounts which will be assigned IPs on t |
| [addressing_memberships](addressing-memberships.md) | array | Zones and Accounts which will be assigned IPs on t |
| [addressing_messages](addressing-messages.md) | array |  |
| [addressing_modified_at](addressing-modified-at.md) | primitive | Timestamp of the moment the object was modified. |
| [addressing_modified_at_nullable](addressing-modified-at-nullable.md) | primitive | Last time the advertisement status was changed. Th |
| [addressing_on_demand_enabled](addressing-on-demand-enabled.md) | primitive | Whether advertisement of the prefix to the Interne |
| [addressing_on_demand_locked](addressing-on-demand-locked.md) | primitive | Whether advertisement status of the prefix is lock |
| [addressing_ownership_validation_token](addressing-ownership-validation-token.md) | primitive | Token provided to demonstrate ownership of the pre |
| [addressing_prefix_identifier](addressing-prefix-identifier.md) | primitive | Identifier of an IP Prefix. |
| [addressing_provisioning](addressing-provisioning.md) | object | Status of a Service Binding's deployment to the Cl |
| [addressing_response_collection](addressing-response-collection.md) | allOf |  |
| [addressing_response_collection_bgp](addressing-response-collection-bgp.md) | allOf |  |
| [addressing_schemas-account_identifier](addressing-schemas-account-identifier.md) | primitive | Identifier of a Cloudflare account. |
| [addressing_schemas-advertised](addressing-schemas-advertised.md) | primitive | Prefix advertisement status to the Internet. This  |
| [addressing_schemas-asn](addressing-schemas-asn.md) | primitive | Autonomous System Number (ASN) the prefix will be  |
| [addressing_schemas-can_delete](addressing-schemas-can-delete.md) | primitive | Controls whether the membership can be deleted via |
| [addressing_schemas-cidr](addressing-schemas-cidr.md) | primitive | IP Prefix in Classless Inter-Domain Routing format |
| [addressing_schemas-description](addressing-schemas-description.md) | primitive | An optional description field which may be used to |
| [addressing_schemas-on_demand_enabled](addressing-schemas-on-demand-enabled.md) | primitive | Whether advertisement of the prefix to the Interne |
| [addressing_schemas-on_demand_locked](addressing-schemas-on-demand-locked.md) | primitive | Whether the advertisement status of the prefix is  |
| [addressing_schemas-response_collection](addressing-schemas-response-collection.md) | allOf |  |
| [addressing_schemas-single_response](addressing-schemas-single-response.md) | allOf |  |
| [addressing_service_binding](addressing-service-binding.md) | object |  |
| [addressing_service_binding_identifier](addressing-service-binding-identifier.md) | primitive | Identifier of a Service Binding. |
| [addressing_service_identifier](addressing-service-identifier.md) | primitive | Identifier of a Service on the Cloudflare network. |
| [addressing_service_name](addressing-service-name.md) | primitive | Name of a service running on the Cloudflare networ |
| [addressing_single_response](addressing-single-response.md) | allOf |  |
| [addressing_single_response_bgp](addressing-single-response-bgp.md) | allOf |  |
| [addressing_size_bytes](addressing-size-bytes.md) | primitive | File size of the uploaded LOA document. |
| [addressing_timestamp](addressing-timestamp.md) | primitive |  |
| [addressing_validation_state](addressing-validation-state.md) | primitive | State of one kind of validation for an IP prefix. |
| [addressing_verified](addressing-verified.md) | primitive | Whether the LOA has been verified by Cloudflare st |
| [addressing_verified_at](addressing-verified-at.md) | primitive | Timestamp of the moment the LOA was marked as vali |
| [addressing_zone_identifier](addressing-zone-identifier.md) | primitive | Identifier of a zone. |
