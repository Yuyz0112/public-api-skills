# PUT /accounts/{account_id}/hyperdrive/configs/{hyperdrive_id}

**Resource:** [Hyperdrive](../resources/Hyperdrive.md)
**Update Hyperdrive**
**Operation ID:** `update-hyperdrive`

Updates and returns the specified Hyperdrive configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | hyperdrive_identifier | Yes | The Cloudflare account ID. |
| `hyperdrive_id` | path | hyperdrive_identifier | Yes | The unique identifier of the Hyperdrive configuration. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [hyperdrive_hyperdrive-config](../schemas/hyperdrive/hyperdrive-hyperdrive-config.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Hyperdrive Response. |
| 4XX | Update Hyperdrive Failure Response. |

## Security

- **api_token**
- **api_email**
- **api_key**
