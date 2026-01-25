# PATCH /accounts/{account_id}/hyperdrive/configs/{hyperdrive_id}

**Resource:** [Hyperdrive](../resources/Hyperdrive.md)
**Patch Hyperdrive**
**Operation ID:** `patch-hyperdrive`

Patches and returns the specified Hyperdrive configuration. Custom caching settings are not kept if caching is disabled.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | hyperdrive_identifier | Yes | The Cloudflare account ID. |
| `hyperdrive_id` | path | hyperdrive_identifier | Yes | The unique identifier of the Hyperdrive configuration. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [hyperdrive_hyperdrive-config-patch](../schemas/hyperdrive/hyperdrive-hyperdrive-config-patch.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch Hyperdrive Response. |
| 4XX | Patch Hyperdrive Failure Response. |

## Security

- **api_token**
- **api_email**
- **api_key**
