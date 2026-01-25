# PUT /rest/api/3/filter/{id}/favourite

**Resource:** [Filters](../resources/Filters.md)
**Add filter as favorite**
**Operation ID:** `setFavouriteForFilter`

Add a filter as a favorite for the user.

**[Permissions](#permissions) required:** Permission to access Jira, however, the user can only favorite:

 *  filters owned by the user.
 *  filters shared with a group that the user is a member of.
 *  filters shared with a private project that the user has *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for.
 *  filters shared with a public project.
 *  filters shared with the public.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the filter. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about filter in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `sharedUsers` Returns the users that the filter is shared with. This includes users that can browse projects that the filter is shared with. If you don't specify `sharedUsers`, then the `sharedUsers` object is returned but it doesn't list any users. The list of users returned is limited to 1000, to access additional users append `[start-index:end-index]` to the expand request. For example, to access the next 1000 users, use `?expand=sharedUsers[1001:2000]`.
 *  `subscriptions` Returns the users that are subscribed to the filter. If you don't specify `subscriptions`, the `subscriptions` object is returned but it doesn't list any subscriptions. The list of subscriptions returned is limited to 1000, to access additional subscriptions append `[start-index:end-index]` to the expand request. For example, to access the next 1000 subscriptions, use `?expand=subscriptions[1001:2000]`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  the filter is not found.
 *  the user does not have permission to favorite the filter. |

**Success Response Schema:**

[Filter](../schemas/Filter/Filter.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
