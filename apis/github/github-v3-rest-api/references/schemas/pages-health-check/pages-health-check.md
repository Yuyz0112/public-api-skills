# pages-health-check

Pages Health Check Status

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `domain` | object | No |  |
| `alt_domain` | object | No |  |

## Nested Fields

### `domain`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `host` | string | No |  |
| `uri` | string | No |  |
| `nameservers` | string | No |  |
| `dns_resolves` | boolean | No |  |
| `is_proxied` | boolean | No |  |
| `is_cloudflare_ip` | boolean | No |  |
| `is_fastly_ip` | boolean | No |  |
| `is_old_ip_address` | boolean | No |  |
| `is_a_record` | boolean | No |  |
| `has_cname_record` | boolean | No |  |
| `has_mx_records_present` | boolean | No |  |
| `is_valid_domain` | boolean | No |  |
| `is_apex_domain` | boolean | No |  |
| `should_be_a_record` | boolean | No |  |
| `is_cname_to_github_user_domain` | boolean | No |  |
| `is_cname_to_pages_dot_github_dot_com` | boolean | No |  |
| `is_cname_to_fastly` | boolean | No |  |
| `is_pointed_to_github_pages_ip` | boolean | No |  |
| `is_non_github_pages_ip_present` | boolean | No |  |
| `is_pages_domain` | boolean | No |  |
| `is_served_by_pages` | boolean | No |  |
| `is_valid` | boolean | No |  |
| `reason` | string | No |  |
| `responds_to_https` | boolean | No |  |
| `enforces_https` | boolean | No |  |
| `https_error` | string | No |  |
| `is_https_eligible` | boolean | No |  |
| `caa_error` | string | No |  |

### `alt_domain`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `host` | string | No |  |
| `uri` | string | No |  |
| `nameservers` | string | No |  |
| `dns_resolves` | boolean | No |  |
| `is_proxied` | boolean | No |  |
| `is_cloudflare_ip` | boolean | No |  |
| `is_fastly_ip` | boolean | No |  |
| `is_old_ip_address` | boolean | No |  |
| `is_a_record` | boolean | No |  |
| `has_cname_record` | boolean | No |  |
| `has_mx_records_present` | boolean | No |  |
| `is_valid_domain` | boolean | No |  |
| `is_apex_domain` | boolean | No |  |
| `should_be_a_record` | boolean | No |  |
| `is_cname_to_github_user_domain` | boolean | No |  |
| `is_cname_to_pages_dot_github_dot_com` | boolean | No |  |
| `is_cname_to_fastly` | boolean | No |  |
| `is_pointed_to_github_pages_ip` | boolean | No |  |
| `is_non_github_pages_ip_present` | boolean | No |  |
| `is_pages_domain` | boolean | No |  |
| `is_served_by_pages` | boolean | No |  |
| `is_valid` | boolean | No |  |
| `reason` | string | No |  |
| `responds_to_https` | boolean | No |  |
| `enforces_https` | boolean | No |  |
| `https_error` | string | No |  |
| `is_https_eligible` | boolean | No |  |
| `caa_error` | string | No |  |

