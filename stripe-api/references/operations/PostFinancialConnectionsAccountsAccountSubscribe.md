# POST /v1/financial_connections/accounts/{account}/subscribe

**Resource:** [financial_connections](../resources/financial-connections.md)
**Subscribe to data refreshes for an Account**
**Operation ID:** `PostFinancialConnectionsAccountsAccountSubscribe`

<p>Subscribes to periodic refreshes of data associated with a Financial Connections <code>Account</code>. When the account status is active, data is typically refreshed once a day.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[financial_connections.account](../schemas/financial/financial-connections-account.md)

