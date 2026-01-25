# SwimlanesPayload

The payload for customising a swimlanes on a board

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `customSwimlanes` | SwimlanePayload[] | No | The custom swimlane definitions. |
| `defaultCustomSwimlaneName` | string | No | The name of the custom swimlane to use for work items that don't match any other swimlanes. |
| `swimlaneStrategy` | enum: none, custom, parentChild... | No | The swimlane strategy for the board. |

