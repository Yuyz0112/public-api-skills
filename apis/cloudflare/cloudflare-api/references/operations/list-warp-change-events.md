# GET /accounts/{account_id}/dex/warp-change-events

**Resource:** [WARP Change Events](../resources/WARP-Change-Events.md)
**List WARP change events.**
**Operation ID:** `list-warp-change-events`

List WARP configuration and enablement toggle change events by device.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account in the API request path |
| `page` | query | number | Yes | Page number of paginated results |
| `per_page` | query | number | Yes | Number of items per page |
| `from` | query | string | Yes | Start time for the query in ISO (RFC3339 - ISO 8601) format |
| `to` | query | string | Yes | End time for the query in ISO (RFC3339 - ISO 8601) format |
| `type` | query | enum: config, toggle | No | Filter events by type 'config' or 'toggle' |
| `toggle` | query | enum: on, off | No | Filter events by type toggle value. Applicable to type='toggle' events only. |
| `config_name` | query | string | No | Filter events by WARP configuration name changed from or to. Applicable to type='config' events only. |
| `account_name` | query | string | No | Filter events by account name. |
| `sort_order` | query | enum: ASC, DESC | No | Sort response by event timestamp. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | success response |
| 4XX | List WARP change events failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
