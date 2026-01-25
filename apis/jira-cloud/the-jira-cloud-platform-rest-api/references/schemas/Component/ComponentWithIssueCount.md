# ComponentWithIssueCount

Details about a component with a count of the issues it contains.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assignee` | any | No | The details of the user associated with `assigneeType`, if any. See `realAssignee` for details of the user assigned to issues created with this component. |
| `assigneeType` | enum: PROJECT_DEFAULT, COMPONENT_LEAD, PROJECT_LEAD... | No | The nominal user type used to determine the assignee for issues created with this component. See `realAssigneeType` for details on how the type of the user, and hence the user, assigned to issues is determined. Takes the following values:

 *  `PROJECT_LEAD` the assignee to any issues created with this component is nominally the lead for the project the component is in.
 *  `COMPONENT_LEAD` the assignee to any issues created with this component is nominally the lead for the component.
 *  `UNASSIGNED` an assignee is not set for issues created with this component.
 *  `PROJECT_DEFAULT` the assignee to any issues created with this component is nominally the default assignee for the project that the component is in. |
| `description` | string | No | The description for the component. |
| `id` | string | No | The unique identifier for the component. |
| `isAssigneeTypeValid` | boolean | No | Whether a user is associated with `assigneeType`. For example, if the `assigneeType` is set to `COMPONENT_LEAD` but the component lead is not set, then `false` is returned. |
| `issueCount` | integer (int64) | No | Count of issues for the component. |
| `lead` | any | No | The user details for the component's lead user. |
| `name` | string | No | The name for the component. |
| `project` | string | No | The key of the project to which the component is assigned. |
| `projectId` | integer (int64) | No | Not used. |
| `realAssignee` | any | No | The user assigned to issues created with this component, when `assigneeType` does not identify a valid assignee. |
| `realAssigneeType` | enum: PROJECT_DEFAULT, COMPONENT_LEAD, PROJECT_LEAD... | No | The type of the assignee that is assigned to issues created with this component, when an assignee cannot be set from the `assigneeType`. For example, `assigneeType` is set to `COMPONENT_LEAD` but no component lead is set. This property is set to one of the following values:

 *  `PROJECT_LEAD` when `assigneeType` is `PROJECT_LEAD` and the project lead has permission to be assigned issues in the project that the component is in.
 *  `COMPONENT_LEAD` when `assignee`Type is `COMPONENT_LEAD` and the component lead has permission to be assigned issues in the project that the component is in.
 *  `UNASSIGNED` when `assigneeType` is `UNASSIGNED` and Jira is configured to allow unassigned issues.
 *  `PROJECT_DEFAULT` when none of the preceding cases are true. |
| `self` | string (uri) | No | The URL for this count of the issues contained in the component. |

