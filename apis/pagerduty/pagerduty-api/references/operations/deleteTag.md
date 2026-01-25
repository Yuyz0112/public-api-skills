# DELETE /tags/{id}

**Resource:** [Tags](../resources/Tags.md)
**Delete a tag**
**Operation ID:** `deleteTag`

Remove an existing Tag.

A Tag is applied to Escalation Policies, Teams or Users and can be used to filter them.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#tags)

Scoped OAuth requires: `tags.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The tag was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

