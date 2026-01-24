# GET /v1/accounts/{account}/persons/{person}

**Resource:** [accounts](../resources/accounts.md)
**Retrieve a person**
**Operation ID:** `GetAccountsAccountPersonsPerson`

<p>Retrieves an existing person.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `person` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[person](../schemas/person/person.md)

