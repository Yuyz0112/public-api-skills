# POST /v1/accounts/{account}/login_links

**Resource:** [accounts](../resources/accounts.md)
**Create a login link**
**Operation ID:** `PostAccountsAccountLoginLinks`

<p>Creates a login link for a connected account to access the Express Dashboard.</p>

<p><strong>You can only create login links for accounts that use the <a href="/connect/express-dashboard">Express Dashboard</a> and are connected to your platform</strong>.</p>

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

[login_link](../schemas/login/login-link.md)

