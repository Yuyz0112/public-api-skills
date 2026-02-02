# POST /version/{id}/move

**Resource:** [version](../resources/version.md)
**Operation ID:** `moveVersion`

Modify a version's sequence within a project.
 <p/>
 The move version bean has 2 alternative field value pairs:
 <dl>
 <dt>position</dt><dd>An absolute position, which may have a value of 'First', 'Last', 'Earlier' or 'Later'</dd>
 <dt>after</dt><dd>A version to place this version after.  The value should be the self link of another version</dd>
 </dl>

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

