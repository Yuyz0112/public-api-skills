# DELETE /v1/accounts/{account}

**Resource:** [accounts](../resources/accounts.md)
**Delete an account**
**Operation ID:** `DeleteAccountsAccount`

<p>With <a href="/connect">Connect</a>, you can delete accounts you manage.</p>

<p>Test-mode accounts can be deleted at any time.</p>

<p>Live-mode accounts that have access to the standard dashboard and Stripe is responsible for negative account balances cannot be deleted, which includes Standard accounts. All other Live-mode accounts, can be deleted when all <a href="/api/balance/balance_object">balances</a> are zero.</p>

<p>If you want to delete your own account, use the <a href="https://dashboard.stripe.com/settings/account">account information tab in your account settings</a> instead.</p>

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

[deleted_account](../schemas/deleted/deleted-account.md)

