# FieldLastUsed

Information about the most recent use of a field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: TRACKED, NOT_TRACKED, NO_INFORMATION | No | Last used value type:

 *  *TRACKED*: field is tracked and a last used date is available.
 *  *NOT\_TRACKED*: field is not tracked, last used date is not available.
 *  *NO\_INFORMATION*: field is tracked, but no last used date is available. |
| `value` | string (date-time) | No | The date when the value of the field last changed. |

