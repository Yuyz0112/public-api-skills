# GET /accounts/{account_id}/hyperdrive/configs

**Resource:** [Hyperdrive](../resources/Hyperdrive.md)
**List Hyperdrives**
**Operation ID:** `list-hyperdrive`

Returns a list of Hyperdrives.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | hyperdrive_identifier | Yes | The Cloudflare account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Hyperdrives Response. |
| 4XX | List Hyperdrives Failure Response. |

## Security

- **api_token**
- **api_email**
- **api_key**
