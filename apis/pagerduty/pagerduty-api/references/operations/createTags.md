# POST /tags

**Resource:** [Tags](../resources/Tags.md)
**Create a tag**
**Operation ID:** `createTags`

Create a Tag.

A Tag is applied to Escalation Policies, Teams or Users and can be used to filter them.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#tags)

Scoped OAuth requires: `tags.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The tag that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

