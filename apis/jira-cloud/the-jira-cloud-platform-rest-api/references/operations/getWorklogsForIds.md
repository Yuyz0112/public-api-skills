# POST /rest/api/3/worklog/list

**Resource:** [Issue worklogs](../resources/Issue-worklogs.md)
**Get worklogs**
**Operation ID:** `getWorklogsForIds`

Returns worklog details for a list of worklog IDs.

The returned list of worklogs is limited to 1000 items.

**[Permissions](#permissions) required:** Permission to access Jira, however, worklogs are only returned where either of the following is true:

 *  the worklog is set as *Viewable by All Users*.
 *  the user is a member of a project role or group with permission to view the worklog.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about worklogs in the response. This parameter accepts `properties` that returns the properties of each worklog. |

## Request Body

A JSON object containing a list of worklog IDs.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorklogIdsRequestBean](../schemas/Worklog/WorklogIdsRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request contains more than 1000 worklog IDs or is empty. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

Array of [Worklog](../schemas/Worklog/Worklog.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
