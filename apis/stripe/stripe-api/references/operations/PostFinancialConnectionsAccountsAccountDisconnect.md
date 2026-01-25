# POST /v1/financial_connections/accounts/{account}/disconnect

**Resource:** [financial_connections](../resources/financial-connections.md)
**Disconnect an Account**
**Operation ID:** `PostFinancialConnectionsAccountsAccountDisconnect`

<p>Disables your access to a Financial Connections <code>Account</code>. You will no longer be able to access data associated with the account (e.g. balances, transactions).</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[financial_connections.account](../schemas/financial/financial-connections-account.md)

