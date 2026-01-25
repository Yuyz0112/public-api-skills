# GET /rest/api/3/field

**Resource:** [Issue fields](../resources/Issue-fields.md)
**Get fields**
**Operation ID:** `getFields`

Returns system and custom issue fields according to the following rules:

 *  Fields that cannot be added to the issue navigator are always returned.
 *  Fields that cannot be placed on an issue screen are always returned.
 *  Fields that depend on global Jira settings are only returned if the setting is enabled. That is, timetracking fields, subtasks, votes, and watches.
 *  For all other fields, this operation only returns the fields that the user has permission to view (that is, the field is used in at least one project that the user has *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for.)

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

Array of [FieldDetails](../schemas/Field/FieldDetails.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
