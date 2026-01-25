# DELETE /accounts/{account_id}/rum/site_info/{site_id}

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**Delete a Web Analytics site**
**Operation ID:** `web-analytics-delete-site`

Deletes an existing Web Analytics site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | rum_identifier | Yes |  |
| `site_id` | path | rum_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Deleted Web Analytics site identifier. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_site-tag-response-single](../schemas/rum/rum-site-tag-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
