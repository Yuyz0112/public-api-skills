# GET /rest/api/3/workflows/capabilities

**Resource:** [Workflows](../resources/Workflows.md)
**Get available workflow capabilities**
**Operation ID:** `workflowCapabilities`

Get the list of workflow capabilities for a specific workflow using either the workflow ID, or the project and issue type ID pair. The response includes the scope of the workflow, defined as global/project-based, and a list of project types that the workflow is scoped to. It also includes all rules organised into their broad categories (conditions, validators, actions, triggers, screens) as well as the source location (Atlassian-provided, Connect, Forge).

**[Permissions](#permissions) required:**

 *  *Administer Jira* project permission to access all, including global-scoped, workflows
 *  *Administer projects* project permissions to access project-scoped workflows

The current list of Atlassian-provided rules:

#### Validators ####

A validator rule that checks if a user has the required permissions to execute the transition in the workflow.

##### Permission validator #####

A validator rule that checks if a user has the required permissions to execute the transition in the workflow.

    {
       "ruleKey": "system:check-permission-validator",
       "parameters": {
         "permissionKey": "ADMINISTER_PROJECTS"
       }
     }

Parameters:

 *  `permissionKey` The permission required to perform the transition. Allowed values: [built-in Jira permissions](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-permission-schemes/#built-in-permissions).

##### Parent or child blocking validator #####

A validator to block the child issue's transition depending on the parent issue's status.

    {
       "ruleKey" : "system:parent-or-child-blocking-validator"
       "parameters" : {
         "blocker" : "PARENT"
         "statusIds" : "1,2,3"
       }
     }

Parameters:

 *  `blocker` currently only supports `PARENT`.
 *  `statusIds` a comma-separated list of status IDs.

##### Previous status validator #####

A validator that checks if an issue has transitioned through specified previous status(es) before allowing the current transition to occur.

    {
       "ruleKey": "system:previous-status-validator",
       "parameters": {
         "previousStatusIds": "10014",
         "mostRecentStatusOnly": "true"
       }
     }

Parameters:

 *  `previousStatusIds` a comma-separated list of status IDs, currently only support one ID.
 *  `mostRecentStatusOnly` when `true` only considers the most recent status for the condition evaluation. Allowed values: `true`, `false`.

##### Validate a field value #####

A validation that ensures a specific field's value meets the defined criteria before allowing an issue to transition in the workflow.

Depending on the rule type, the result will vary:

###### Field required ######

    {
       "ruleKey": "system:validate-field-value",
       "parameters": {
         "ruleType": "fieldRequired",
         "fieldsRequired": "assignee",
         "ignoreContext": "true",
         "errorMessage": "An assignee must be set!"
       }
     }

Parameters:

 *  `fieldsRequired` the ID of the field that is required. For a custom field, it would look like `customfield_123`.
 *  `ignoreContext` controls the impact of context settings on field validation. When set to `true`, the validator doesn't check a required field if its context isn't configured for the current issue. When set to `false`, the validator requires a field even if its context is invalid. Allowed values: `true`, `false`.
 *  `errorMessage` is the error message to display if the user does not provide a value during the transition. A default error message will be shown if you don't provide one (Optional).

###### Field changed ######

    {
       "ruleKey": "system:validate-field-value",
       "parameters": {
         "ruleType": "fieldChanged",
         "groupsExemptFromValidation": "6862ac20-8672-4f68-896d-4854f5efb79e",
         "fieldKey": "versions",
         "errorMessage": "Affect versions must be modified before transition"
       }
     }

Parameters:

 *  `groupsExemptFromValidation` a comma-separated list of group IDs to be exempt from the validation.
 *  `fieldKey` the ID of the field that has changed. For a custom field, it would look like `customfield_123`.
 *  `errorMessage` the error message to display if the user does not provide a value during the transition. A default error message will be shown if you don't provide one (Optional).

###### Field has a single value ######

    {
       "ruleKey": "system:validate-field-value",
       "parameters": {
         "ruleType": "fieldHasSingleValue",
         "fieldKey": "created",
         "excludeSubtasks": "true"
       }
     }

Parameters:

 *  `fieldKey` the ID of the field to validate. For a custom field, it would look like `customfield_123`.
 *  `excludeSubtasks` Option to exclude values copied from sub-tasks. Allowed values: `true`, `false`.

###### Field matches regular expression ######

    {
       "ruleKey": "system:validate-field-value",
       "parameters": {
         "ruleType": "fieldMatchesRegularExpression",
         "regexp": "[0-9]{4}",
         "fieldKey": "description"
       }
     }

Parameters:

 *  `regexp` the regular expression used to validate the field\\u2019s content.
 *  `fieldKey` the ID of the field to validate. For a custom field, it would look like `customfield_123`.

###### Date field comparison ######

    {
       "ruleKey": "system:validate-field-value",
       "parameters": {
         "ruleType": "dateFieldComparison",
         "date1FieldKey": "duedate",
         "date2FieldKey": "customfield_10054",
         "includeTime": "true",
         "conditionSelected": ">="
       }
     }

Parameters:

 *  `date1FieldKey` the ID of the first field to compare. For a custom field, it would look like `customfield_123`.
 *  `date2FieldKey` the ID of the second field to compare. For a custom field, it would look like `customfield_123`.
 *  `includeTime` if `true`, compares both date and time. Allowed values: `true`, `false`.
 *  `conditionSelected` the condition to compare with. Allowed values: `>`, `>=`, `=`, `<=`, `<`, `!=`.

###### Date range comparison ######

    {
       "ruleKey": "system:validate-field-value",
       "parameters": {
         "ruleType": "windowDateComparison",
         "date1FieldKey": "customfield_10009",
         "date2FieldKey": "customfield_10054",
         "numberOfDays": "3"
       }
     }

Parameters:

 *  `date1FieldKey` the ID of the first field to compare. For a custom field, it would look like `customfield_123`.
 *  `date2FieldKey` the ID of the second field to compare. For a custom field, it would look like `customfield_123`.
 *  `numberOfDays` maximum number of days past the reference date (`date2FieldKey`) to pass validation.

This rule is composed by aggregating the following legacy rules:

 *  FieldRequiredValidator
 *  FieldChangedValidator
 *  FieldHasSingleValueValidator
 *  RegexpFieldValidator
 *  DateFieldValidator
 *  WindowsDateValidator

##### Pro forma: Forms attached validator #####

Validates that one or more forms are attached to the issue.

    {
       "ruleKey" : "system:proforma-forms-attached"
       "parameters" : {}
     }

##### Proforma: Forms submitted validator #####

Validates that all forms attached to the issue have been submitted.

    {
       "ruleKey" : "system:proforma-forms-submitted"
       "parameters" : {}
     }

#### Conditions ####

Conditions enable workflow rules that govern whether a transition can execute.

##### Check field value #####

A condition rule evaluates as true if a specific field's value meets the defined criteria. This rule ensures that an issue can only transition to the next step in the workflow if the field's value matches the desired condition.

    {
       "ruleKey": "system:check-field-value",
       "parameters": {
         "fieldId": "description",
         "fieldValue": "[\"Done\"]",
         "comparator": "=",
         "comparisonType": "STRING"
       }
     }

Parameters:

 *  `fieldId` The ID of the field to check the value of. For non-system fields, it will look like `customfield_123`. Note: `fieldId` is used interchangeably with the idea of `fieldKey` here, they refer to the same field.
 *  `fieldValue` the list of values to check against the field\\u2019s value.
 *  `comparator` The comparison logic. Allowed values: `>`, `>=`, `=`, `<=`, `<`, `!=`.
 *  `comparisonType` The type of data being compared. Allowed values: `STRING`, `NUMBER`, `DATE`, `DATE_WITHOUT_TIME`, `OPTIONID`.

##### Restrict issue transition #####

This rule ensures that issue transitions are restricted based on user accounts, roles, group memberships, and permissions, maintaining control over who can transition an issue. This condition evaluates as `true` if any of the following criteria is met.

    {
       "ruleKey": "system:restrict-issue-transition",
       "parameters": {
         "accountIds": "allow-reporter,5e68ac137d64450d01a77fa0",
         "roleIds": "10002,10004",
         "groupIds": "703ff44a-7dc8-4f4b-9aa6-a65bf3574fa4",
         "permissionKeys": "ADMINISTER_PROJECTS",
         "groupCustomFields": "customfield_10028",
         "allowUserCustomFields": "customfield_10072,customfield_10144,customfield_10007",
         "denyUserCustomFields": "customfield_10107"
       }
     }

Parameters:

 *  `accountIds` a comma-separated list of the user account IDs. It also allows generic values like: `allow-assignee`, `allow-reporter`, and `accountIds` Note: This is only supported in team-managed projects
 *  `roleIds` a comma-separated list of role IDs.
 *  `groupIds` a comma-separated list of group IDs.
 *  `permissionKeys` a comma-separated list of permission keys. Allowed values: [built-in Jira permissions](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-permission-schemes/#built-in-permissions).
 *  `groupCustomFields` a comma-separated list of group custom field IDs.
 *  `allowUserCustomFields` a comma-separated list of user custom field IDs to allow for issue transition.
 *  `denyUserCustomFields` a comma-separated list of user custom field IDs to deny for issue transition.

This rule is composed by aggregating the following legacy rules:

 *  AllowOnlyAssignee
 *  AllowOnlyReporter
 *  InAnyProjectRoleCondition
 *  InProjectRoleCondition
 *  UserInAnyGroupCondition
 *  UserInGroupCondition
 *  PermissionCondtion
 *  InGroupCFCondition
 *  UserIsInCustomFieldCondition

##### Previous status condition #####

A condition that evaluates based on an issue's previous status(es) and specific criteria.

    {
       "ruleKey" : "system:previous-status-condition"
       "parameters" : {
         "previousStatusIds" : "10004",
         "not": "true",
         "mostRecentStatusOnly" : "true",
         "includeCurrentStatus": "true",
         "ignoreLoopTransitions": "true"
       }
     }

Parameters:

 *  `previousStatusIds` a comma-separated list of status IDs, current only support one ID.
 *  `not` indicates if the condition should be reversed. When `true` it checks that the issue has not been in the selected statuses. Allowed values: `true`, `false`.
 *  `mostRecentStatusOnly` when true only considers the most recent status for the condition evaluation. Allowed values: `true`, `false`.
 *  `includeCurrentStatus` includes the current status when evaluating if the issue has been through the selected statuses. Allowed values: `true`, `false`.
 *  `ignoreLoopTransitions` ignore loop transitions. Allowed values: `true`, `false`.

##### Parent or child blocking condition #####

A condition to block the parent\\u2019s issue transition depending on the child\\u2019s issue status.

    {
       "ruleKey" : "system:parent-or-child-blocking-condition"
       "parameters" : {
         "blocker" : "CHILD",
         "statusIds" : "1,2,3"
       }
     }

Parameters:

 *  `blocker` currently only supports `CHILD`.
 *  `statusIds` a comma-separated list of status IDs.

##### Separation of duties #####

A condition preventing the user from performing, if the user has already performed a transition on the issue.

    {
       "ruleKey": "system:separation-of-duties",
       "parameters": {
         "fromStatusId": "10161",
         "toStatusId": "10160"
       }
     }

Parameters:

 *  `fromStatusId` represents the status ID from which the issue is transitioning. It ensures that the user performing the current transition has not performed any actions when the issue was in the specified status.
 *  `toStatusId` represents the status ID to which the issue is transitioning. It ensures that the user performing the current transition is not the same user who has previously transitioned the issue.

##### Restrict transitions #####

A condition preventing all users from transitioning the issue can also optionally include APIs as well.

    {
       "ruleKey": "system:restrict-from-all-users",
       "parameters": {
         "restrictMode": "users"
       }
     }

Parameters:

 *  `restrictMode` restricts the issue transition including/excluding APIs. Allowed values: `"users"`, `"usersAndAPI"`.

##### Jira Service Management block until approved #####

Block an issue transition until approval. Note: This is only supported in team-managed projects.

    {
       "ruleKey": "system:jsd-approvals-block-until-approved",
       "parameters": {
         "approvalConfigurationJson": "{"statusExternalUuid...}"
       }
     }

Parameters:

 *  `approvalConfigurationJson` a stringified JSON holding the Jira Service Management approval configuration.

##### Jira Service Management block until rejected #####

Block an issue transition until rejected. Note: This is only supported in team-managed projects.

    {
       "ruleKey": "system:jsd-approvals-block-until-rejected",
       "parameters": {
         "approvalConfigurationJson": "{"statusExternalUuid...}"
       }
     }

Parameters:

 *  `approvalConfigurationJson` a stringified JSON holding the Jira Service Management approval configuration.

##### Block in progress approval #####

Condition to block issue transition if there is pending approval. Note: This is only supported in company-managed projects.

    {
       "ruleKey": "system:block-in-progress-approval",
       "parameters": {}
     }

#### Post functions ####

Post functions carry out any additional processing required after a workflow transition is executed.

##### Change assignee #####

A post function rule that changes the assignee of an issue after a transition.

    {
       "ruleKey": "system:change-assignee",
       "parameters": {
         "type": "to-selected-user",
         "accountId": "example-account-id"
       }
     }

Parameters:

 *  `type` the parameter used to determine the new assignee. Allowed values: `to-selected-user`, `to-unassigned`, `to-current-user`, `to-current-user`, `to-default-user`, `to-default-user`
 *  `accountId` the account ID of the user to assign the issue to. This parameter is required only when the type is `"to-selected-user"`.

##### Copy field value #####

A post function that automates the process of copying values between fields during a specific transition, ensuring data consistency and reducing manual effort.

    {
       "ruleKey": "system:copy-value-from-other-field",
       "parameters": {
         "sourceFieldKey": "description",
         "targetFieldKey": "components",
         "issueSource": "SAME"
       }
     }

Parameters:

 *  `sourceFieldKey` the field key to copy from. For a custom field, it would look like `customfield_123`
 *  `targetFieldKey` the field key to copy to. For a custom field, it would look like `customfield_123`
 *  `issueSource` `SAME` or `PARENT`. Defaults to `SAME` if no value is provided.

##### Update field #####

A post function that updates or appends a specific field with the given value.

    {
       "ruleKey": "system:update-field",
       "parameters": {
         "field": "customfield_10056",
         "value": "asdf",
         "mode": "append"
       }
     }

Parameters:

 *  `field` the ID of the field to update. For a custom field, it would look like `customfield_123`
 *  `value` the value to update the field with.
 *  `mode` `append` or `replace`. Determines if a value will be appended to the current value, or if the current value will be replaced.

##### Trigger webhook #####

A post function that automatically triggers a predefined webhook when a transition occurs in the workflow.

    {
       "ruleKey": "system:trigger-webhook",
       "parameters": {
         "webhookId": "1"
       }
     }

Parameters:

 *  `webhookId` the ID of the webhook.

#### Screen ####

##### Remind people to update fields #####

A screen rule that prompts users to update a specific field when they interact with an issue screen during a transition. This rule is useful for ensuring that users provide or modify necessary information before moving an issue to the next step in the workflow.

    {
       "ruleKey": "system:remind-people-to-update-fields",
       "params": {
         "remindingFieldIds": "assignee,customfield_10025",
         "remindingMessage": "The message",
         "remindingAlwaysAsk": "true"
       }
     }

Parameters:

 *  `remindingFieldIds` a comma-separated list of field IDs. Note: `fieldId` is used interchangeably with the idea of `fieldKey` here, they refer to the same field.
 *  `remindingMessage` the message to display when prompting the users to update the fields.
 *  `remindingAlwaysAsk` always remind to update fields. Allowed values: `true`, `false`.

##### Shared transition screen #####

A common screen that is shared between transitions in a workflow.

    {
       "ruleKey": "system:transition-screen",
       "params": {
         "screenId": "3"
       }
     }

Parameters:

 *  `screenId` the ID of the screen.

#### Connect & Forge ####

##### Connect rules #####

Validator/Condition/Post function for Connect app.

    {
       "ruleKey": "connect:expression-validator",
       "parameters": {
         "appKey": "com.atlassian.app",
         "config": "",
         "id": "90ce590f-e90c-4cd3-8281-165ce41f2ac3",
         "disabled": "false",
         "tag": ""
       }
     }

Parameters:

 *  `ruleKey` Validator: `connect:expression-validator`, Condition: `connect:expression-condition`, and Post function: `connect:remote-workflow-function`
 *  `appKey` the reference to the Connect app
 *  `config` a JSON payload string describing the configuration
 *  `id` the ID of the rule
 *  `disabled` determine if the Connect app is disabled. Allowed values: `true`, `false`.
 *  `tag` additional tags for the Connect app

##### Forge rules #####

Validator/Condition/Post function for Forge app.

    {
       "ruleKey": "forge:expression-validator",
       "parameters": {
         "key": "ari:cloud:ecosystem::extension/{appId}/{environmentId}/static/{moduleKey}",
         "config": "{"searchString":"workflow validator"}",
         "id": "a865ddf6-bb3f-4a7b-9540-c2f8b3f9f6c2",
         "disabled": "false",
         "tag": ""
       }
     }

Parameters:

 *  `ruleKey` Validator: `forge:expression-validator`, Condition: `forge:expression-condition`, and Post function: `forge:workflow-post-function`
 *  `key` the identifier for the Forge app
 *  `config` the persistent stringified JSON configuration for the Forge rule
 *  `id` the ID of the Forge rule
 *  `disabled` determine if the Forge app is disabled. Allowed values: `true`, `false`.
 *  `tag` additional tags for the Forge app

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflowId` | query | string | No |  |
| `projectId` | query | string | No |  |
| `issueTypeId` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

**Success Response Schema:**

[WorkflowCapabilities](../schemas/Workflow/WorkflowCapabilities.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
