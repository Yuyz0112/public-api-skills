# DELETE /repos/{owner}/{repo}/git/refs/{ref}

**Resource:** [git](../resources/git.md)
**Delete a reference**
**Operation ID:** `git/delete-ref`

Deletes the provided reference.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 409 | (reference) |
| 422 | Validation failed, an attempt was made to delete the default branch, or the endpoint has been spammed. |

