# POST /zones/{zone_id}/hold

**Resource:** [Zone Holds](../resources/Zone-Holds.md)
**Create Zone Hold**
**Operation ID:** `zones-0-hold-post`

Enforce a zone hold on the zone, blocking the creation and activation of zones with this zone's hostname.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_schemas-identifier | Yes | Zone ID |
| `include_subdomains` | query | boolean | No | If provided, the zone hold will extend to block any subdomain of the given zone, as well
as SSL4SaaS Custom Hostnames. For example, a zone hold on a zone with the hostname
'example.com' and include_subdomains=true will block 'example.com',
'staging.example.com', 'api.staging.example.com', etc. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |
| 4XX | Client Error |

## Security

- **api_token**
- **api_email**
- **api_key**
