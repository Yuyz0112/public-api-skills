# zero-trust-gateway Schemas

148 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [zero-trust-gateway_account-log-options](zero-trust-gateway-account-log-options.md) | object |  |
| [zero-trust-gateway_action](zero-trust-gateway-action.md) | enum | Specify the action to perform when the associated  |
| [zero-trust-gateway_activity-log-settings](zero-trust-gateway-activity-log-settings.md) | object | Specify activity log settings. |
| [zero-trust-gateway_anti-virus-settings](zero-trust-gateway-anti-virus-settings.md) | object | Specify anti-virus settings. |
| [zero-trust-gateway_api-response-collection](zero-trust-gateway-api-response-collection.md) | allOf |  |
| [zero-trust-gateway_api-response-common](zero-trust-gateway-api-response-common.md) | object |  |
| [zero-trust-gateway_api-response-common-failure](zero-trust-gateway-api-response-common-failure.md) | object |  |
| [zero-trust-gateway_api-response-single](zero-trust-gateway-api-response-single.md) | allOf |  |
| [zero-trust-gateway_app-types](zero-trust-gateway-app-types.md) | oneOf |  |
| [zero-trust-gateway_app-types_components-schemas-name](zero-trust-gateway-app-types-components-schemas-name.md) | primitive | Specify the name of the application or application |
| [zero-trust-gateway_app-types_components-schemas-response_collection](zero-trust-gateway-app-types-components-schemas-response-collection.md) | allOf |  |
| [zero-trust-gateway_app_id](zero-trust-gateway-app-id.md) | primitive | Identify this application. Only one application pe |
| [zero-trust-gateway_app_type_id](zero-trust-gateway-app-type-id.md) | primitive | Identify the type of this application. Multiple ap |
| [zero-trust-gateway_application](zero-trust-gateway-application.md) | object |  |
| [zero-trust-gateway_application_type](zero-trust-gateway-application-type.md) | object |  |
| [zero-trust-gateway_applications_review_status_response](zero-trust-gateway-applications-review-status-response.md) | allOf |  |
| [zero-trust-gateway_applications_review_status_response_content](zero-trust-gateway-applications-review-status-response-content.md) | object |  |
| [zero-trust-gateway_approved_apps](zero-trust-gateway-approved-apps.md) | array | Contains the ids of the approved applications. |
| [zero-trust-gateway_audit_ssh_settings_components-schemas-single_response](zero-trust-gateway-audit-ssh-settings-components-schemas-single-response.md) | allOf |  |
| [zero-trust-gateway_audit_ssh_settings_components-schemas-uuid](zero-trust-gateway-audit-ssh-settings-components-schemas-uuid.md) | primitive | Identify the seed ID. |
| [zero-trust-gateway_beta](zero-trust-gateway-beta.md) | primitive | Indicate whether the category is in beta and subje |
| [zero-trust-gateway_binding_status](zero-trust-gateway-binding-status.md) | enum | Indicate the read-only deployment status of the ce |
| [zero-trust-gateway_block-page-settings](zero-trust-gateway-block-page-settings.md) | object | Specify block page layout settings. |
| [zero-trust-gateway_body-scanning-settings](zero-trust-gateway-body-scanning-settings.md) | object | Specify the DLP inspection mode. |
| [zero-trust-gateway_browser-isolation-settings](zero-trust-gateway-browser-isolation-settings.md) | object | Specify Clientless Browser Isolation settings. |
| [zero-trust-gateway_categories](zero-trust-gateway-categories.md) | object |  |
| [zero-trust-gateway_categories_components-schemas-name](zero-trust-gateway-categories-components-schemas-name.md) | primitive | Specify the category name. |
| [zero-trust-gateway_categories_components-schemas-response_collection](zero-trust-gateway-categories-components-schemas-response-collection.md) | allOf |  |
| [zero-trust-gateway_certificate-settings](zero-trust-gateway-certificate-settings.md) | object | Specify certificate settings for Gateway TLS inter |
| [zero-trust-gateway_certificates](zero-trust-gateway-certificates.md) | object |  |
| [zero-trust-gateway_cf_account_id](zero-trust-gateway-cf-account-id.md) | primitive | Specify the Cloudflare account ID. |
| [zero-trust-gateway_class](zero-trust-gateway-class.md) | enum | Specify which account types can create policies fo |
| [zero-trust-gateway_client-default](zero-trust-gateway-client-default.md) | primitive | Indicate whether this location is the default loca |
| [zero-trust-gateway_components-schemas-description](zero-trust-gateway-components-schemas-description.md) | primitive | Provide a short summary of domains in the category |
| [zero-trust-gateway_components-schemas-identifier](zero-trust-gateway-components-schemas-identifier.md) | primitive | Provide the identifier string. |
| [zero-trust-gateway_components-schemas-name](zero-trust-gateway-components-schemas-name.md) | primitive | Specify the rule name. |
| [zero-trust-gateway_components-schemas-response_collection](zero-trust-gateway-components-schemas-response-collection.md) | allOf |  |
| [zero-trust-gateway_components-schemas-single_response](zero-trust-gateway-components-schemas-single-response.md) | allOf |  |
| [zero-trust-gateway_components-schemas-uuid](zero-trust-gateway-components-schemas-uuid.md) | primitive |  |
| [zero-trust-gateway_contents](zero-trust-gateway-contents.md) | primitive | Actual contents of the PAC file |
| [zero-trust-gateway_count](zero-trust-gateway-count.md) | primitive | Indicate the number of items in the list. |
| [zero-trust-gateway_custom-certificate-settings](zero-trust-gateway-custom-certificate-settings.md) | object | Specify custom certificate settings for BYO-PKI. T |
| [zero-trust-gateway_deleted_at](zero-trust-gateway-deleted-at.md) | primitive | Indicate the date of deletion, if any. |
| [zero-trust-gateway_description](zero-trust-gateway-description.md) | primitive | Provide the list description. |
| [zero-trust-gateway_description_item](zero-trust-gateway-description-item.md) | primitive | Provide the list item description (optional). |
| [zero-trust-gateway_device_posture](zero-trust-gateway-device-posture.md) | primitive | Specify the wirefilter expression used for device  |
| [zero-trust-gateway_dns-destination-ips-id-read](zero-trust-gateway-dns-destination-ips-id-read.md) | primitive | Indicate the identifier of the pair of IPv4 addres |
| [zero-trust-gateway_dns-destination-ips-id-write](zero-trust-gateway-dns-destination-ips-id-write.md) | primitive | Specify the identifier of the pair of IPv4 address |
| [zero-trust-gateway_dns_destination_ipv6_block_id](zero-trust-gateway-dns-destination-ipv6-block-id.md) | primitive | Specify the UUID of the IPv6 block brought to the  |
| [zero-trust-gateway_dns_resolver_settings_v4](zero-trust-gateway-dns-resolver-settings-v4.md) | object |  |
| [zero-trust-gateway_dns_resolver_settings_v6](zero-trust-gateway-dns-resolver-settings-v6.md) | object |  |
| [zero-trust-gateway_doh_endpoint](zero-trust-gateway-doh-endpoint.md) | object |  |
| [zero-trust-gateway_dot_endpoint](zero-trust-gateway-dot-endpoint.md) | object |  |
| [zero-trust-gateway_ecs-support](zero-trust-gateway-ecs-support.md) | primitive | Indicate whether the location must resolve EDNS qu |
| [zero-trust-gateway_empty_response](zero-trust-gateway-empty-response.md) | allOf |  |
| [zero-trust-gateway_enabled](zero-trust-gateway-enabled.md) | primitive | Specify whether the rule is enabled. |
| [zero-trust-gateway_enabled_download_phase](zero-trust-gateway-enabled-download-phase.md) | primitive | Specify whether to enable anti-virus scanning on d |
| [zero-trust-gateway_enabled_upload_phase](zero-trust-gateway-enabled-upload-phase.md) | primitive | Specify whether to enable anti-virus scanning on u |
| [zero-trust-gateway_endpoints](zero-trust-gateway-endpoints.md) | object | Configure the destination endpoints for this locat |
| [zero-trust-gateway_expiration](zero-trust-gateway-expiration.md) | object | Defines the expiration time stamp and default dura |
| [zero-trust-gateway_extended-email-matching](zero-trust-gateway-extended-email-matching.md) | object | Configures user email settings for firewall polici |
| [zero-trust-gateway_fail_closed](zero-trust-gateway-fail-closed.md) | primitive | Specify whether to block requests for unscannable  |
| [zero-trust-gateway_filters](zero-trust-gateway-filters.md) | array | Specify the protocol or layer to evaluate the traf |
| [zero-trust-gateway_fips-settings](zero-trust-gateway-fips-settings.md) | object | Specify FIPS settings. |
| [zero-trust-gateway_gateway-account-logging-settings](zero-trust-gateway-gateway-account-logging-settings.md) | object |  |
| [zero-trust-gateway_gateway-account-logging-settings-response](zero-trust-gateway-gateway-account-logging-settings-response.md) | allOf |  |
| [zero-trust-gateway_gateway-account-settings](zero-trust-gateway-gateway-account-settings.md) | object | Specify account settings. |
| [zero-trust-gateway_gateway_account](zero-trust-gateway-gateway-account.md) | allOf |  |
| [zero-trust-gateway_gateway_account_config](zero-trust-gateway-gateway-account-config.md) | allOf |  |
| [zero-trust-gateway_gateway_tag](zero-trust-gateway-gateway-tag.md) | primitive | Specify the gateway internal ID. |
| [zero-trust-gateway_generate-cert-request](zero-trust-gateway-generate-cert-request.md) | object |  |
| [zero-trust-gateway_host-selector-settings](zero-trust-gateway-host-selector-settings.md) | object | Enable host selection in egress policies. |
| [zero-trust-gateway_id](zero-trust-gateway-id.md) | primitive | Identify this category. Only one category per ID. |
| [zero-trust-gateway_identifier](zero-trust-gateway-identifier.md) | primitive |  |
| [zero-trust-gateway_identity](zero-trust-gateway-identity.md) | primitive | Specify the wirefilter expression used for identit |
| [zero-trust-gateway_in_review_apps](zero-trust-gateway-in-review-apps.md) | array | Contains the ids of the applications in review. |
| [zero-trust-gateway_inspection-settings](zero-trust-gateway-inspection-settings.md) | object | Define the proxy inspection mode. |
| [zero-trust-gateway_ip](zero-trust-gateway-ip.md) | primitive | Defines the automatically generated IPv6 destinati |
| [zero-trust-gateway_ip_network](zero-trust-gateway-ip-network.md) | object |  |
| [zero-trust-gateway_ip_networks](zero-trust-gateway-ip-networks.md) | array | Specify the list of allowed source IP network rang |
| [zero-trust-gateway_ips](zero-trust-gateway-ips.md) | array | Specify the list of CIDRs to restrict ingress conn |
| [zero-trust-gateway_ipv4_endpoint](zero-trust-gateway-ipv4-endpoint.md) | object |  |
| [zero-trust-gateway_ipv4_network](zero-trust-gateway-ipv4-network.md) | object |  |
| [zero-trust-gateway_ipv4_networks](zero-trust-gateway-ipv4-networks.md) | array | Specify the list of network ranges from which requ |
| [zero-trust-gateway_ipv6_endpoint](zero-trust-gateway-ipv6-endpoint.md) | object |  |
| [zero-trust-gateway_ipv6_network](zero-trust-gateway-ipv6-network.md) | object |  |
| [zero-trust-gateway_ipv6_networks](zero-trust-gateway-ipv6-networks.md) | array | Specify the list of allowed source IPv6 network ra |
| [zero-trust-gateway_items](zero-trust-gateway-items.md) | array | Provide the list items. |
| [zero-trust-gateway_items-input](zero-trust-gateway-items-input.md) | array | Add items to the list. |
| [zero-trust-gateway_list_item_response_collection](zero-trust-gateway-list-item-response-collection.md) | allOf |  |
| [zero-trust-gateway_list_single_response](zero-trust-gateway-list-single-response.md) | allOf |  |
| [zero-trust-gateway_lists](zero-trust-gateway-lists.md) | object |  |
| [zero-trust-gateway_locations](zero-trust-gateway-locations.md) | object |  |
| [zero-trust-gateway_messages](zero-trust-gateway-messages.md) | array |  |
| [zero-trust-gateway_name](zero-trust-gateway-name.md) | primitive | Specify the list name. |
| [zero-trust-gateway_notification_settings](zero-trust-gateway-notification-settings.md) | object | Configure the message the user's device shows duri |
| [zero-trust-gateway_pacfile](zero-trust-gateway-pacfile.md) | object |  |
| [zero-trust-gateway_pacfiles_components-schemas-description](zero-trust-gateway-pacfiles-components-schemas-description.md) | primitive | Detailed description of the PAC file. |
| [zero-trust-gateway_pacfiles_components-schemas-name](zero-trust-gateway-pacfiles-components-schemas-name.md) | primitive | Name of the PAC file. |
| [zero-trust-gateway_pacfiles_components-schemas-response_collection](zero-trust-gateway-pacfiles-components-schemas-response-collection.md) | allOf |  |
| [zero-trust-gateway_pacfiles_components-schemas-single_response](zero-trust-gateway-pacfiles-components-schemas-single-response.md) | allOf |  |
| [zero-trust-gateway_precedence](zero-trust-gateway-precedence.md) | primitive | Set the order of your rules. Lower values indicate |
| [zero-trust-gateway_protocol-detection](zero-trust-gateway-protocol-detection.md) | object | Specify whether to detect protocols from the initi |
| [zero-trust-gateway_provider_name](zero-trust-gateway-provider-name.md) | primitive | Specify the provider name (usually Cloudflare). |
| [zero-trust-gateway_proxy-endpoint-identity](zero-trust-gateway-proxy-endpoint-identity.md) | object |  |
| [zero-trust-gateway_proxy-endpoint-identity-create](zero-trust-gateway-proxy-endpoint-identity-create.md) | object |  |
| [zero-trust-gateway_proxy-endpoint-ip](zero-trust-gateway-proxy-endpoint-ip.md) | object |  |
| [zero-trust-gateway_proxy-endpoint-ip-create](zero-trust-gateway-proxy-endpoint-ip-create.md) | object |  |
| [zero-trust-gateway_proxy-endpoints](zero-trust-gateway-proxy-endpoints.md) | oneOf |  |
| [zero-trust-gateway_proxy-endpoints_components-schemas-name](zero-trust-gateway-proxy-endpoints-components-schemas-name.md) | primitive | Specify the name of the proxy endpoint. |
| [zero-trust-gateway_proxy-endpoints_components-schemas-response_collection](zero-trust-gateway-proxy-endpoints-components-schemas-response-collection.md) | allOf |  |
| [zero-trust-gateway_proxy-endpoints_components-schemas-single_response](zero-trust-gateway-proxy-endpoints-components-schemas-single-response.md) | allOf |  |
| [zero-trust-gateway_public_key](zero-trust-gateway-public-key.md) | primitive | Provide the Base64-encoded HPKE public key that en |
| [zero-trust-gateway_read_only](zero-trust-gateway-read-only.md) | primitive | Indicate that this rule is shared via the Orgs API |
| [zero-trust-gateway_read_only_timestamp](zero-trust-gateway-read-only-timestamp.md) | primitive |  |
| [zero-trust-gateway_response_collection](zero-trust-gateway-response-collection.md) | allOf |  |
| [zero-trust-gateway_result_info](zero-trust-gateway-result-info.md) | object |  |
| [zero-trust-gateway_rule-settings](zero-trust-gateway-rule-settings.md) | object | Defines settings for this rule. Settings apply onl |
| [zero-trust-gateway_rules](zero-trust-gateway-rules.md) | object |  |
| [zero-trust-gateway_rules_components-schemas-response_collection](zero-trust-gateway-rules-components-schemas-response-collection.md) | allOf |  |
| [zero-trust-gateway_sandbox](zero-trust-gateway-sandbox.md) | object | Specify whether to enable the sandbox. |
| [zero-trust-gateway_schedule](zero-trust-gateway-schedule.md) | object | Defines the schedule for activating DNS policies.  |
| [zero-trust-gateway_schemas-description](zero-trust-gateway-schemas-description.md) | primitive | Specify the rule description. |
| [zero-trust-gateway_schemas-identifier](zero-trust-gateway-schemas-identifier.md) | primitive |  |
| [zero-trust-gateway_schemas-name](zero-trust-gateway-schemas-name.md) | primitive | Specify the location name. |
| [zero-trust-gateway_schemas-response_collection](zero-trust-gateway-schemas-response-collection.md) | allOf |  |
| [zero-trust-gateway_schemas-single_response](zero-trust-gateway-schemas-single-response.md) | allOf |  |
| [zero-trust-gateway_schemas-subdomain](zero-trust-gateway-schemas-subdomain.md) | primitive | Specify the subdomain to use as the destination in |
| [zero-trust-gateway_schemas-type](zero-trust-gateway-schemas-type.md) | enum | Specify the list type. |
| [zero-trust-gateway_schemas-uuid](zero-trust-gateway-schemas-uuid.md) | primitive | Identify the API resource with a UUID. |
| [zero-trust-gateway_settings](zero-trust-gateway-settings.md) | object |  |
| [zero-trust-gateway_sharable](zero-trust-gateway-sharable.md) | primitive | Indicate that this rule is sharable via the Orgs A |
| [zero-trust-gateway_single_response](zero-trust-gateway-single-response.md) | allOf |  |
| [zero-trust-gateway_single_response_with_list_items](zero-trust-gateway-single-response-with-list-items.md) | allOf |  |
| [zero-trust-gateway_slug](zero-trust-gateway-slug.md) | primitive | URL-friendly version of the PAC file name. |
| [zero-trust-gateway_source_account](zero-trust-gateway-source-account.md) | primitive | Provide the account tag of the account that create |
| [zero-trust-gateway_subcategory](zero-trust-gateway-subcategory.md) | object |  |
| [zero-trust-gateway_subdomain](zero-trust-gateway-subdomain.md) | primitive | Specify the DNS over HTTPS domain that receives DN |
| [zero-trust-gateway_timestamp](zero-trust-gateway-timestamp.md) | primitive |  |
| [zero-trust-gateway_tls-settings](zero-trust-gateway-tls-settings.md) | object | Specify whether to inspect encrypted HTTP traffic. |
| [zero-trust-gateway_traffic](zero-trust-gateway-traffic.md) | primitive | Specify the wirefilter expression used for traffic |
| [zero-trust-gateway_type](zero-trust-gateway-type.md) | enum | Indicate the read-only certificate type, BYO-PKI ( |
| [zero-trust-gateway_unapproved_apps](zero-trust-gateway-unapproved-apps.md) | array | Contains the ids of the unapproved applications. |
| [zero-trust-gateway_url](zero-trust-gateway-url.md) | primitive | Unique URL to download the PAC file. |
| [zero-trust-gateway_uuid](zero-trust-gateway-uuid.md) | primitive | Identify the certificate with a UUID. |
| [zero-trust-gateway_value](zero-trust-gateway-value.md) | primitive | Specify the item value. |
| [zero-trust-gateway_version](zero-trust-gateway-version.md) | primitive | Indicate the version number of the rule(read-only) |
| [zero-trust-gateway_warning_status](zero-trust-gateway-warning-status.md) | primitive | Indicate a warning for a misconfigured rule, if an |
