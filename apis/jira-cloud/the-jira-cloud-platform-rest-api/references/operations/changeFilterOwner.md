# PUT /rest/api/3/filter/{id}/owner

**Resource:** [Filters](../resources/Filters.md)
**Change filter owner**
**Operation ID:** `changeFilterOwner`

Changes the owner of the filter.

**[Permissions](#permissions) required:** Permission to access Jira. However, the user must own the filter or have the *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the filter to update. |

## Request Body

The account ID of the new owner of the filter.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ChangeFilterOwner](../schemas/Change/ChangeFilterOwner.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned when:

 *  The new owner of the filter owns a filter with the same name.
 *  An attempt is made to change owner of the default filter. |
| 403 | Returned if the requesting user is not an owner of the filter or does not have *Administer Jira* global permission. |
| 404 | Returned if the filter or the new owner of the filter is not found. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
