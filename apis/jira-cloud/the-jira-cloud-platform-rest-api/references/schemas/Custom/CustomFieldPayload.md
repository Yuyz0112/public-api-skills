# CustomFieldPayload

Defines the payload for the custom field definitions. See https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-fields/\#api-rest-api-3-field-post

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cfType` | string | No | The type of the custom field |
| `description` | string | No | The description of the custom field |
| `name` | string | No | The name of the custom field |
| `onConflict` | enum: FAIL, USE, NEW | No | The strategy to use when there is a conflict with an existing custom field. FAIL - Fail execution, this always needs to be unique; USE - Use the existing entity and ignore new entity parameters |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `scope` | enum: GLOBAL, TEMPLATE, PROJECT | No | Allows an overwrite to declare the new Custom Field to be created as a GLOBAL-scoped field. Leave this as empty or null to use the project's default scope. |
| `searcherKey` | string | No | The searcher key of the custom field |

