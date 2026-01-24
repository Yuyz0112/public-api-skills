# POST /v1/linked_accounts/{account}/refresh

**Resource:** [linked_accounts](../resources/linked-accounts.md)
**Refresh Account data**
**Operation ID:** `PostLinkedAccountsAccountRefresh`

<p>Refreshes the data associated with a Financial Connections <code>Account</code>.</p>

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

