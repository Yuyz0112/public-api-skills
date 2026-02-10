# Access requests

Operations related to access requests.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/groups/{id}/access_requests` | Gets a list of access requests for a group. | [View](../operations/getApiV4GroupsIdAccessRequests.md) |
| POST | `/api/v4/groups/{id}/access_requests` | Requests access for the authenticated user to a group. | [View](../operations/postApiV4GroupsIdAccessRequests.md) |
| PUT | `/api/v4/groups/{id}/access_requests/{user_id}/approve` | Approves an access request for the given user. | [View](../operations/putApiV4GroupsIdAccessRequestsUserIdApprove.md) |
| DELETE | `/api/v4/groups/{id}/access_requests/{user_id}` | Denies an access request for the given user. | [View](../operations/deleteApiV4GroupsIdAccessRequestsUserId.md) |
| GET | `/api/v4/projects/{id}/access_requests` | Gets a list of access requests for a project. | [View](../operations/getApiV4ProjectsIdAccessRequests.md) |
| POST | `/api/v4/projects/{id}/access_requests` | Requests access for the authenticated user to a project. | [View](../operations/postApiV4ProjectsIdAccessRequests.md) |
| PUT | `/api/v4/projects/{id}/access_requests/{user_id}/approve` | Approves an access request for the given user. | [View](../operations/putApiV4ProjectsIdAccessRequestsUserIdApprove.md) |
| DELETE | `/api/v4/projects/{id}/access_requests/{user_id}` | Denies an access request for the given user. | [View](../operations/deleteApiV4ProjectsIdAccessRequestsUserId.md) |
