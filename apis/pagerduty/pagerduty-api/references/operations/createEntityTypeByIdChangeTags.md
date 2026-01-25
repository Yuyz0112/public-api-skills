# POST /{entity_type}/{id}/change_tags

**Resource:** [Tags](../resources/Tags.md)
**Assign tags**
**Operation ID:** `createEntityTypeByIdChangeTags`

Assign existing or new tags.

A Tag is applied to Escalation Policies, Teams or Users and can be used to filter them.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#tags)

Scoped OAuth requires: `tags.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The tags were added and/or removed. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

