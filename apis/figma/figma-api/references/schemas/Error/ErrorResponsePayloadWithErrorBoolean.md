# ErrorResponsePayloadWithErrorBoolean

A response indicating an error occurred.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `error` | enum: true | Yes | For erroneous requests, this value is always `true`. |
| `status` | number | Yes | Status code |
| `message` | string | Yes | A string describing the error |

