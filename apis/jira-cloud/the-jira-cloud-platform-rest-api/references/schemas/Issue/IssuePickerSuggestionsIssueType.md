# IssuePickerSuggestionsIssueType

A type of issue suggested for use in auto-completion.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The ID of the type of issues suggested for use in auto-completion. |
| `issues` | SuggestedIssue[] | No | A list of issues suggested for use in auto-completion. |
| `label` | string | No | The label of the type of issues suggested for use in auto-completion. |
| `msg` | string | No | If no issue suggestions are found, returns a message indicating no suggestions were found, |
| `sub` | string | No | If issue suggestions are found, returns a message indicating the number of issues suggestions found and returned. |

