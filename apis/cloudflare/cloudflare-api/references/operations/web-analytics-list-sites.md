# GET /accounts/{account_id}/rum/site_info/list

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**List Web Analytics sites**
**Operation ID:** `web-analytics-list-sites`

Lists all Web Analytics sites of an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | rum_identifier | Yes |  |
| `per_page` | query | rum_per_page | No |  |
| `page` | query | rum_page | No |  |
| `order_by` | query | rum_order_by | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of Web Analytics sites. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_sites-response-collection](../schemas/rum/rum-sites-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
