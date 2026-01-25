# CreateWorkflowTransitionRulesDetails

The details of a workflow transition rules.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conditions` | any | No | The workflow conditions. |
| `postFunctions` | CreateWorkflowTransitionRule[] | No | The workflow post functions.

**Note:** The default post functions are always added to the *initial* transition, as in:

    "postFunctions": [
        {
            "type": "IssueCreateFunction"
        },
        {
            "type": "IssueReindexFunction"
        },
        {
            "type": "FireIssueEventFunction",
            "configuration": {
                "event": {
                    "id": "1",
                    "name": "issue_created"
                }
            }
        }
    ]

**Note:** The default post functions are always added to the *global* and *directed* transitions, as in:

    "postFunctions": [
        {
            "type": "UpdateIssueStatusFunction"
        },
        {
            "type": "CreateCommentFunction"
        },
        {
            "type": "GenerateChangeHistoryFunction"
        },
        {
            "type": "IssueReindexFunction"
        },
        {
            "type": "FireIssueEventFunction",
            "configuration": {
                "event": {
                    "id": "13",
                    "name": "issue_generic"
                }
            }
        }
    ] |
| `validators` | CreateWorkflowTransitionRule[] | No | The workflow validators.

**Note:** The default permission validator is always added to the *initial* transition, as in:

    "validators": [
        {
            "type": "PermissionValidator",
            "configuration": {
                "permissionKey": "CREATE_ISSUES"
            }
        }
    ] |

