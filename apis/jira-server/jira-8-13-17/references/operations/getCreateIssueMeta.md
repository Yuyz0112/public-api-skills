# GET /issue/createmeta

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `getCreateIssueMeta`

Returns the meta data for creating issues. This includes the available projects, issue types and fields,
 including field types and whether or not those fields are required.
 Projects will not be returned if the user does not have permission to create issues in that project.
 <p/>
 The fields in the createmeta correspond to the fields in the create screen for the project/issuetype.
 Fields not in the screen will not be in the createmeta.
 <p/>
 Fields will only be returned if <code>expand=projects.issuetypes.fields</code>.
 <p/>
 The results can be filtered by project and/or issue type, given by the query params.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIds` | query | string | No | combined with the projectKeys param, lists the projects with which to filter the results. If absent, all projects are returned.
                       This parameter can be specified multiple times, and/or be a comma-separated list.
                       Specifiying a project that does not exist (or that you cannot create issues in) is not an error, but it will not be in the results. |
| `projectKeys` | query | string | No | combined with the projectIds param, lists the projects with which to filter the results. If null, all projects are returned.
                       This parameter can be specified multiple times, and/or be a comma-separated list.
                       Specifiying a project that does not exist (or that you cannot create issues in) is not an error, but it will not be in the results. |
| `issuetypeIds` | query | string | No | combinded with issuetypeNames, lists the issue types with which to filter the results. If null, all issue types are returned.
                       This parameter can be specified multiple times, and/or be a comma-separated list.
                       Specifiying an issue type that does not exist is not an error. |
| `issuetypeNames` | query | string | No | combinded with issuetypeIds, lists the issue types with which to filter the results. If null, all issue types are returned.
                       This parameter can be specified multiple times, but is NOT interpreted as a comma-separated list.
                       Specifiying an issue type that does not exist is not an error. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

