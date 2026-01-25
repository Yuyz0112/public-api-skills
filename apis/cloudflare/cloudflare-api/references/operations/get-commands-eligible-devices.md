# GET /accounts/{account_id}/dex/commands/devices

**Resource:** [DEX Remote Commands](../resources/DEX-Remote-Commands.md)
**List devices eligible for remote captures**
**Operation ID:** `get-commands-eligible-devices`

List devices with WARP client support for remote captures which have been connected in the last 1 hour.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account in the API request path |
| `page` | query | number | Yes | Page number of paginated results |
| `per_page` | query | number | Yes | Number of items per page |
| `search` | query | string | No | Filter devices by name or email |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of eligible devices |
| 4XX | List eligible devices failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
