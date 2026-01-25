# Request for Information (RFI)

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/accounts/{account_id}/cloudforce-one/requests` | List Requests | [View](../operations/cloudforce-one-request-list.md) |
| GET | `/accounts/{account_id}/cloudforce-one/requests/constants` | Get Request Priority, Status, and TLP constants | [View](../operations/cloudforce-one-request-constants.md) |
| POST | `/accounts/{account_id}/cloudforce-one/requests/new` | Create a New Request. | [View](../operations/cloudforce-one-request-new.md) |
| GET | `/accounts/{account_id}/cloudforce-one/requests/quota` | Get Request Quota | [View](../operations/cloudforce-one-request-quota.md) |
| GET | `/accounts/{account_id}/cloudforce-one/requests/types` | Get Request Types | [View](../operations/cloudforce-one-request-types.md) |
| GET | `/accounts/{account_id}/cloudforce-one/requests/{request_id}` | Get a Request | [View](../operations/cloudforce-one-request-get.md) |
| PUT | `/accounts/{account_id}/cloudforce-one/requests/{request_id}` | Update a Request | [View](../operations/cloudforce-one-request-update.md) |
| DELETE | `/accounts/{account_id}/cloudforce-one/requests/{request_id}` | Delete a Request | [View](../operations/cloudforce-one-request-delete.md) |
| POST | `/accounts/{account_id}/cloudforce-one/requests/{request_id}/asset` | List Request Assets | [View](../operations/cloudforce-one-request-asset-list.md) |
| POST | `/accounts/{account_id}/cloudforce-one/requests/{request_id}/asset/new` | Create a New Request Asset | [View](../operations/cloudforce-one-request-asset-new.md) |
| GET | `/accounts/{account_id}/cloudforce-one/requests/{request_id}/asset/{asset_id}` | Get a Request Asset | [View](../operations/cloudforce-one-request-asset-get.md) |
| PUT | `/accounts/{account_id}/cloudforce-one/requests/{request_id}/asset/{asset_id}` | Update a Request Asset | [View](../operations/cloudforce-one-request-asset-update.md) |
| DELETE | `/accounts/{account_id}/cloudforce-one/requests/{request_id}/asset/{asset_id}` | Delete a Request Asset | [View](../operations/cloudforce-one-request-asset-delete.md) |
| POST | `/accounts/{account_id}/cloudforce-one/requests/{request_id}/message` | List Request Messages | [View](../operations/cloudforce-one-request-message-list.md) |
| POST | `/accounts/{account_id}/cloudforce-one/requests/{request_id}/message/new` | Create a New Request Message | [View](../operations/cloudforce-one-request-message-new.md) |
| PUT | `/accounts/{account_id}/cloudforce-one/requests/{request_id}/message/{message_id}` | Update a Request Message | [View](../operations/cloudforce-one-request-message-update.md) |
| DELETE | `/accounts/{account_id}/cloudforce-one/requests/{request_id}/message/{message_id}` | Delete a Request Message | [View](../operations/cloudforce-one-request-message-delete.md) |
