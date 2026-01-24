# GET /v1/balance_settings

**Resource:** [balance_settings](../resources/balance-settings.md)
**Retrieve balance settings**
**Operation ID:** `GetBalanceSettings`

<p>Retrieves balance settings for a given connected account.
 Related guide: <a href="/connect/authentication">Making API calls for connected accounts</a></p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[balance_settings](../schemas/balance/balance-settings.md)

