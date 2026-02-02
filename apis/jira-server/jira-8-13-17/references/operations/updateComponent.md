# PUT /component/{id}

**Resource:** [component](../resources/component.md)
**Operation ID:** `updateComponent`

Modify a component via PUT. Any fields present in the PUT will override existing values. As a convenience, if a field
 is not present, it is silently ignored.
 <p>
 If leadUserName is an empty string ("") the component lead will be removed.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

