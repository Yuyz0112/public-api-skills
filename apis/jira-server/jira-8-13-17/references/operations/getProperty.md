# GET /application-properties

**Resource:** [application-properties](../resources/application-properties.md)
**Operation ID:** `getProperty`

Returns an application property.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | query | string | No | a String containing the property key |
| `permissionLevel` | query | string | No | when fetching a list specifies the permission level of all items in the list
                        see {@link com.atlassian.jira.bc.admin.ApplicationPropertiesService.EditPermissionLevel} |
| `keyFilter` | query | string | No | when fetching a list allows the list to be filtered by the property's start of key
                        e.g. "jira.lf.*" whould fetch only those permissions that are editable and whose keys start with
                        "jira.lf.". This is a regex. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

