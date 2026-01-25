# DELETE /users/{username}/attestations/digest/{subject_digest}

**Resource:** [users](../resources/users.md)
**Delete attestations by subject digest**
**Operation ID:** `users/delete-attestations-by-subject-digest`

Delete an artifact attestation by subject digest.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subject_digest` | path | string | Yes | Subject Digest |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 204 | Response |
| 404 | (reference) |

