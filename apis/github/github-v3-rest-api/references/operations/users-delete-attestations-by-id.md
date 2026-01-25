# DELETE /users/{username}/attestations/{attestation_id}

**Resource:** [users](../resources/users.md)
**Delete attestations by ID**
**Operation ID:** `users/delete-attestations-by-id`

Delete an artifact attestation by unique ID that is associated with a repository owned by a user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `attestation_id` | path | integer | Yes | Attestation ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 204 | Response |
| 403 | (reference) |
| 404 | (reference) |

