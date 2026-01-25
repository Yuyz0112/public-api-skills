# DefaultShareScope

Details of the scope of the default sharing for new filters and dashboards.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scope` | enum: GLOBAL, AUTHENTICATED, PRIVATE | Yes | The scope of the default sharing for new filters and dashboards:

 *  `AUTHENTICATED` Shared with all logged-in users.
 *  `GLOBAL` Shared with all logged-in users. This shows as `AUTHENTICATED` in the response.
 *  `PRIVATE` Not shared with any users. |

