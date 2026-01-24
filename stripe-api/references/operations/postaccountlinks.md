# POST /v1/account_links

**Resource:** [account_links](../resources/account-links.md)
**Create an account link**
**Operation ID:** `PostAccountLinks`

<p>Creates an AccountLink object that includes a single-use Stripe URL that the platform can redirect their user to in order to take them through the Connect Onboarding flow.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[account_link](../schemas/account/account-link.md)

