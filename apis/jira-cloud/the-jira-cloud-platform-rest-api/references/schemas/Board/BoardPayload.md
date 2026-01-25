# BoardPayload

The payload for creating a board

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `boardFilterJQL` | string | No | Takes in a JQL string to create a new filter. If no value is provided, it'll default to a JQL filter for the project creating |
| `cardColorStrategy` | enum: ISSUE_TYPE, REQUEST_TYPE, ASSIGNEE... | No | Card color settings of the board |
| `cardLayout` | [CardLayout](CardLayout.md) | No |  |
| `cardLayouts` | CardLayoutField[] | No | Card layout settings of the board |
| `columns` | BoardColumnPayload[] | No | The columns of the board |
| `features` | BoardFeaturePayload[] | No | Feature settings for the board |
| `name` | string | No | The name of the board |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `quickFilters` | QuickFilterPayload[] | No | The quick filters for the board. |
| `supportsSprint` | boolean | No | Whether sprints are supported on the board |
| `swimlanes` | [SwimlanesPayload](SwimlanesPayload.md) | No |  |
| `workingDaysConfig` | [WorkingDaysConfig](WorkingDaysConfig.md) | No |  |

