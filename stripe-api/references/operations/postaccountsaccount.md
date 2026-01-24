# POST /v1/accounts/{account}

**Resource:** [accounts](../resources/accounts.md)
**Update an account**
**Operation ID:** `PostAccountsAccount`

<p>Updates a <a href="/connect/accounts">connected account</a> by setting the values of the parameters passed. Any parameters not provided are
left unchanged.</p>

<p>For accounts where <a href="/api/accounts/object#account_object-controller-requirement_collection">controller.requirement_collection</a>
is <code>application</code>, which includes Custom accounts, you can update any information on the account.</p>

<p>For accounts where <a href="/api/accounts/object#account_object-controller-requirement_collection">controller.requirement_collection</a>
is <code>stripe</code>, which includes Standard and Express accounts, you can update all information until you create
an <a href="/api/account_links">Account Link</a> or <a href="/api/account_sessions">Account Session</a> to start Connect onboarding,
after which some properties can no longer be updated.</p>

<p>To update your own account, use the <a href="https://dashboard.stripe.com/settings/account">Dashboard</a>. Refer to our
<a href="/docs/connect/updating-accounts">Connect</a> documentation to learn more about updating accounts.</p>

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

[account](../schemas/account/account.md)

