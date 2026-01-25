# PUT /accounts/{account_id}/gateway/apps/review_status

**Resource:** [Zero Trust applications review status](../resources/Zero-Trust-applications-review-status.md)
**Update applications review statuses**
**Operation ID:** `zero-trust-applications-review-status-update`

Update the statuses of your applications.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update applications review status response. |
| 4XX | Update applications review status failure response. |

**Success Response Schema:**

[zero-trust-gateway_applications_review_status_response](../schemas/zero-trust-gateway/zero-trust-gateway-applications-review-status-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
