# ProjectTemplateInstantiateProjectRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the new project. |
| `team` | string | No | *Optional*. Sets the team of the new project. If the project template exists in an _organization_, you may specify a value for `team`. If no value is provided then it defaults to the same team as the project template. |
| `public` | boolean | No | *Deprecated:* new integrations use `privacy_setting` instead. |
| `privacy_setting` | enum: public_to_workspace, private_to_team, private | No | The privacy setting of the project. *Note: Administrators in your organization may restrict the values of `privacy_setting`.* The value `private_to_team` is deprecated. Use `POST /memberships` to share a project with a team after creation. |
| `is_strict` | boolean | No | *Optional*. If set to `true`, the endpoint returns an "Unprocessable Entity" error if you fail to provide a calendar date value for any date variable. If set to `false`, a default date is used for each unfulfilled date variable (e.g., the current date is used as the Start Date of a project). |
| `requested_dates` | DateVariableRequest[] | No | *Conditional*. Array of mappings of date variables to calendar dates. This property is required in the instantiation request if the project template includes dates (e.g., a start date on a task). |
| `requested_roles` | RequestedRoleRequest[] | No | Array of mappings of template roles to user ids |

