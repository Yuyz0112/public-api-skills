# PUT /myself

**Resource:** [myself](../resources/myself.md)
**Operation ID:** `updateUser`

Modify currently logged user. The "value" fields present will override the existing value.
 Fields skipped in request will not be changed. Only email and display name can be change that way.
 Requires user password.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

