# POST /rest/api/3/workflow

**Resource:** [Workflows](../resources/Workflows.md)
**Create workflow**
**Operation ID:** `createWorkflow`
⚠️ **Deprecated**

This will be removed on [February 1, 2026](https://developer.atlassian.com/cloud/jira/platform/changelog/#CHANGE-2568); use [Bulk create workflows](#api-rest-api-3-workflows-create-post) to create both team and company-managed scoped workflows.

Creates a workflow. You can define transition rules using the shapes detailed in the following sections. If no transitional rules are specified the default system transition rules are used. Note: This only applies to company-managed scoped workflows.

#### Conditions ####

Conditions enable workflow rules that govern whether a transition can execute.

##### Always false condition #####

A condition that always fails.

    {
       "type": "AlwaysFalseCondition"
     }

##### Block transition until approval #####

A condition that blocks issue transition if there is a pending approval.

    {
       "type": "BlockInProgressApprovalCondition"
     }

##### Compare number custom field condition #####

A condition that allows transition if a comparison between a number custom field and a value is true.

    {
       "type": "CompareNumberCFCondition",
       "configuration": {
         "comparator": "=",
         "fieldId": "customfield_10029",
         "fieldValue": 2
       }
     }

 *  `comparator` One of the supported comparator: `=`, `>`, and `<`.
 *  `fieldId` The custom numeric field ID. Allowed field types:
    
     *  `com.atlassian.jira.plugin.system.customfieldtypes:float`
     *  `com.pyxis.greenhopper.jira:jsw-story-points`
 *  `fieldValue` The value for comparison.

##### Hide from user condition #####

A condition that hides a transition from users. The transition can only be triggered from a workflow function or REST API operation.

    {
       "type": "RemoteOnlyCondition"
     }

##### Only assignee condition #####

A condition that allows only the assignee to execute a transition.

    {
       "type": "AllowOnlyAssignee"
     }

##### Only Bamboo notifications workflow condition (deprecated) #####

A condition that makes the transition available only to Bamboo build notifications.

    {
       "type": "OnlyBambooNotificationsCondition"
     }

##### Only reporter condition #####

A condition that allows only the reporter to execute a transition.

    {
       "type": "AllowOnlyReporter"
     }

##### Permission condition #####

A condition that allows only users with a permission to execute a transition.

    {
       "type": "PermissionCondition",
       "configuration": {
           "permissionKey": "BROWSE_PROJECTS"
       }
     }

 *  `permissionKey` The permission required to perform the transition. Allowed values: [built-in](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-permission-schemes/#built-in-permissions) or app defined permissions.

##### Previous status condition #####

A condition that allows a transition based on whether an issue has or has not transitioned through a status.

    {
       "type": "PreviousStatusCondition",
       "configuration": {
         "ignoreLoopTransitions": true,
         "includeCurrentStatus": true,
         "mostRecentStatusOnly": true,
         "reverseCondition": true,
         "previousStatus": {
           "id": "5"
         }
       }
     }

By default this condition allows the transition if the status, as defined by its ID in the `previousStatus` object, matches any previous issue status, unless:

 *  `ignoreLoopTransitions` is `true`, then loop transitions (from and to the same status) are ignored.
 *  `includeCurrentStatus` is `true`, then the current issue status is also checked.
 *  `mostRecentStatusOnly` is `true`, then only the issue's preceding status (the one immediately before the current status) is checked.
 *  `reverseCondition` is `true`, then the status must not be present.

##### Separation of duties condition #####

A condition that prevents a user to perform the transition, if the user has already performed a transition on the issue.

    {
       "type": "SeparationOfDutiesCondition",
       "configuration": {
         "fromStatus": {
           "id": "5"
         },
         "toStatus": {
           "id": "6"
         }
       }
     }

 *  `fromStatus` OPTIONAL. An object containing the ID of the source status of the transition that is blocked. If omitted any transition to `toStatus` is blocked.
 *  `toStatus` An object containing the ID of the target status of the transition that is blocked.

##### Subtask blocking condition #####

A condition that blocks transition on a parent issue if any of its subtasks are in any of one or more statuses.

    {
       "type": "SubTaskBlockingCondition",
       "configuration": {
         "statuses": [
           {
             "id": "1"
           },
           {
             "id": "3"
           }
         ]
       }
     }

 *  `statuses` A list of objects containing status IDs.

##### User is in any group condition #####

A condition that allows users belonging to any group from a list of groups to execute a transition.

    {
       "type": "UserInAnyGroupCondition",
       "configuration": {
         "groups": [
           "administrators",
           "atlassian-addons-admin"
         ]
       }
     }

 *  `groups` A list of group names.

##### User is in any project role condition #####

A condition that allows only users with at least one project roles from a list of project roles to execute a transition.

    {
       "type": "InAnyProjectRoleCondition",
       "configuration": {
         "projectRoles": [
           {
             "id": "10002"
           },
           {
             "id": "10003"
           },
           {
             "id": "10012"
           },
           {
             "id": "10013"
           }
         ]
       }
     }

 *  `projectRoles` A list of objects containing project role IDs.

##### User is in custom field condition #####

A condition that allows only users listed in a given custom field to execute the transition.

    {
       "type": "UserIsInCustomFieldCondition",
       "configuration": {
         "allowUserInField": false,
         "fieldId": "customfield_10010"
       }
     }

 *  `allowUserInField` If `true` only a user who is listed in `fieldId` can perform the transition, otherwise, only a user who is not listed in `fieldId` can perform the transition.
 *  `fieldId` The ID of the field containing the list of users.

##### User is in group condition #####

A condition that allows users belonging to a group to execute a transition.

    {
       "type": "UserInGroupCondition",
       "configuration": {
         "group": "administrators"
       }
     }

 *  `group` The name of the group.

##### User is in group custom field condition #####

A condition that allows users belonging to a group specified in a custom field to execute a transition.

    {
       "type": "InGroupCFCondition",
       "configuration": {
         "fieldId": "customfield_10012"
       }
     }

 *  `fieldId` The ID of the field. Allowed field types:
    
     *  `com.atlassian.jira.plugin.system.customfieldtypes:multigrouppicker`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:grouppicker`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:select`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:multiselect`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:radiobuttons`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:multicheckboxes`
     *  `com.pyxis.greenhopper.jira:gh-epic-status`

##### User is in project role condition #####

A condition that allows users with a project role to execute a transition.

    {
       "type": "InProjectRoleCondition",
       "configuration": {
         "projectRole": {
           "id": "10002"
         }
       }
     }

 *  `projectRole` An object containing the ID of a project role.

##### Value field condition #####

A conditions that allows a transition to execute if the value of a field is equal to a constant value or simply set.

    {
       "type": "ValueFieldCondition",
       "configuration": {
         "fieldId": "assignee",
         "fieldValue": "qm:6e1ecee6-8e64-4db6-8c85-916bb3275f51:54b56885-2bd2-4381-8239-78263442520f",
         "comparisonType": "NUMBER",
         "comparator": "="
       }
     }

 *  `fieldId` The ID of a field used in the comparison.
 *  `fieldValue` The expected value of the field.
 *  `comparisonType` The type of the comparison. Allowed values: `STRING`, `NUMBER`, `DATE`, `DATE_WITHOUT_TIME`, or `OPTIONID`.
 *  `comparator` One of the supported comparator: `>`, `>=`, `=`, `<=`, `<`, `!=`.

**Notes:**

 *  If you choose the comparison type `STRING`, only `=` and `!=` are valid options.
 *  You may leave `fieldValue` empty when comparison type is `!=` to indicate that a value is required in the field.
 *  For date fields without time format values as `yyyy-MM-dd`, and for those with time as `yyyy-MM-dd HH:mm`. For example, for July 16 2021 use `2021-07-16`, for 8:05 AM use `2021-07-16 08:05`, and for 4 PM: `2021-07-16 16:00`.

#### Validators ####

Validators check that any input made to the transition is valid before the transition is performed.

##### Date field validator #####

A validator that compares two dates.

    {
       "type": "DateFieldValidator",
       "configuration": {
           "comparator": ">",
           "date1": "updated",
           "date2": "created",
           "expression": "1d",
           "includeTime": true
         }
     }

 *  `comparator` One of the supported comparator: `>`, `>=`, `=`, `<=`, `<`, or `!=`.
 *  `date1` The date field to validate. Allowed field types:
    
     *  `com.atlassian.jira.plugin.system.customfieldtypes:datepicker`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:datetime`
     *  `com.atlassian.jpo:jpo-custom-field-baseline-end`
     *  `com.atlassian.jpo:jpo-custom-field-baseline-start`
     *  `duedate`
     *  `created`
     *  `updated`
     *  `resolutiondate`
 *  `date2` The second date field. Required, if `expression` is not passed. Allowed field types:
    
     *  `com.atlassian.jira.plugin.system.customfieldtypes:datepicker`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:datetime`
     *  `com.atlassian.jpo:jpo-custom-field-baseline-end`
     *  `com.atlassian.jpo:jpo-custom-field-baseline-start`
     *  `duedate`
     *  `created`
     *  `updated`
     *  `resolutiondate`
 *  `expression` An expression specifying an offset. Required, if `date2` is not passed. Offsets are built with a number, with `-` as prefix for the past, and one of these time units: `d` for day, `w` for week, `m` for month, or `y` for year. For example, -2d means two days into the past and 1w means one week into the future. The `now` keyword enables a comparison with the current date.
 *  `includeTime` If `true`, then the time part of the data is included for the comparison. If the field doesn't have a time part, 00:00:00 is used.

##### Windows date validator #####

A validator that checks that a date falls on or after a reference date and before or on the reference date plus a number of days.

    {
       "type": "WindowsDateValidator",
       "configuration": {
           "date1": "customfield_10009",
           "date2": "created",
           "windowsDays": 5
         }
     }

 *  `date1` The date field to validate. Allowed field types:
    
     *  `com.atlassian.jira.plugin.system.customfieldtypes:datepicker`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:datetime`
     *  `com.atlassian.jpo:jpo-custom-field-baseline-end`
     *  `com.atlassian.jpo:jpo-custom-field-baseline-start`
     *  `duedate`
     *  `created`
     *  `updated`
     *  `resolutiondate`
 *  `date2` The reference date. Allowed field types:
    
     *  `com.atlassian.jira.plugin.system.customfieldtypes:datepicker`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:datetime`
     *  `com.atlassian.jpo:jpo-custom-field-baseline-end`
     *  `com.atlassian.jpo:jpo-custom-field-baseline-start`
     *  `duedate`
     *  `created`
     *  `updated`
     *  `resolutiondate`
 *  `windowsDays` A positive integer indicating a number of days.

##### Field required validator #####

A validator that checks fields are not empty. By default, if a field is not included in the current context it's ignored and not validated.

    {
         "type": "FieldRequiredValidator",
         "configuration": {
             "ignoreContext": true,
             "errorMessage": "Hey",
             "fieldIds": [
                 "versions",
                 "customfield_10037",
                 "customfield_10003"
             ]
         }
     }

 *  `ignoreContext` If `true`, then the context is ignored and all the fields are validated.
 *  `errorMessage` OPTIONAL. The error message displayed when one or more fields are empty. A default error message is shown if an error message is not provided.
 *  `fieldIds` The list of fields to validate.

##### Field changed validator #####

A validator that checks that a field value is changed. However, this validation can be ignored for users from a list of groups.

    {
         "type": "FieldChangedValidator",
         "configuration": {
             "fieldId": "comment",
             "errorMessage": "Hey",
             "exemptedGroups": [
                 "administrators",
                 "atlassian-addons-admin"
             ]
         }
     }

 *  `fieldId` The ID of a field.
 *  `errorMessage` OPTIONAL. The error message displayed if the field is not changed. A default error message is shown if the error message is not provided.
 *  `exemptedGroups` OPTIONAL. The list of groups.

##### Field has single value validator #####

A validator that checks that a multi-select field has only one value. Optionally, the validation can ignore values copied from subtasks.

    {
         "type": "FieldHasSingleValueValidator",
         "configuration": {
             "fieldId": "attachment,
             "excludeSubtasks": true
         }
     }

 *  `fieldId` The ID of a field.
 *  `excludeSubtasks` If `true`, then values copied from subtasks are ignored.

##### Parent status validator #####

A validator that checks the status of the parent issue of a subtask. Ìf the issue is not a subtask, no validation is performed.

    {
         "type": "ParentStatusValidator",
         "configuration": {
             "parentStatuses": [
                 {
                   "id":"1"
                 },
                 {
                   "id":"2"
                 }
             ]
         }
     }

 *  `parentStatus` The list of required parent issue statuses.

##### Permission validator #####

A validator that checks the user has a permission.

    {
       "type": "PermissionValidator",
       "configuration": {
           "permissionKey": "ADMINISTER_PROJECTS"
       }
     }

 *  `permissionKey` The permission required to perform the transition. Allowed values: [built-in](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-permission-schemes/#built-in-permissions) or app defined permissions.

##### Previous status validator #####

A validator that checks if the issue has held a status.

    {
       "type": "PreviousStatusValidator",
       "configuration": {
           "mostRecentStatusOnly": false,
           "previousStatus": {
               "id": "15"
           }
       }
     }

 *  `mostRecentStatusOnly` If `true`, then only the issue's preceding status (the one immediately before the current status) is checked.
 *  `previousStatus` An object containing the ID of an issue status.

##### Regular expression validator #####

A validator that checks the content of a field against a regular expression.

    {
       "type": "RegexpFieldValidator",
       "configuration": {
           "regExp": "[0-9]",
           "fieldId": "customfield_10029"
       }
     }

 *  `regExp`A regular expression.
 *  `fieldId` The ID of a field. Allowed field types:
    
     *  `com.atlassian.jira.plugin.system.customfieldtypes:select`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:multiselect`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:radiobuttons`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:multicheckboxes`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:textarea`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:textfield`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:url`
     *  `com.atlassian.jira.plugin.system.customfieldtypes:float`
     *  `com.pyxis.greenhopper.jira:jsw-story-points`
     *  `com.pyxis.greenhopper.jira:gh-epic-status`
     *  `description`
     *  `summary`

##### User permission validator #####

A validator that checks if a user has a permission. Obsolete. You may encounter this validator when getting transition rules and can pass it when updating or creating rules, for example, when you want to duplicate the rules from a workflow on a new workflow.

    {
         "type": "UserPermissionValidator",
         "configuration": {
             "permissionKey": "BROWSE_PROJECTS",
             "nullAllowed": false,
             "username": "TestUser"
         }
     }

 *  `permissionKey` The permission to be validated. Allowed values: [built-in](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-permission-schemes/#built-in-permissions) or app defined permissions.
 *  `nullAllowed` If `true`, allows the transition when `username` is empty.
 *  `username` The username to validate against the `permissionKey`.

#### Post functions ####

Post functions carry out any additional processing required after a Jira workflow transition is executed.

##### Fire issue event function #####

A post function that fires an event that is processed by the listeners.

    {
       "type": "FireIssueEventFunction",
       "configuration": {
         "event": {
           "id":"1"
         }
       }
     }

**Note:** If provided, this post function overrides the default `FireIssueEventFunction`. Can be included once in a transition.

 *  `event` An object containing the ID of the issue event.

##### Update issue status #####

A post function that sets issue status to the linked status of the destination workflow status.

    {
       "type": "UpdateIssueStatusFunction"
     }

**Note:** This post function is a default function in global and directed transitions. It can only be added to the initial transition and can only be added once.

##### Create comment #####

A post function that adds a comment entered during the transition to an issue.

    {
       "type": "CreateCommentFunction"
     }

**Note:** This post function is a default function in global and directed transitions. It can only be added to the initial transition and can only be added once.

##### Store issue #####

A post function that stores updates to an issue.

    {
       "type": "IssueStoreFunction"
     }

**Note:** This post function can only be added to the initial transition and can only be added once.

##### Assign to current user function #####

A post function that assigns the issue to the current user if the current user has the `ASSIGNABLE_USER` permission.

    {
         "type": "AssignToCurrentUserFunction"
     }

**Note:** This post function can be included once in a transition.

##### Assign to lead function #####

A post function that assigns the issue to the project or component lead developer.

    {
         "type": "AssignToLeadFunction"
     }

**Note:** This post function can be included once in a transition.

##### Assign to reporter function #####

A post function that assigns the issue to the reporter.

    {
         "type": "AssignToReporterFunction"
     }

**Note:** This post function can be included once in a transition.

##### Clear field value function #####

A post function that clears the value from a field.

    {
       "type": "ClearFieldValuePostFunction",
       "configuration": {
         "fieldId": "assignee"
       }
     }

 *  `fieldId` The ID of the field.

##### Copy value from other field function #####

A post function that copies the value of one field to another, either within an issue or from parent to subtask.

    {
       "type": "CopyValueFromOtherFieldPostFunction",
       "configuration": {
         "sourceFieldId": "assignee",
         "destinationFieldId": "creator",
         "copyType": "same"
       }
     }

 *  `sourceFieldId` The ID of the source field.
 *  `destinationFieldId` The ID of the destination field.
 *  `copyType` Use `same` to copy the value from a field inside the issue, or `parent` to copy the value from the parent issue.

##### Create Crucible review workflow function (deprecated) #####

A post function that creates a Crucible review for all unreviewed code for the issue.

    {
         "type": "CreateCrucibleReviewWorkflowFunction"
     }

**Note:** This post function can be included once in a transition.

##### Set issue security level based on user's project role function #####

A post function that sets the issue's security level if the current user has a project role.

    {
       "type": "SetIssueSecurityFromRoleFunction",
       "configuration": {
         "projectRole": {
             "id":"10002"
         },
         "issueSecurityLevel": {
             "id":"10000"
         }
       }
     }

 *  `projectRole` An object containing the ID of the project role.
 *  `issueSecurityLevel` OPTIONAL. The object containing the ID of the security level. If not passed, then the security level is set to `none`.

##### Trigger a webhook function #####

A post function that triggers a webhook.

    {
       "type": "TriggerWebhookFunction",
       "configuration": {
         "webhook": {
           "id": "1"
         }
       }
     }

 *  `webhook` An object containing the ID of the webhook listener to trigger.

##### Update issue custom field function #####

A post function that updates the content of an issue custom field.

    {
       "type": "UpdateIssueCustomFieldPostFunction",
       "configuration": {
         "mode": "append",
         "fieldId": "customfield_10003",
         "fieldValue": "yikes"
       }
     }

 *  `mode` Use `replace` to override the field content with `fieldValue` or `append` to add `fieldValue` to the end of the field content.
 *  `fieldId` The ID of the field.
 *  `fieldValue` The update content.

##### Update issue field function #####

A post function that updates a simple issue field.

    {
       "type": "UpdateIssueFieldFunction",
       "configuration": {
         "fieldId": "assignee",
         "fieldValue": "5f0c277e70b8a90025a00776"
       }
     }

 *  `fieldId` The ID of the field. Allowed field types:
    
     *  `assignee`
     *  `description`
     *  `environment`
     *  `priority`
     *  `resolution`
     *  `summary`
     *  `timeoriginalestimate`
     *  `timeestimate`
     *  `timespent`
 *  `fieldValue` The update value.
 *  If the `fieldId` is `assignee`, the `fieldValue` should be one of these values:
    
     *  an account ID.
     *  `automatic`.
     *  a blank string, which sets the value to `unassigned`.

#### Connect rules ####

Connect rules are conditions, validators, and post functions of a transition that are registered by Connect apps. To create a rule registered by the app, the app must be enabled and the rule's module must exist.

    {
       "type": "appKey__moduleKey",
       "configuration": {
         "value":"{\"isValid\":\"true\"}"
       }
     }

 *  `type` A Connect rule key in a form of `appKey__moduleKey`.
 *  `value` The stringified JSON configuration of a Connect rule.

#### Forge rules ####

Forge transition rules are not yet supported.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

The workflow details.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateWorkflowDetails](../schemas/Create/CreateWorkflowDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the workflow is created. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if one or more statuses is not found. |

**Success Response Schema:**

[WorkflowIDs](../schemas/Workflow/WorkflowIDs.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
