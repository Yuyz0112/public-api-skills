# DELETE /v1/ephemeral_keys/{key}

**Resource:** [ephemeral_keys](../resources/ephemeral-keys.md)
**Immediately invalidate an ephemeral key**
**Operation ID:** `DeleteEphemeralKeysKey`

<p>Invalidates a short-lived API key for a given resource.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[ephemeral_key](../schemas/ephemeral/ephemeral-key.md)

