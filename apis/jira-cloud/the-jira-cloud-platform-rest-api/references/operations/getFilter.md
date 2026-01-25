# GET /rest/api/3/filter/{id}

**Resource:** [Filters](../resources/Filters.md)
**Get filter**
**Operation ID:** `getFilter`

Returns a filter.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None, however, the filter is only returned where it is:

 *  owned by the user.
 *  shared with a group that the user is a member of.
 *  shared with a private project that the user has *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for.
 *  shared with a public project.
 *  shared with the public.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the filter to return. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about filter in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `sharedUsers` Returns the users that the filter is shared with. This includes users that can browse projects that the filter is shared with. If you don't specify `sharedUsers`, then the `sharedUsers` object is returned but it doesn't list any users. The list of users returned is limited to 1000, to access additional users append `[start-index:end-index]` to the expand request. For example, to access the next 1000 users, use `?expand=sharedUsers[1001:2000]`.
 *  `subscriptions` Returns the users that are subscribed to the filter. If you don't specify `subscriptions`, the `subscriptions` object is returned but it doesn't list any subscriptions. The list of subscriptions returned is limited to 1000, to access additional subscriptions append `[start-index:end-index]` to the expand request. For example, to access the next 1000 subscriptions, use `?expand=subscriptions[1001:2000]`. |
| `overrideSharePermissions` | query | boolean | No | EXPERIMENTAL: Whether share permissions are overridden to enable filters with any share permissions to be returned. Available to users with *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the filter is not found or the user does not have permission to view it. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[Filter](../schemas/Filter/Filter.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
