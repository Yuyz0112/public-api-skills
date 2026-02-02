# GET /user/anonymization

**Resource:** [user](../resources/user.md)
**Operation ID:** `validateUserAnonymization`

Validates user anonymization process.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `userKey` | query | string | No | the key of the user to validate anonymization for. |
| `expand` | query | string | No | Parameter used to include parts of the response. This can be used to include: affectedEntities. Affected entities will only be returned if <code>expand=affectedEntities</code>. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

