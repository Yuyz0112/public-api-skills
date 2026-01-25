# GET /tags/{id}/{entity_type}

**Resource:** [Tags](../resources/Tags.md)
**Get connected entities**
**Operation ID:** `getTagsByEntityType`

Get related Users, Teams or Escalation Policies for the Tag.

A Tag is applied to Escalation Policies, Teams or Users and can be used to filter them.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#tags)

Scoped OAuth requires: `tags.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of connected entities. |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

