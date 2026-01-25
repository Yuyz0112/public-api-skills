# PATCH /accounts/{account_id}/cloudforce-one/scans/config/{config_id}

**Resource:** [Scans](../resources/Scans.md)
**Update an existing Scan Config**
**Operation ID:** `post_ConfigUpdate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Defines the Account ID. |
| `config_id` | path | string | Yes | Defines the Config ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the updated config. |
| 4XX | Update an Existing Scan Config failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
