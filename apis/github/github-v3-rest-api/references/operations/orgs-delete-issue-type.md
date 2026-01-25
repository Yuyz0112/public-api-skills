# DELETE /orgs/{org}/issue-types/{issue_type_id}

**Resource:** [orgs](../resources/orgs.md)
**Delete issue type for an organization**
**Operation ID:** `orgs/delete-issue-type`

Deletes an issue type for an organization.

You can find out more about issue types in [Managing issue types in an organization](https://docs.github.com/issues/tracking-your-work-with-issues/configuring-issues/managing-issue-types-in-an-organization).

To use this endpoint, the authenticated user must be an administrator for the organization. OAuth app tokens and
personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |
| 422 | (reference) |

