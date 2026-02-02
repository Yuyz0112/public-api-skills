# DELETE /user/anonymization/unlock

**Resource:** [user](../resources/user.md)
**Operation ID:** `unlockAnonymization`

Removes stale user anonymization task, for scenarios when the node that was executing it is no longer alive.
 <p>
 <strong>Use it only after making sure that the parent node of the task is actually down, and not just having
 connectivity issues.</strong>

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

