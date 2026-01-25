# GET /tags/{id}

**Resource:** [Tags](../resources/Tags.md)
**Get a tag**
**Operation ID:** `getTag`

Get details about an existing Tag.

A Tag is applied to Escalation Policies, Teams or Users and can be used to filter them.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#tags)

Scoped OAuth requires: `tags.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The tag requested. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

