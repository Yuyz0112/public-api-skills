# zones_zone

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | object | Yes | The account the zone belongs to. |
| `activated_on` | string (date-time) | Yes | The last time proof of ownership was detected and the zone was made
active. |
| `cname_suffix` | string | No | Allows the customer to use a custom apex.
*Tenants Only Configuration*. |
| `created_on` | string (date-time) | Yes | When the zone was created. |
| `development_mode` | number | Yes | The interval (in seconds) from when development mode expires
(positive integer) or last expired (negative integer) for the
domain. If development mode has never been enabled, this value is 0. |
| `id` | [zones_identifier](zones-identifier.md) | Yes |  |
| `meta` | object | Yes | Metadata about the zone. |
| `modified_on` | string (date-time) | Yes | When the zone was last modified. |
| `name` | string | Yes | The domain name. |
| `name_servers` | string[] | Yes | The name servers Cloudflare assigns to a zone. |
| `original_dnshost` | string | Yes | DNS host at the time of switching to Cloudflare. |
| `original_name_servers` | string[] | Yes | Original name servers before moving to Cloudflare. |
| `original_registrar` | string | Yes | Registrar for the domain at the time of switching to Cloudflare. |
| `owner` | object | Yes | The owner of the zone. |
| `paused` | [zones_paused](zones-paused.md) | No |  |
| `permissions` | string[] | No | Legacy permissions based on legacy user membership information. |
| `plan` | any | Yes | A Zones subscription information. |
| `status` | enum: initializing, pending, active... | No | The zone status on Cloudflare. |
| `tenant` | any | No | The root organizational unit that this zone belongs to (such as a tenant or organization). |
| `tenant_unit` | any | No | The immediate parent organizational unit that this zone belongs to (such as under a tenant or sub-organization). |
| `type` | [zones_type](zones-type.md) | No |  |
| `vanity_name_servers` | string[] | No | An array of domains used for custom name servers. This is only available for Business and Enterprise plans. |
| `verification_key` | string | No | Verification key for partial zone setup. |

## Nested Fields

### `account`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [zones_identifier](zones-identifier.md) | No |  |
| `name` | string | No | The name of the account. |

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cdn_only` | boolean | No | The zone is only configured for CDN. |
| `custom_certificate_quota` | integer | No | Number of Custom Certificates the zone can have. |
| `dns_only` | boolean | No | The zone is only configured for DNS. |
| `foundation_dns` | boolean | No | The zone is setup with Foundation DNS. |
| `page_rule_quota` | integer | No | Number of Page Rules a zone can have. |
| `phishing_detected` | boolean | No | The zone has been flagged for phishing. |
| `step` | integer | No |  |

### `owner`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [zones_identifier](zones-identifier.md) | No |  |
| `name` | string | No | Name of the owner. |
| `type` | string | No | The type of owner. |

