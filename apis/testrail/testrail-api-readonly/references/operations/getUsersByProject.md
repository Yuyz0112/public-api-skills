# GET /index.php?/api/v2/get_users/{project_id}

**Resource:** [read](../resources/read.md)
**Get users for project**
**Operation ID:** `getUsersByProject`

## Responses

| Status | Description |
|--------|-------------|
| 200 | User list |
| default | (reference) |

**Success Response Schema:**

Array of [User](../schemas/User/User.md)

## Security

- **basicAuth**
