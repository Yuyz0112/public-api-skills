# POST /accounts/{account_id}/pay-per-crawl/publisher/stripe

**Resource:** [ppc_stripe](../resources/ppc-stripe.md)
**Creates the stripe config for a publisher**
**Operation ID:** `pay-per-crawl.publisherCreateStripeConfig`

Creates the stripe config for a publisher.

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

[pay-per-crawl_createStripeConfigResponse](../schemas/pay-per-crawl/pay-per-crawl-createStripeConfigResponse.md)

## Security

- **api_email**
- **api_key**
