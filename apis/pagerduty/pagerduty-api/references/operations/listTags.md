# GET /tags

**Resource:** [Tags](../resources/Tags.md)
**List tags**
**Operation ID:** `listTags`

List all of your account's tags.

A Tag is applied to Escalation Policies, Teams or Users and can be used to filter them.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#tags)

Scoped OAuth requires: `tags.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of tags names. |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

