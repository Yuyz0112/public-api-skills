# GET /{entity_type}/{id}/tags

**Resource:** [Tags](../resources/Tags.md)
**Get tags for entities**
**Operation ID:** `getEntityTypeByIdTags`

Get related tags for Users, Teams or Escalation Policies.

A Tag is applied to Escalation Policies, Teams or Users and can be used to filter them.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#tags)

Scoped OAuth requires: `tags.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of tags. |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

