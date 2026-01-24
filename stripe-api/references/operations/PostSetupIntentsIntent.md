# POST /v1/setup_intents/{intent}

**Resource:** [setup_intents](../resources/setup-intents.md)
**Update a SetupIntent**
**Operation ID:** `PostSetupIntentsIntent`

<p>Updates a SetupIntent object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `intent` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[setup_intent](../schemas/setup/setup-intent.md)

