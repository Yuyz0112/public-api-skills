# GET /v1/setup_intents/{intent}

**Resource:** [setup_intents](../resources/setup-intents.md)
**Retrieve a SetupIntent**
**Operation ID:** `GetSetupIntentsIntent`

<p>Retrieves the details of a SetupIntent that has previously been created. </p>

<p>Client-side retrieval using a publishable key is allowed when the <code>client_secret</code> is provided in the query string. </p>

<p>When retrieved with a publishable key, only a subset of properties will be returned. Please refer to the <a href="#setup_intent_object">SetupIntent</a> object reference for more details.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `client_secret` | query | string | No | The client secret of the SetupIntent. We require this string if you use a publishable key to retrieve the SetupIntent. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

