# DELETE /accounts/{account_id}/pay-per-crawl/publisher/stripe

**Resource:** [ppc_stripe](../resources/ppc-stripe.md)
**Deletes the stripe config for a publisher**
**Operation ID:** `pay-per-crawl.publisherDeleteStripeConfig`

Deletes the stripe config for a publisher.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | account id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

**Success Response Schema:**

[pay-per-crawl_apiNoResultResponse](../schemas/pay-per-crawl/pay-per-crawl-apiNoResultResponse.md)

## Security

- **api_email**
- **api_key**
