# GET /v1/accounts/{account}/capabilities/{capability}

**Resource:** [accounts](../resources/accounts.md)
**Retrieve an Account Capability**
**Operation ID:** `GetAccountsAccountCapabilitiesCapability`

<p>Retrieves information about the specified Account Capability.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account` | path | string | Yes |  |
| `capability` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[capability](../schemas/capability/capability.md)

