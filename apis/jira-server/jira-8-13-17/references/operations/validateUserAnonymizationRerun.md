# GET /user/anonymization/rerun

**Resource:** [user](../resources/user.md)
**Operation ID:** `validateUserAnonymizationRerun`

Validates user anonymization re-run process.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `userKey` | query | string | No | the key of the user to validate anonymization for |
| `oldUserKey` | query | string | No | user key before anonymization, only needed when current value is anonymized.
                    If there is no old key, e.g. because the user was already created
                    using the new key generation strategy, provide a value equal to the current key. |
| `oldUserName` | query | string | No | user name before anonymization, only needed when the current value is anonymized.
                    If there is no old name, provide a value equal to the current name. |
| `expand` | query | string | No | Parameter used to include parts of the response. This can be used to include: affectedEntities. Affected entities will only be returned if <code>expand=affectedEntities</code>. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

