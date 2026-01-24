# POST /v1/setup_intents

**Resource:** [setup_intents](../resources/setup-intents.md)
**Create a SetupIntent**
**Operation ID:** `PostSetupIntents`

<p>Creates a SetupIntent object.</p>

<p>After you create the SetupIntent, attach a payment method and <a href="/docs/api/setup_intents/confirm">confirm</a>
it to collect any required permissions to charge the payment method later.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[setup_intent](../schemas/setup/setup-intent.md)

