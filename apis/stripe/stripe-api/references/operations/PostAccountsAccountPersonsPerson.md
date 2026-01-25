# POST /v1/accounts/{account}/persons/{person}

**Resource:** [accounts](../resources/accounts.md)
**Update a person**
**Operation ID:** `PostAccountsAccountPersonsPerson`

<p>Updates an existing person.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account` | path | string | Yes |  |
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

