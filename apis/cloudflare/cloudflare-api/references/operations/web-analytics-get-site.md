# GET /accounts/{account_id}/rum/site_info/{site_id}

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**Get a Web Analytics site**
**Operation ID:** `web-analytics-get-site`

Retrieves a Web Analytics site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | rum_identifier | Yes |  |
| `site_id` | path | rum_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Web Analytics site. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_site-response-single](../schemas/rum/rum-site-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
