# POST /accounts/{account_id}/hyperdrive/configs

**Resource:** [Hyperdrive](../resources/Hyperdrive.md)
**Create Hyperdrive**
**Operation ID:** `create-hyperdrive`

Creates and returns a new Hyperdrive configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | hyperdrive_identifier | Yes | The Cloudflare account ID. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [hyperdrive_hyperdrive-config](../schemas/hyperdrive/hyperdrive-hyperdrive-config.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Hyperdrive Response. |
| 4XX | Create Hyperdrive Failure Response. |

## Security

- **api_token**
- **api_email**
- **api_key**
