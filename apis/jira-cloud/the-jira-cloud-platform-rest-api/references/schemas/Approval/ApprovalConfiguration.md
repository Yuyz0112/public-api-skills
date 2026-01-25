# ApprovalConfiguration

The approval configuration of a status within a workflow. Applies only to Jira Service Management approvals.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | enum: true, false | Yes | Whether the approval configuration is active. |
| `conditionType` | enum: number, percent, numberPerPrincipal | Yes | How the required approval count is calculated. It may be configured to require a specific number of approvals, or approval by a percentage of approvers. If the approvers source field is Approver groups, you can configure how many approvals per group are required for the request to be approved. The number will be the same across all groups. |
| `conditionValue` | string | Yes | The number or percentage of approvals required for a request to be approved. If `conditionType` is `number`, the value must be 20 or less. If `conditionType` is `percent`, the value must be 100 or less. |
| `exclude` | string[] | No | A list of roles that should be excluded as possible approvers. |
| `fieldId` | string | Yes | The custom field ID of the "Approvers" or "Approver Groups" field. |
| `prePopulatedFieldId` | string | No | The custom field ID of the field used to pre-populate the Approver field. Only supports the "Affected Services" field. |
| `transitionApproved` | string | Yes | The numeric ID of the transition to be executed if the request is approved. |
| `transitionRejected` | string | Yes | The numeric ID of the transition to be executed if the request is declined. |

