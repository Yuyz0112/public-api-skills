# Path

Defines a single path

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `path` | string | Yes | A series of path commands that encodes how to draw the path. |
| `windingRule` | enum: NONZERO, EVENODD | Yes | The winding rule for the path (same as in SVGs). This determines whether a given point in space is inside or outside the path. |
| `overrideID` | number | No | If there is a per-region fill, this refers to an ID in the `fillOverrideTable`. |

