# Resource Sharing

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/shares` | List account shares | [View](../operations/shares-list.md) |
| POST | `/accounts/{account_id}/shares` | Create a new share | [View](../operations/share-create.md) |
| GET | `/accounts/{account_id}/shares/{share_id}` | Get account share by ID | [View](../operations/shares-get-by-id.md) |
| PUT | `/accounts/{account_id}/shares/{share_id}` | Update a share | [View](../operations/share-update.md) |
| DELETE | `/accounts/{account_id}/shares/{share_id}` | Delete a share | [View](../operations/share-delete.md) |
| GET | `/accounts/{account_id}/shares/{share_id}/recipients` | List share recipients by share ID | [View](../operations/share-recipients-list.md) |
| PUT | `/accounts/{account_id}/shares/{share_id}/recipients` | Update a share's recipients | [View](../operations/share-recipients-update.md) |
| POST | `/accounts/{account_id}/shares/{share_id}/recipients` | Create a new share recipient | [View](../operations/share-recipient-create.md) |
| GET | `/accounts/{account_id}/shares/{share_id}/recipients/{recipient_id}` | Get share recipient by ID | [View](../operations/share-recipients-get-by-id.md) |
| DELETE | `/accounts/{account_id}/shares/{share_id}/recipients/{recipient_id}` | Delete a share recipient | [View](../operations/share-recipient-delete.md) |
| GET | `/accounts/{account_id}/shares/{share_id}/resources` | List share resources by share ID | [View](../operations/share-resources-list.md) |
| POST | `/accounts/{account_id}/shares/{share_id}/resources` | Create a new share resource | [View](../operations/share-resource-create.md) |
| GET | `/accounts/{account_id}/shares/{share_id}/resources/{resource_id}` | Get share resource by ID | [View](../operations/share-resources-get-by-id.md) |
| PUT | `/accounts/{account_id}/shares/{share_id}/resources/{resource_id}` | Update a share resource | [View](../operations/share-resource-update.md) |
| DELETE | `/accounts/{account_id}/shares/{share_id}/resources/{resource_id}` | Delete a share resource | [View](../operations/share-resource-delete.md) |
| GET | `/organizations/{organization_id}/shares` | List organization shares | [View](../operations/organization-shares-list.md) |
