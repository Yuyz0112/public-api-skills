# POST /v1/accounts

**Resource:** [accounts](../resources/accounts.md)
**Operation ID:** `PostAccounts`

<p>With <a href="/docs/connect">Connect</a>, you can create Stripe accounts for your users.
To do this, you’ll first need to <a href="https://dashboard.stripe.com/account/applications/settings">register your platform</a>.</p>

<p>If you’ve already collected information for your connected accounts, you <a href="/docs/connect/best-practices#onboarding">can prefill that information</a> when
creating the account. Connect Onboarding won’t ask for the prefilled information during account onboarding.
You can prefill any information on the account.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[account](../schemas/account/account.md)

