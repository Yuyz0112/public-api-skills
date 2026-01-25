# POST /rest/api/3/filter

**Resource:** [Filters](../resources/Filters.md)
**Create filter**
**Operation ID:** `createFilter`

Creates a filter. The filter is shared according to the [default share scope](#api-rest-api-3-filter-post). The filter is not selected as a favorite.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about filter in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `sharedUsers` Returns the users that the filter is shared with. This includes users that can browse projects that the filter is shared with. If you don't specify `sharedUsers`, then the `sharedUsers` object is returned but it doesn't list any users. The list of users returned is limited to 1000, to access additional users append `[start-index:end-index]` to the expand request. For example, to access the next 1000 users, use `?expand=sharedUsers[1001:2000]`.
 *  `subscriptions` Returns the users that are subscribed to the filter. If you don't specify `subscriptions`, the `subscriptions` object is returned but it doesn't list any subscriptions. The list of subscriptions returned is limited to 1000, to access additional subscriptions append `[start-index:end-index]` to the expand request. For example, to access the next 1000 subscriptions, use `?expand=subscriptions[1001:2000]`. |
| `overrideSharePermissions` | query | boolean | No | EXPERIMENTAL: Whether share permissions are overridden to enable filters with any share permissions to be created. Available to users with *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). |

## Request Body

The filter to create.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [Filter](../schemas/Filter/Filter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request object is invalid. For example, the `name` is not unique or the project ID is not specified for a project role share permission. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[Filter](../schemas/Filter/Filter.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
