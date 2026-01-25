# DELETE /accounts/{account_id}/hyperdrive/configs/{hyperdrive_id}

**Resource:** [Hyperdrive](../resources/Hyperdrive.md)
**Delete Hyperdrive**
**Operation ID:** `delete-hyperdrive`

Deletes the specified Hyperdrive.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | hyperdrive_identifier | Yes | The Cloudflare account ID. |
| `hyperdrive_id` | path | hyperdrive_identifier | Yes | The unique identifier of the Hyperdrive configuration. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Hyperdrive Response. |
| 4XX | Delete Hyperdrive Failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
