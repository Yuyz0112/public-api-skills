# zero-trust-gateway_rule-settings

Defines settings for this rule. Settings apply only to specific rule types and must use compatible selectors. If Terraform detects drift, confirm the setting supports your rule type and check whether the API modifies the value. Use API-returned values in your configuration to prevent drift.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `add_headers` | object | No | Add custom headers to allowed requests as key-value pairs. Use header names as keys that map to arrays of header values. Settable only for `http` rules with the action set to `allow`. |
| `allow_child_bypass` | boolean | No | Set to enable MSP children to bypass this rule. Only parent MSP accounts can set this. this rule. Settable for all types of rules. |
| `audit_ssh` | object | No | Define the settings for the Audit SSH action. Settable only for `l4` rules with `audit_ssh` action. |
| `biso_admin_controls` | object | No | Configure browser isolation behavior. Settable only for `http` rules with the action set to `isolate`. |
| `block_page` | object | No | Configure custom block page settings. If missing or null, use the account settings. Settable only for `http` rules with the action set to `block`. |
| `block_page_enabled` | boolean | No | Enable the custom block page. Settable only for `dns` rules with action `block`. |
| `block_reason` | string | No | Explain why the rule blocks the request. The custom block page shows this text (if enabled). Settable only for `dns`, `l4`, and `http` rules when the action set to `block`. |
| `bypass_parent_rule` | boolean | No | Set to enable MSP accounts to bypass their parent's rules. Only MSP child accounts can set this. Settable for all types of rules. |
| `check_session` | object | No | Configure session check behavior. Settable only for `l4` and `http` rules with the action set to `allow`. |
| `dns_resolvers` | object | No | Configure custom resolvers to route queries that match the resolver policy. Unused with 'resolve_dns_through_cloudflare' or 'resolve_dns_internally' settings. DNS queries get routed to the address closest to their origin. Only valid when a rule's action set to 'resolve'. Settable only for `dns_resolver` rules. |
| `egress` | object | No | Configure how Gateway Proxy traffic egresses. You can enable this setting for rules with Egress actions and filters, or omit it to indicate local egress via WARP IPs. Settable only for `egress` rules. |
| `forensic_copy` | object | No | Configure whether a copy of the HTTP request will be sent to storage when the rule matches. |
| `ignore_cname_category_matches` | boolean | No | Ignore category matches at CNAME domains in a response. When off, evaluate categories in this rule against all CNAME domain categories in the response. Settable only for `dns` and `dns_resolver` rules. |
| `insecure_disable_dnssec_validation` | boolean | No | Specify whether to disable DNSSEC validation (for Allow actions) [INSECURE]. Settable only for `dns` rules. |
| `ip_categories` | boolean | No | Enable IPs in DNS resolver category blocks. The system blocks only domain name categories unless you enable this setting. Settable only for `dns` and `dns_resolver` rules. |
| `ip_indicator_feeds` | boolean | No | Indicates whether to include IPs in DNS resolver indicator feed blocks. Default, indicator feeds block only domain names. Settable only for `dns` and `dns_resolver` rules. |
| `l4override` | object | No | Send matching traffic to the supplied destination IP address and port. Settable only for `l4` rules with the action set to `l4_override`. |
| `notification_settings` | object | No | Configure a notification to display on the user's device when this rule matched. Settable for all types of rules with the action set to `block`. |
| `override_host` | string | No | Defines a hostname for override, for the matching DNS queries. Settable only for `dns` rules with the action set to `override`. |
| `override_ips` | string[] | No | Defines a an IP or set of IPs for overriding matched DNS queries. Settable only for `dns` rules with the action set to `override`. |
| `payload_log` | object | No | Configure DLP payload logging. Settable only for `http` rules. |
| `quarantine` | object | No | Configure settings that apply to quarantine rules. Settable only for `http` rules. |
| `redirect` | object | No | Apply settings to redirect rules. Settable only for `http` rules with the action set to `redirect`. |
| `resolve_dns_internally` | object | No | Configure to forward the query to the internal DNS service, passing the specified 'view_id' as input. Not used when 'dns_resolvers' is specified or 'resolve_dns_through_cloudflare' is set. Only valid when a rule's action set to 'resolve'. Settable only for `dns_resolver` rules. |
| `resolve_dns_through_cloudflare` | boolean | No | Enable to send queries that match the policy to Cloudflare's default 1.1.1.1 DNS resolver. Cannot set when 'dns_resolvers' specified or 'resolve_dns_internally' is set. Only valid when a rule's action set to 'resolve'. Settable only for `dns_resolver` rules. |
| `untrusted_cert` | object | No | Configure behavior when an upstream certificate is invalid or an SSL error occurs. Settable only for `http` rules with the action set to `allow`. |

