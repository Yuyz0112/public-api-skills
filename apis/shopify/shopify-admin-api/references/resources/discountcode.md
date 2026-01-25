# discountcode

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/price_rules/{price_rule_id}/discount_codes.json` | Retrieve a list of discount codes. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-price-rules-param-price-rule-id-discount-codes.md) |
| POST | `/admin/api/2020-01/price_rules/{price_rule_id}/discount_codes.json` | Creates a discount code | [View](../operations/deprecated-202001-create-price-rules-param-price-rule-id-discount-codes.md) |
| GET | `/admin/api/2020-01/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Retrieves a single discount code | [View](../operations/deprecated-202001-get-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| PUT | `/admin/api/2020-01/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Updates an existing discount code | [View](../operations/deprecated-202001-update-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| DELETE | `/admin/api/2020-01/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Deletes a discount code | [View](../operations/deprecated-202001-delete-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| GET | `/admin/api/2020-01/discount_codes/lookup.json` | Retrieves the location of a discount code.
          The discount code's location is returned in the location header, not in the DiscountCode object itself.
            Depending on your HTTP client, the location of the discount code might follow the location header automatically. | [View](../operations/deprecated-202001-get-discount-codes-lookup.md) |
| POST | `/admin/api/2020-01/price_rules/{price_rule_id}/batch.json` | Creates a discount code creation job.
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
                "Price rule allocation method can't be blank" | [View](../operations/deprecated-202001-create-price-rules-param-price-rule-id-batch.md) |
| GET | `/admin/api/2020-01/price_rules/{price_rule_id}/batch/{batch_id}.json` | Retrieves a discount code creation job | [View](../operations/deprecated-202001-get-price-rules-param-price-rule-id-batch-param-batch-id.md) |
| GET | `/admin/api/2020-01/price_rules/{price_rule_id}/batch/{batch_id}/discount_codes.json` | Retrieves a list of discount codes for a discount code creation job.
          Discount codes that have been successfully created include a populated id field. Discount codes that
          encountered errors during the creation process include a populated errors field. | [View](../operations/deprecated-202001-get-price-rules-param-price-rule-id-batch-param-batch-id-discount-codes.md) |
| GET | `/admin/api/2020-04/price_rules/{price_rule_id}/discount_codes.json` | Retrieve a list of discount codes. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-price-rules-param-price-rule-id-discount-codes.md) |
| POST | `/admin/api/2020-04/price_rules/{price_rule_id}/discount_codes.json` | Creates a discount code | [View](../operations/deprecated-202004-create-price-rules-param-price-rule-id-discount-codes.md) |
| GET | `/admin/api/2020-04/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Retrieves a single discount code | [View](../operations/deprecated-202004-get-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| PUT | `/admin/api/2020-04/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Updates an existing discount code | [View](../operations/deprecated-202004-update-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| DELETE | `/admin/api/2020-04/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Deletes a discount code | [View](../operations/deprecated-202004-delete-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| GET | `/admin/api/2020-04/discount_codes/lookup.json` | Retrieves the location of a discount code.
          The discount code's location is returned in the location header, not in the DiscountCode object itself.
            Depending on your HTTP client, the location of the discount code might follow the location header automatically. | [View](../operations/deprecated-202004-get-discount-codes-lookup.md) |
| POST | `/admin/api/2020-04/price_rules/{price_rule_id}/batch.json` | Creates a discount code creation job.
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
                "Price rule allocation method can't be blank" | [View](../operations/deprecated-202004-create-price-rules-param-price-rule-id-batch.md) |
| GET | `/admin/api/2020-04/price_rules/{price_rule_id}/batch/{batch_id}.json` | Retrieves a discount code creation job | [View](../operations/deprecated-202004-get-price-rules-param-price-rule-id-batch-param-batch-id.md) |
| GET | `/admin/api/2020-04/price_rules/{price_rule_id}/batch/{batch_id}/discount_codes.json` | Retrieves a list of discount codes for a discount code creation job.
          Discount codes that have been successfully created include a populated id field. Discount codes that
          encountered errors during the creation process include a populated errors field. | [View](../operations/deprecated-202004-get-price-rules-param-price-rule-id-batch-param-batch-id-discount-codes.md) |
| GET | `/admin/api/2020-07/price_rules/{price_rule_id}/discount_codes.json` | Retrieve a list of discount codes. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-price-rules-param-price-rule-id-discount-codes.md) |
| POST | `/admin/api/2020-07/price_rules/{price_rule_id}/discount_codes.json` | Creates a discount code | [View](../operations/deprecated-202007-create-price-rules-param-price-rule-id-discount-codes.md) |
| GET | `/admin/api/2020-07/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Retrieves a single discount code | [View](../operations/deprecated-202007-get-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| PUT | `/admin/api/2020-07/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Updates an existing discount code | [View](../operations/deprecated-202007-update-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| DELETE | `/admin/api/2020-07/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Deletes a discount code | [View](../operations/deprecated-202007-delete-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| GET | `/admin/api/2020-07/discount_codes/lookup.json` | Retrieves the location of a discount code.
          The discount code's location is returned in the location header, not in the DiscountCode object itself.
            Depending on your HTTP client, the location of the discount code might follow the location header automatically. | [View](../operations/deprecated-202007-get-discount-codes-lookup.md) |
| POST | `/admin/api/2020-07/price_rules/{price_rule_id}/batch.json` | Creates a discount code creation job.
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
                "Price rule allocation method can't be blank" | [View](../operations/deprecated-202007-create-price-rules-param-price-rule-id-batch.md) |
| GET | `/admin/api/2020-07/price_rules/{price_rule_id}/batch/{batch_id}.json` | Retrieves a discount code creation job | [View](../operations/deprecated-202007-get-price-rules-param-price-rule-id-batch-param-batch-id.md) |
| GET | `/admin/api/2020-07/price_rules/{price_rule_id}/batch/{batch_id}/discount_codes.json` | Retrieves a list of discount codes for a discount code creation job.
          Discount codes that have been successfully created include a populated id field. Discount codes that
          encountered errors during the creation process include a populated errors field. | [View](../operations/deprecated-202007-get-price-rules-param-price-rule-id-batch-param-batch-id-discount-codes.md) |
| GET | `/admin/api/2020-10/price_rules/{price_rule_id}/discount_codes.json` | Retrieve a list of discount codes. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-price-rules-param-price-rule-id-discount-codes.md) |
| POST | `/admin/api/2020-10/price_rules/{price_rule_id}/discount_codes.json` | Creates a discount code | [View](../operations/create-price-rules-param-price-rule-id-discount-codes.md) |
| GET | `/admin/api/2020-10/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Retrieves a single discount code | [View](../operations/get-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| PUT | `/admin/api/2020-10/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Updates an existing discount code | [View](../operations/update-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| DELETE | `/admin/api/2020-10/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Deletes a discount code | [View](../operations/delete-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| GET | `/admin/api/2020-10/discount_codes/lookup.json` | Retrieves the location of a discount code.
          The discount code's location is returned in the location header, not in the DiscountCode object itself.
            Depending on your HTTP client, the location of the discount code might follow the location header automatically. | [View](../operations/get-discount-codes-lookup.md) |
| POST | `/admin/api/2020-10/price_rules/{price_rule_id}/batch.json` | Creates a discount code creation job.
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
                "Price rule allocation method can't be blank" | [View](../operations/create-price-rules-param-price-rule-id-batch.md) |
| GET | `/admin/api/2020-10/price_rules/{price_rule_id}/batch/{batch_id}.json` | Retrieves a discount code creation job | [View](../operations/get-price-rules-param-price-rule-id-batch-param-batch-id.md) |
| GET | `/admin/api/2020-10/price_rules/{price_rule_id}/batch/{batch_id}/discount_codes.json` | Retrieves a list of discount codes for a discount code creation job.
          Discount codes that have been successfully created include a populated id field. Discount codes that
          encountered errors during the creation process include a populated errors field. | [View](../operations/get-price-rules-param-price-rule-id-batch-param-batch-id-discount-codes.md) |
| GET | `/admin/api/2021-01/price_rules/{price_rule_id}/discount_codes.json` | Retrieve a list of discount codes. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-price-rules-param-price-rule-id-discount-codes.md) |
| POST | `/admin/api/2021-01/price_rules/{price_rule_id}/discount_codes.json` | Creates a discount code | [View](../operations/deprecated-202101-create-price-rules-param-price-rule-id-discount-codes.md) |
| GET | `/admin/api/2021-01/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Retrieves a single discount code | [View](../operations/deprecated-202101-get-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| PUT | `/admin/api/2021-01/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Updates an existing discount code | [View](../operations/deprecated-202101-update-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| DELETE | `/admin/api/2021-01/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Deletes a discount code | [View](../operations/deprecated-202101-delete-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| GET | `/admin/api/2021-01/discount_codes/lookup.json` | Retrieves the location of a discount code.
          The discount code's location is returned in the location header, not in the DiscountCode object itself.
            Depending on your HTTP client, the location of the discount code might follow the location header automatically. | [View](../operations/deprecated-202101-get-discount-codes-lookup.md) |
| POST | `/admin/api/2021-01/price_rules/{price_rule_id}/batch.json` | Creates a discount code creation job.
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
                "Price rule allocation method can't be blank" | [View](../operations/deprecated-202101-create-price-rules-param-price-rule-id-batch.md) |
| GET | `/admin/api/2021-01/price_rules/{price_rule_id}/batch/{batch_id}.json` | Retrieves a discount code creation job | [View](../operations/deprecated-202101-get-price-rules-param-price-rule-id-batch-param-batch-id.md) |
| GET | `/admin/api/2021-01/price_rules/{price_rule_id}/batch/{batch_id}/discount_codes.json` | Retrieves a list of discount codes for a discount code creation job.
          Discount codes that have been successfully created include a populated id field. Discount codes that
          encountered errors during the creation process include a populated errors field. | [View](../operations/deprecated-202101-get-price-rules-param-price-rule-id-batch-param-batch-id-discount-codes.md) |
| GET | `/admin/api/unstable/price_rules/{price_rule_id}/discount_codes.json` | Retrieve a list of discount codes. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-price-rules-param-price-rule-id-discount-codes.md) |
| POST | `/admin/api/unstable/price_rules/{price_rule_id}/discount_codes.json` | Creates a discount code | [View](../operations/deprecated-unstable-create-price-rules-param-price-rule-id-discount-codes.md) |
| GET | `/admin/api/unstable/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Retrieves a single discount code | [View](../operations/deprecated-unstable-get-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| PUT | `/admin/api/unstable/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Updates an existing discount code | [View](../operations/deprecated-unstable-update-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| DELETE | `/admin/api/unstable/price_rules/{price_rule_id}/discount_codes/{discount_code_id}.json` | Deletes a discount code | [View](../operations/deprecated-unstable-delete-price-rules-param-price-rule-id-discount-codes-param-discount-code-id.md) |
| GET | `/admin/api/unstable/discount_codes/lookup.json` | Retrieves the location of a discount code.
          The discount code's location is returned in the location header, not in the DiscountCode object itself.
            Depending on your HTTP client, the location of the discount code might follow the location header automatically. | [View](../operations/deprecated-unstable-get-discount-codes-lookup.md) |
| POST | `/admin/api/unstable/price_rules/{price_rule_id}/batch.json` | Creates a discount code creation job.
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
                "Price rule allocation method can't be blank" | [View](../operations/deprecated-unstable-create-price-rules-param-price-rule-id-batch.md) |
| GET | `/admin/api/unstable/price_rules/{price_rule_id}/batch/{batch_id}.json` | Retrieves a discount code creation job | [View](../operations/deprecated-unstable-get-price-rules-param-price-rule-id-batch-param-batch-id.md) |
| GET | `/admin/api/unstable/price_rules/{price_rule_id}/batch/{batch_id}/discount_codes.json` | Retrieves a list of discount codes for a discount code creation job.
          Discount codes that have been successfully created include a populated id field. Discount codes that
          encountered errors during the creation process include a populated errors field. | [View](../operations/deprecated-unstable-get-price-rules-param-price-rule-id-batch-param-batch-id-discount-codes.md) |
