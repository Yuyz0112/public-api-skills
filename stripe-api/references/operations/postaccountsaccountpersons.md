# POST /v1/accounts/{account}/persons

**Resource:** [accounts](../resources/accounts.md)
**Create a person**
**Operation ID:** `PostAccountsAccountPersons`

<p>Creates a new person.</p>

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

[person](../schemas/person/person.md)