## Nested Fields

### `audit_ssh`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `command_logging` | boolean | No | Enable SSH command logging. |

### `biso_admin_controls`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `copy` | enum: enabled, disabled, remote_only | No | Configure copy behavior. If set to remote_only, users cannot copy isolated content from the remote browser to the local clipboard. If this field is absent, copying remains enabled. Applies only when version == "v2". |
| `dcp` | boolean | No | Set to false to enable copy-pasting. Only applies when `version == "v1"`. |
| `dd` | boolean | No | Set to false to enable downloading. Only applies when `version == "v1"`. |
| `dk` | boolean | No | Set to false to enable keyboard usage. Only applies when `version == "v1"`. |
| `download` | enum: enabled, disabled, remote_only | No | Configure download behavior. When set to remote_only, users can view downloads but cannot save them. Applies only when version == "v2". |
| `dp` | boolean | No | Set to false to enable printing. Only applies when `version == "v1"`. |
| `du` | boolean | No | Set to false to enable uploading. Only applies when `version == "v1"`. |
| `keyboard` | enum: enabled, disabled | No | Configure keyboard usage behavior. If this field is absent, keyboard usage remains enabled. Applies only when version == "v2". |
| `paste` | enum: enabled, disabled, remote_only | No | Configure paste behavior. If set to remote_only, users cannot paste content from the local clipboard into isolated pages. If this field is absent, pasting remains enabled. Applies only when version == "v2". |
| `printing` | enum: enabled, disabled | No | Configure print behavior. Default, Printing is enabled. Applies only when version == "v2". |
| `upload` | enum: enabled, disabled | No | Configure upload behavior. If this field is absent, uploading remains enabled. Applies only when version == "v2". |
| `version` | enum: v1, v2 | No | Indicate which version of the browser isolation controls should apply. |

### `block_page`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `include_context` | boolean | No | Specify whether to pass the context information as query parameters. |
| `target_uri` | string (uri) | Yes | Specify the URI to which the user is redirected. |

### `check_session`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `duration` | string | No | Sets the required session freshness threshold. The API returns a normalized version of this value. |
| `enforce` | boolean | No | Enable session enforcement. |

### `dns_resolvers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ipv4` | zero-trust-gateway_dns_resolver_settings_v4[] | No |  |
| `ipv6` | zero-trust-gateway_dns_resolver_settings_v6[] | No |  |

### `egress`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ipv4` | string | No | Specify the IPv4 address to use for egress. |
| `ipv4_fallback` | string | No | Specify the fallback IPv4 address to use for egress when the primary IPv4 fails. Set '0.0.0.0' to indicate local egress via WARP IPs. |
| `ipv6` | string | No | Specify the IPv6 range to use for egress. |

### `forensic_copy`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Enable sending the copy to storage. |

### `l4override`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ip` | string | No | Defines the IPv4 or IPv6 address. |
| `port` | integer | No | Defines a port number to use for TCP/UDP overrides. |

### `notification_settings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Enable notification. |
| `include_context` | boolean | No | Indicates whether to pass the context information as query parameters. |
| `msg` | string | No | Customize the message shown in the notification. |
| `support_url` | string | No | Defines an optional URL to direct users to additional information. If unset, the notification opens a block page. |

### `payload_log`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Enable DLP payload logging for this rule. |

### `quarantine`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `file_types` | string[] | No | Specify the types of files to sandbox. |

### `redirect`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `include_context` | boolean | No | Specify whether to pass the context information as query parameters. |
| `preserve_path_and_query` | boolean | No | Specify whether to append the path and query parameters from the original request to target_uri. |
| `target_uri` | string (uri) | Yes | Specify the URI to which the user is redirected. |

### `resolve_dns_internally`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fallback` | enum: none, public_dns | No | Specify the fallback behavior to apply when the internal DNS response code differs from 'NOERROR' or when the response data contains only CNAME records for 'A' or 'AAAA' queries. |
| `view_id` | string | No | Specify the internal DNS view identifier to pass to the internal DNS service. |

### `untrusted_cert`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: pass_through, block, error | No | Defines the action performed when an untrusted certificate seen. The default action an error with HTTP code 526. |

