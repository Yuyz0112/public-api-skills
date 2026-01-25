# DELETE /accounts/{account_id}/access/custom_pages/{custom_page_id}

**Resource:** [Access custom pages](../resources/Access-custom-pages.md)
**Delete a custom page**
**Operation ID:** `access-custom-pages-delete-a-custom-page`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_page_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete a custom page response |
| 4XX | Delete a custom page response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
