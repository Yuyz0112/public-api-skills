# POST /v1/setup_intents/{intent}/verify_microdeposits

**Resource:** [setup_intents](../resources/setup-intents.md)
**Verify microdeposits on a SetupIntent**
**Operation ID:** `PostSetupIntentsIntentVerifyMicrodeposits`

<p>Verifies microdeposits on a SetupIntent object.</p>

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

