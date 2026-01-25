# GET /accounts/{account_id}/infrastructure/targets

**Resource:** [Infrastructure Access Targets](../resources/Infrastructure-Access-Targets.md)
**List all targets**
**Operation ID:** `infra-targets-list`

Lists and sorts an account’s targets. Filters are optional and are ANDed
together.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | infra_AccountTag | Yes |  |
| `hostname` | query | string | No | Hostname of a target |
| `hostname_contains` | query | string | No | Partial match to the hostname of a target |
| `virtual_network_id` | query | string (uuid) | No | Private virtual network identifier of the target |
| `ip_v4` | query | string | No | IPv4 address of the target |
| `ip_v6` | query | string | No | IPv6 address of the target |
| `created_before` | query | string (date-time) | No | Date and time at which the target was created before (inclusive) |
| `created_after` | query | string (date-time) | No | Date and time at which the target was created after (inclusive) |
| `modified_before` | query | string (date-time) | No | Date and time at which the target was modified before (inclusive) |
| `modified_after` | query | string (date-time) | No | Date and time at which the target was modified after (inclusive) |
| `ips` | query | string[] | No | Filters for targets that have any of the following IP addresses. Specify
`ips` multiple times in query parameter to build list of candidates. |
| `target_ids` | query | string[] | No | Filters for targets that have any of the following UUIDs. Specify
`target_ids` multiple times in query parameter to build list of
candidates. |
| `ip_like` | query | string | No | Filters for targets whose IP addresses look like the specified string.
Supports `*` as a wildcard character |
| `ipv4_start` | query | string | No | Defines an IPv4 filter range's starting value (inclusive). Requires
`ipv4_end` to be specified as well. |
| `ipv4_end` | query | string | No | Defines an IPv4 filter range's ending value (inclusive). Requires
`ipv4_start` to be specified as well. |
| `ipv6_start` | query | string | No | Defines an IPv6 filter range's starting value (inclusive). Requires
`ipv6_end` to be specified as well. |
| `ipv6_end` | query | string | No | Defines an IPv6 filter range's ending value (inclusive). Requires
`ipv6_start` to be specified as well. |
| `page` | query | integer (int32) | No | Current page in the response |
| `per_page` | query | integer (int32) | No | Max amount of entries returned per page |
| `order` | query | enum: hostname, created_at | No | The field to sort by. |
| `direction` | query | any | No | The sorting direction. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved all targets in the account |
| 4XX | Failed to retrieve all targets in the account |

## Security

- **api_email**
- **api_key**
- **api_token**
