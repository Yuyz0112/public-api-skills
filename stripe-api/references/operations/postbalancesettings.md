# POST /v1/balance_settings

**Resource:** [balance_settings](../resources/balance-settings.md)
**Update balance settings**
**Operation ID:** `PostBalanceSettings`

<p>Updates balance settings for a given connected account.
 Related guide: <a href="/connect/authentication">Making API calls for connected accounts</a></p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[balance_settings](../schemas/balance/balance-settings.md)

