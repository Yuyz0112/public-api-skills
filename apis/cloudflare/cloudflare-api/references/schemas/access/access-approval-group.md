# access_approval_group

A group of email addresses that can approve a temporary authentication request.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `approvals_needed` | number | Yes | The number of approvals needed to obtain access. |
| `email_addresses` | string[] | No | A list of emails that can approve the access request. |
| `email_list_uuid` | string | No | The UUID of an re-usable email list. |

