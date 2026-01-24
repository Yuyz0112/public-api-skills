# POST /v1/ephemeral_keys

**Resource:** [ephemeral_keys](../resources/ephemeral-keys.md)
**Create an ephemeral key**
**Operation ID:** `PostEphemeralKeys`

<p>Creates a short-lived API key for a given resource.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[ephemeral_key](../schemas/ephemeral/ephemeral-key.md)

