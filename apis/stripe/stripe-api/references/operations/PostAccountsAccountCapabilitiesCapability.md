# POST /v1/accounts/{account}/capabilities/{capability}

**Resource:** [accounts](../resources/accounts.md)
**Update an Account Capability**
**Operation ID:** `PostAccountsAccountCapabilitiesCapability`

<p>Updates an existing Account Capability. Request or remove a capability by updating its <code>requested</code> parameter.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account` | path | string | Yes |  |
| `capability` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[capability](../schemas/capability/capability.md)

