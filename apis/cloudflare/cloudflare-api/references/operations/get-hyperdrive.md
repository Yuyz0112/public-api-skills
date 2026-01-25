# GET /accounts/{account_id}/hyperdrive/configs/{hyperdrive_id}

**Resource:** [Hyperdrive](../resources/Hyperdrive.md)
**Get Hyperdrive**
**Operation ID:** `get-hyperdrive`

Returns the specified Hyperdrive configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | hyperdrive_identifier | Yes | The Cloudflare account ID. |
| `hyperdrive_id` | path | hyperdrive_identifier | Yes | The unique identifier of the Hyperdrive configuration. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Hyperdrive Response. |
| 4XX | Get Hyperdrive Failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
