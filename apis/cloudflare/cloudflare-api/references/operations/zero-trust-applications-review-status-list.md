# GET /accounts/{account_id}/gateway/apps/review_status

**Resource:** [Zero Trust applications review status](../resources/Zero-Trust-applications-review-status.md)
**List applications review statuses**
**Operation ID:** `zero-trust-applications-review-status-list`

Retrieve the statuses of your applications.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List applications review status response. |
| 4XX | List applications review status failure response. |

**Success Response Schema:**

[zero-trust-gateway_applications_review_status_response](../schemas/zero-trust-gateway/zero-trust-gateway-applications-review-status-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
