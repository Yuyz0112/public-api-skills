# Access requests

An access request object represents a user's request to an item, such as a project or portfolio, that they do not have access to. The request is sent to the owner of the item for approval.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/access_requests` | Get access requests | [View](../operations/getAccessRequests.md) |
| POST | `/access_requests` | Create an access request | [View](../operations/createAccessRequest.md) |
| POST | `/access_requests/{access_request_gid}/approve` | Approve an access request | [View](../operations/approveAccessRequest.md) |
| POST | `/access_requests/{access_request_gid}/reject` | Reject an access request | [View](../operations/rejectAccessRequest.md) |
