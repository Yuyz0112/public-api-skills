# DELETE /api/v4/groups/{id}/wikis/{slug}

**Resource:** [Wikis](../resources/Wikis.md)
**Delete a wiki page**
**Operation ID:** `deleteApiV4GroupsIdWikisSlug`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slug` | path | string | Yes | The slug of a wiki page |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Validation error |
| 404 | Not found |

