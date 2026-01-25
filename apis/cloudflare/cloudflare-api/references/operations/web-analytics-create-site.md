# POST /accounts/{account_id}/rum/site_info

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**Create a Web Analytics site**
**Operation ID:** `web-analytics-create-site`

Creates a new Web Analytics site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | rum_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [rum_create-site-request](../schemas/rum/rum-create-site-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Created Web Analytics site. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_site-response-single](../schemas/rum/rum-site-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
