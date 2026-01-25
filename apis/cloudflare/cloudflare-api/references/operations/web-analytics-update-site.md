# PUT /accounts/{account_id}/rum/site_info/{site_id}

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**Update a Web Analytics site**
**Operation ID:** `web-analytics-update-site`

Updates an existing Web Analytics site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | rum_identifier | Yes |  |
| `site_id` | path | rum_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [rum_update-site-request](../schemas/rum/rum-update-site-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Updated Web Analytics site. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_site-response-single](../schemas/rum/rum-site-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
