# POST /admin/api/unstable/price_rules/{price_rule_id}/batch.json

**Resource:** [discounts/discountcode](../resources/discounts-discountcode.md)
**Creates a discount code creation job.
          The batch endpoint can be used to asynchronously create up to 100 discount codes in a single request. It
          enqueues and returns a discount_code_creation object that can be monitored for completion.
          Response fields that are specific to the batch endpoint include:
          
            status: The state of the discount code creation job. Possible values are:
              
                queued: The job is acknowledged, but not started.
                running: The job is in process.
                completed: The job has finished.
              
            codes_count: The number of discount codes to create.
            imported_count: The number of discount codes created successfully.
            failed_count: The number of discount codes that were not created successfully. Unsuccessful attempts will retry up to three times.
            logs: A report that specifies when no discount codes were created because the provided data was invalid. Example responses:
              
                "Price rule target selection can't be blank"
                "Price rule allocation method can't be blank"**
**Operation ID:** `deprecated_unstable_create_price_rules_param_price_rule_id_batch`

https://shopify.dev/docs/admin-api/rest/reference/discounts/discountcode#batch_create-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `price_rule_id` | path | string | Yes | price_rule_id |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

