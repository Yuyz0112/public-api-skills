# POST /accounts/{account_id}/cloudforce-one/scans/config

**Resource:** [Scans](../resources/Scans.md)
**Create a new Scan Config**
**Operation ID:** `post_ConfigCreate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Defines the Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the created config. |
| 4XX | Create a new Scan Config failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
