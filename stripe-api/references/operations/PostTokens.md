# POST /v1/tokens

**Resource:** [tokens](../resources/tokens.md)
**Create a CVC update token**
**Operation ID:** `PostTokens`

<p>Creates a single-use token that represents a bank account’s details.
You can use this token with any v1 API method in place of a bank account dictionary. You can only use this token once. To do so, attach it to a <a href="#accounts">connected account</a> where <a href="/api/accounts/object#account_object-controller-requirement_collection">controller.requirement_collection</a> is <code>application</code>, which includes Custom accounts.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[token](../schemas/token/token.md)

