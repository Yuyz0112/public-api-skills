# latest_api_version

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/oauth/access_scopes.json` | Retrieves a list of access scopes associated to the access token. | [View](../operations/get-admin-oauth-access-scopes.md) |
| GET | `/admin/api/2020-10/storefront_access_tokens.json` | Retrieves a list of storefront access tokens that have been issued | [View](../operations/get-storefront-access-tokens.md) |
| POST | `/admin/api/2020-10/storefront_access_tokens.json` | Creates a new storefront access token | [View](../operations/create-storefront-access-tokens.md) |
| DELETE | `/admin/api/2020-10/storefront_access_tokens/{storefront_access_token_id}.json` | Deletes an existing storefront access token | [View](../operations/delete-storefront-access-tokens-param-storefront-access-token-id.md) |
| GET | `/admin/api/2020-10/reports.json` | Retrieves a list of reports. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-reports.md) |
| POST | `/admin/api/2020-10/reports.json` | Creates a new report | [View](../operations/create-reports.md) |
| GET | `/admin/api/2020-10/reports/{report_id}.json` | Retrieves a single report created by your app | [View](../operations/get-reports-param-report-id.md) |
| PUT | `/admin/api/2020-10/reports/{report_id}.json` | Updates a report | [View](../operations/update-reports-param-report-id.md) |
| DELETE | `/admin/api/2020-10/reports/{report_id}.json` | Deletes a report | [View](../operations/delete-reports-param-report-id.md) |
| GET | `/admin/api/2020-10/application_charges.json` | Retrieves a list of application charges | [View](../operations/get-application-charges.md) |
| POST | `/admin/api/2020-10/application_charges.json` | Creates an application charge | [View](../operations/create-application-charges.md) |
| GET | `/admin/api/2020-10/application_charges/{application_charge_id}.json` | Retrieves an application charge | [View](../operations/get-application-charges-param-application-charge-id.md) |
| POST | `/admin/api/2020-10/application_charges/{application_charge_id}/activate.json` | Caution
  This endpoint is no longer required and is deprecated as of
  API version 2021-01.

"Activates an accepted application charge. One-time charges are now immediately activated
when approved by a merchant. | [View](../operations/create-application-charges-param-application-charge-id-activate.md) |
| GET | `/admin/api/2020-10/application_credits.json` | Retrieves all application credits | [View](../operations/get-application-credits.md) |
| POST | `/admin/api/2020-10/application_credits.json` | Creates an application credit | [View](../operations/create-application-credits.md) |
| GET | `/admin/api/2020-10/application_credits/{application_credit_id}.json` | Retrieves a single application credit | [View](../operations/get-application-credits-param-application-credit-id.md) |
| GET | `/admin/api/2020-10/recurring_application_charges.json` | Retrieves a list of recurring application charges | [View](../operations/get-recurring-application-charges.md) |
| POST | `/admin/api/2020-10/recurring_application_charges.json` | Creates a recurring application charge | [View](../operations/create-recurring-application-charges.md) |
| GET | `/admin/api/2020-10/recurring_application_charges/{recurring_application_charge_id}.json` | Retrieves a single charge | [View](../operations/get-recurring-application-charges-param-recurring-application-charge-id.md) |
| DELETE | `/admin/api/2020-10/recurring_application_charges/{recurring_application_charge_id}.json` | Cancels a recurring application charge | [View](../operations/delete-recurring-application-charges-param-recurring-application-charge-id.md) |
| POST | `/admin/api/2020-10/recurring_application_charges/{recurring_application_charge_id}/activate.json` | Caution
  This endpoint is no longer required and is deprecated as of
  API version 2021-01.

Activates a previously accepted recurring application charge. Recurring charges are now
immediately activated when approved by a merchant. | [View](../operations/create-recurring-application-charges-param-recurring-application-charge-id-activate.md) |
| PUT | `/admin/api/2020-10/recurring_application_charges/{recurring_application_charge_id}/customize.json` | Updates the capped amount of an active recurring application charge | [View](../operations/update-recurring-application-charges-param-recurring-application-charge-id-customize.md) |
| GET | `/admin/api/2020-10/recurring_application_charges/{recurring_application_charge_id}/usage_charges.json` | Retrieves a list of usage charges | [View](../operations/get-recurring-application-charges-param-recurring-application-charge-id-usage-charges.md) |
| POST | `/admin/api/2020-10/recurring_application_charges/{recurring_application_charge_id}/usage_charges.json` | Creates a usage charge | [View](../operations/create-recurring-application-charges-param-recurring-application-charge-id-usage-charges.md) |
| GET | `/admin/api/2020-10/recurring_application_charges/{recurring_application_charge_id}/usage_charges/{usage_charge_id}.json` | Retrieves a single charge | [View](../operations/get-recurring-application-charges-param-recurring-application-charge-id-usage-charges-param-usage-charge-id.md) |
| GET | `/admin/api/2020-10/customers.json` | Retrieves a list of customers. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-customers.md) |
| POST | `/admin/api/2020-10/customers.json` | Creates a customer. | [View](../operations/create-customers.md) |
| GET | `/admin/api/2020-10/customers/search.json` | Searches for customers that match a supplied query. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-customers-search.md) |
| GET | `/admin/api/2020-10/customers/{customer_id}.json` | Retrieves a single customer. | [View](../operations/get-customers-param-customer-id.md) |
| PUT | `/admin/api/2020-10/customers/{customer_id}.json` | Updates a customer. | [View](../operations/update-customers-param-customer-id.md) |
| DELETE | `/admin/api/2020-10/customers/{customer_id}.json` | Deletes a customer. A customer can't be deleted if they have existing orders. | [View](../operations/delete-customers-param-customer-id.md) |
| POST | `/admin/api/2020-10/customers/{customer_id}/account_activation_url.json` | Generate an account activation URL for a customer whose account is not yet enabled. This is useful when you've imported a large number of customers and want to send them activation emails all at once. Using this approach, you'll need to generate and send the activation emails yourself.
            The account activation URL generated by this endpoint is for one-time use and will expire after 30 days. If you make a new POST request to this endpoint, then a new URL will be generated. The new URL will be again valid for 30 days, but the previous URL will no longer be valid. | [View](../operations/create-customers-param-customer-id-account-activation-url.md) |
| POST | `/admin/api/2020-10/customers/{customer_id}/send_invite.json` | Sends an account invite to a customer. | [View](../operations/create-customers-param-customer-id-send-invite.md) |
| GET | `/admin/api/2020-10/customers/count.json` | Retrieves a count of all customers. | [View](../operations/get-customers-count.md) |
| GET | `/admin/api/2020-10/customers/{customer_id}/orders.json` | Retrieves all orders belonging to a customer. The query string parameters that are available to the  Order resource are also available to this endpoint. | [View](../operations/get-customers-param-customer-id-orders.md) |
| GET | `/admin/api/2020-10/customers/{customer_id}/addresses.json` | Retrieves a list of addresses for a customer. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-customers-param-customer-id-addresses.md) |
| POST | `/admin/api/2020-10/customers/{customer_id}/addresses.json` | Creates a new address for a customer. | [View](../operations/create-customers-param-customer-id-addresses.md) |
| GET | `/admin/api/2020-10/customers/{customer_id}/addresses/{address_id}.json` | Retrieves details a single customer address. | [View](../operations/get-customers-param-customer-id-addresses-param-address-id.md) |
| PUT | `/admin/api/2020-10/customers/{customer_id}/addresses/{address_id}.json` | Updates an existing customer address. | [View](../operations/update-customers-param-customer-id-addresses-param-address-id.md) |
| DELETE | `/admin/api/2020-10/customers/{customer_id}/addresses/{address_id}.json` | Removes an address from a customer’s address list. | [View](../operations/delete-customers-param-customer-id-addresses-param-address-id.md) |
| PUT | `/admin/api/2020-10/customers/{customer_id}/addresses/set.json` | Performs bulk operations for multiple customer addresses. | [View](../operations/update-customers-param-customer-id-addresses-set.md) |
| PUT | `/admin/api/2020-10/customers/{customer_id}/addresses/{address_id}/default.json` | Sets the default address for a customer. | [View](../operations/update-customers-param-customer-id-addresses-param-address-id-default.md) |
| GET | `/admin/api/2020-10/customer_saved_searches.json` | Retrieves a list of customer saved searches. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-customer-saved-searches.md) |
| POST | `/admin/api/2020-10/customer_saved_searches.json` | Creates a customer saved search. | [View](../operations/create-customer-saved-searches.md) |
| GET | `/admin/api/2020-10/customer_saved_searches/count.json` | Retrieves a count of all customer saved searches. | [View](../operations/get-customer-saved-searches-count.md) |
| GET | `/admin/api/2020-10/customer_saved_searches/{customer_saved_search_id}.json` | Retrieves a single customer saved search. | [View](../operations/get-customer-saved-searches-param-customer-saved-search-id.md) |
| PUT | `/admin/api/2020-10/customer_saved_searches/{customer_saved_search_id}.json` | Updates a customer saved search. | [View](../operations/update-customer-saved-searches-param-customer-saved-search-id.md) |
| DELETE | `/admin/api/2020-10/customer_saved_searches/{customer_saved_search_id}.json` | Deletes a customer saved search. | [View](../operations/delete-customer-saved-searches-param-customer-saved-search-id.md) |
| GET | `/admin/api/2020-10/customer_saved_searches/{customer_saved_search_id}/customers.json` | Retrieves all customers returned by a customer saved search. | [View](../operations/get-customer-saved-searches-param-customer-saved-search-id-customers.md) |
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
| GET | `/admin/api/2020-10/events.json` | Retrieves a list of events. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-events.md) |
| GET | `/admin/api/2020-10/events/{event_id}.json` | Retrieves a single event by its ID | [View](../operations/get-events-param-event-id.md) |
| GET | `/admin/api/2020-10/events/count.json` | Retrieves a count of events | [View](../operations/get-events-count.md) |
| GET | `/admin/api/2020-10/webhooks.json` | Retrieves a list of webhooks. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-webhooks.md) |
| POST | `/admin/api/2020-10/webhooks.json` | Create a new webhook subscription by specifying both an address and a topic | [View](../operations/create-webhooks.md) |
| GET | `/admin/api/2020-10/webhooks/count.json` | Retrieves a count of existing webhook subscriptions | [View](../operations/get-webhooks-count.md) |
| GET | `/admin/api/2020-10/webhooks/{webhook_id}.json` | Retrieves a single webhook subscription | [View](../operations/get-webhooks-param-webhook-id.md) |
| PUT | `/admin/api/2020-10/webhooks/{webhook_id}.json` | Update a webhook subscription's topic or address URIs | [View](../operations/update-webhooks-param-webhook-id.md) |
| DELETE | `/admin/api/2020-10/webhooks/{webhook_id}.json` | Delete a webhook subscription | [View](../operations/delete-webhooks-param-webhook-id.md) |
| GET | `/admin/api/2020-10/inventory_items.json` | Retrieves a list of inventory items. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-inventory-items.md) |
| GET | `/admin/api/2020-10/inventory_items/{inventory_item_id}.json` | Retrieves a single inventory item by ID | [View](../operations/get-inventory-items-param-inventory-item-id.md) |
| PUT | `/admin/api/2020-10/inventory_items/{inventory_item_id}.json` | Updates an existing inventory item | [View](../operations/update-inventory-items-param-inventory-item-id.md) |
| GET | `/admin/api/2020-10/inventory_levels.json` | Retrieves a list of inventory levels.
          You must include inventory_item_ids, location_ids, or both as filter parameters.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-inventory-levels.md) |
| DELETE | `/admin/api/2020-10/inventory_levels.json` | Deletes an inventory level of an inventory item at a location.
          Deleting an inventory level for an inventory item removes that item from the specified location.
          Every inventory item must have at least one inventory level. To move inventory to another location,
          first connect the inventory item to another location, and then delete the previous inventory level. | [View](../operations/delete-inventory-levels.md) |
| POST | `/admin/api/2020-10/inventory_levels/adjust.json` | Adjusts the inventory level of an inventory item at a single location | [View](../operations/create-inventory-levels-adjust.md) |
| POST | `/admin/api/2020-10/inventory_levels/connect.json` | Connects an inventory item to a location by creating an inventory level at that location.
        When connecting inventory items to locations, it's important to understand the rules around
        fulfillment service locations. | [View](../operations/create-inventory-levels-connect.md) |
| POST | `/admin/api/2020-10/inventory_levels/set.json` | Sets the inventory level for an inventory item at a location.
          If the specified location is not connected, it will be automatically connected first.
          When connecting inventory items to locations, it's important to understand the rules around
          fulfillment service locations. | [View](../operations/create-inventory-levels-set.md) |
| GET | `/admin/api/2020-10/locations.json` | Retrieves a list of locations | [View](../operations/get-locations.md) |
| GET | `/admin/api/2020-10/locations/{location_id}.json` | Retrieves a single location by its ID | [View](../operations/get-locations-param-location-id.md) |
| GET | `/admin/api/2020-10/locations/count.json` | Retrieves a count of locations | [View](../operations/get-locations-count.md) |
| GET | `/admin/api/2020-10/locations/{location_id}/inventory_levels.json` | Retrieves a list of inventory levels for a location. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-locations-param-location-id-inventory-levels.md) |
| GET | `/admin/api/2020-10/metafields.json` | Retrieves a list of metafields that belong to a Product Image resource. | [View](../operations/get-metafields.md) |
| POST | `/admin/api/2020-10/metafields.json` | Creates a new metafield for a resource. | [View](../operations/create-metafields.md) |
| GET | `/admin/api/2020-10/metafields/count.json` | Retrieves a count of a resource's metafields. | [View](../operations/get-metafields-count.md) |
| GET | `/admin/api/2020-10/metafields/{metafield_id}.json` | Retrieves a single metafield from a resource by its ID. | [View](../operations/get-metafields-param-metafield-id.md) |
| PUT | `/admin/api/2020-10/metafields/{metafield_id}.json` | Updates a metafield. | [View](../operations/update-metafields-param-metafield-id.md) |
| DELETE | `/admin/api/2020-10/metafields/{metafield_id}.json` | Deletes a metafield by its ID. | [View](../operations/delete-metafields-param-metafield-id.md) |
| GET | `/admin/api/2020-10/blogs/{blog_id}/articles.json` | Retrieves a list of all articles from a blog. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-blogs-param-blog-id-articles.md) |
| POST | `/admin/api/2020-10/blogs/{blog_id}/articles.json` | Creates an article for a blog | [View](../operations/create-blogs-param-blog-id-articles.md) |
| GET | `/admin/api/2020-10/blogs/{blog_id}/articles/count.json` | Retrieves a count of all articles from a blog | [View](../operations/get-blogs-param-blog-id-articles-count.md) |
| GET | `/admin/api/2020-10/blogs/{blog_id}/articles/{article_id}.json` | Retrieves a single article | [View](../operations/get-blogs-param-blog-id-articles-param-article-id.md) |
| PUT | `/admin/api/2020-10/blogs/{blog_id}/articles/{article_id}.json` | Updates an article | [View](../operations/update-blogs-param-blog-id-articles-param-article-id.md) |
| DELETE | `/admin/api/2020-10/blogs/{blog_id}/articles/{article_id}.json` | Deletes an article | [View](../operations/delete-blogs-param-blog-id-articles-param-article-id.md) |
| GET | `/admin/api/2020-10/articles/authors.json` | Retrieves a list all of article authors | [View](../operations/get-articles-authors.md) |
| GET | `/admin/api/2020-10/articles/tags.json` | Retrieves a list of all the tags | [View](../operations/get-articles-tags.md) |
| GET | `/admin/api/2020-10/themes/{theme_id}/assets.json` | Retrieves a single asset for a theme by its key.
          To retrieve a single asset, include asset[key]=#{asset_key} as a request parameter. For example, to retrieve the asset with a key of templates/index.liquid, the request might be /admin/themes/828155753/assets.json?asset[key]=templates/index.liquid.
          For more information on the key property, see Asset properties. | [View](../operations/get-themes-param-theme-id-assets.md) |
| PUT | `/admin/api/2020-10/themes/{theme_id}/assets.json` | Creates or updates an asset for a theme.
          In the PUT request, you can include the src or source_key property to create the asset from an existing file. | [View](../operations/update-themes-param-theme-id-assets.md) |
| DELETE | `/admin/api/2020-10/themes/{theme_id}/assets.json` | Deletes an asset from a theme. | [View](../operations/delete-themes-param-theme-id-assets.md) |
| GET | `/admin/api/2020-10/redirects.json` | Retrieves a list of URL redirects. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-redirects.md) |
| POST | `/admin/api/2020-10/redirects.json` | Creates a redirect. When you provide a full URL as the value of the path property, it will be saved as an absolute path without the domain.
          For example, "path": "http://www.johns-apparel.com/springwear" will be saved as "path": "springwear". | [View](../operations/create-redirects.md) |
| GET | `/admin/api/2020-10/redirects/count.json` | Retrieves a count of URL redirects | [View](../operations/get-redirects-count.md) |
| GET | `/admin/api/2020-10/redirects/{redirect_id}.json` | Retrieves a single redirect | [View](../operations/get-redirects-param-redirect-id.md) |
| PUT | `/admin/api/2020-10/redirects/{redirect_id}.json` | Updates an existing redirect | [View](../operations/update-redirects-param-redirect-id.md) |
| DELETE | `/admin/api/2020-10/redirects/{redirect_id}.json` | Deletes a redirect | [View](../operations/delete-redirects-param-redirect-id.md) |
| GET | `/admin/api/2020-10/script_tags.json` | Retrieves a list of all script tags. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-script-tags.md) |
| POST | `/admin/api/2020-10/script_tags.json` | Creates a new script tag | [View](../operations/create-script-tags.md) |
| GET | `/admin/api/2020-10/script_tags/count.json` | Retrieves a count of all script tags | [View](../operations/get-script-tags-count.md) |
| GET | `/admin/api/2020-10/script_tags/{script_tag_id}.json` | Retrieves a single script tag | [View](../operations/get-script-tags-param-script-tag-id.md) |
| PUT | `/admin/api/2020-10/script_tags/{script_tag_id}.json` | Updates a script tag | [View](../operations/update-script-tags-param-script-tag-id.md) |
| DELETE | `/admin/api/2020-10/script_tags/{script_tag_id}.json` | Deletes a script tag | [View](../operations/delete-script-tags-param-script-tag-id.md) |
| GET | `/admin/api/2020-10/themes.json` | Retrieves a list of themes. | [View](../operations/get-themes.md) |
| POST | `/admin/api/2020-10/themes.json` | Creates a theme by providing the public URL of a ZIP file that contains the theme.
          A new theme is always unpublished by default. To publish a theme when you create it, include
          "role": "main" in the POST request. The theme will be published only after all
          of its files have been extracted and stored by Shopify, which might take a couple of minutes. | [View](../operations/create-themes.md) |
| GET | `/admin/api/2020-10/themes/{theme_id}.json` | Retrieves a single theme. | [View](../operations/get-themes-param-theme-id.md) |
| PUT | `/admin/api/2020-10/themes/{theme_id}.json` | Updates an existing theme. | [View](../operations/update-themes-param-theme-id.md) |
| DELETE | `/admin/api/2020-10/themes/{theme_id}.json` | Deletes a theme. | [View](../operations/delete-themes-param-theme-id.md) |
| GET | `/admin/api/2020-10/checkouts/count.json` | Retrieves a count of checkouts from the past 90 days | [View](../operations/get-checkouts-count.md) |
| POST | `/admin/api/2020-10/checkouts.json` | Creates a checkout | [View](../operations/create-checkouts.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/risks.json` | Retrieves a list of all order risks for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-orders-param-order-id-risks.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/risks.json` | Creates an order risk for an order | [View](../operations/create-orders-param-order-id-risks.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/risks/{risk_id}.json` | Retrieves a single order risk by its ID | [View](../operations/get-orders-param-order-id-risks-param-risk-id.md) |
| PUT | `/admin/api/2020-10/orders/{order_id}/risks/{risk_id}.json` | Updates an order risk
          
          
            Note
            You cannot modify an order risk that was created by another application. | [View](../operations/update-orders-param-order-id-risks-param-risk-id.md) |
| DELETE | `/admin/api/2020-10/orders/{order_id}/risks/{risk_id}.json` | Deletes an order risk for an order
          
          
            Note
            You cannot delete an order risk that was created by another application. | [View](../operations/delete-orders-param-order-id-risks-param-risk-id.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/refunds.json` | Retrieves a list of refunds for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-orders-param-order-id-refunds.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/refunds.json` | Caution
            For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
          
          Creates a refund. Use the calculate endpoint to produce the transactions to submit.
          
          
            Note
            When you use this endpoint with a Partner development store or a trial store, you can create only five refunds per minute. | [View](../operations/create-orders-param-order-id-refunds.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/refunds/{refund_id}.json` | Retrieves a specific refund. | [View](../operations/get-orders-param-order-id-refunds-param-refund-id.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/refunds/calculate.json` | Caution
          For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
        
          Calculates refund transactions based on line items and shipping. When you want to create a refund,
          you should first use the calculate endpoint to generate accurate refund transactions. Specify the line items
          that are being refunded, their quantity and restock instructions, and whether you intend to refund
          shipping costs. If the restock instructions can't be met—for example, because you try to return more items than have been
          fulfilled—then the endpoint returns modified restock instructions. You can then use the response in the body of the request to create the actual refund.
          The response includes a transactions object with "kind": "suggested_refund",
          which must to be changed to "kind" : "refund" for the refund to be accepted. | [View](../operations/create-orders-param-order-id-refunds-calculate.md) |
| GET | `/admin/api/2020-10/gift_cards.json` | Retrieves a list of gift cards. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-gift-cards.md) |
| POST | `/admin/api/2020-10/gift_cards.json` | Creates a gift card | [View](../operations/create-gift-cards.md) |
| GET | `/admin/api/2020-10/gift_cards/{gift_card_id}.json` | Retrieves a single gift card by its ID | [View](../operations/get-gift-cards-param-gift-card-id.md) |
| PUT | `/admin/api/2020-10/gift_cards/{gift_card_id}.json` | Updates an existing gift card.
          The gift card's balance can't be changed via the API. You can change only the expiry date, note, and template suffix. | [View](../operations/update-gift-cards-param-gift-card-id.md) |
| GET | `/admin/api/2020-10/gift_cards/count.json` | Retrieves a count of gift cards | [View](../operations/get-gift-cards-count.md) |
| POST | `/admin/api/2020-10/gift_cards/{gift_card_id}/disable.json` | Disables a gift card. Disabling a gift card can't be undone. | [View](../operations/create-gift-cards-param-gift-card-id-disable.md) |
| GET | `/admin/api/2020-10/gift_cards/search.json` | Searches for gift cards that match a supplied query. The following fields are indexed by search:
          
            created_at
            updated_at
            disabled_at
            balance
            initial_value
            amount_spent
            email
            last_characters
          
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-gift-cards-search.md) |
| GET | `/admin/api/2020-10/users.json` | Retrieves a list of all users. Note: As of version 2021-01, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-users.md) |
| GET | `/admin/api/2020-10/users/{user_id}.json` | Retrieves a single user | [View](../operations/get-users-param-user-id.md) |
| GET | `/admin/api/2020-10/users/current.json` | Retrieves information about the user account associated with the access token used to make this API request. This request works only when the access token was created for a specific user of the shop. | [View](../operations/get-users-current.md) |
| GET | `/admin/api/2020-10/collects.json` | Retrieves a list of collects. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-collects.md) |
| POST | `/admin/api/2020-10/collects.json` | Adds a product to a custom collection. | [View](../operations/create-collects.md) |
| GET | `/admin/api/2020-10/collects/{collect_id}.json` | Retrieves a specific collect by its ID. | [View](../operations/get-collects-param-collect-id.md) |
| DELETE | `/admin/api/2020-10/collects/{collect_id}.json` | Removes a product from a collection. | [View](../operations/delete-collects-param-collect-id.md) |
| GET | `/admin/api/2020-10/collects/count.json` | Retrieves a count of collects. | [View](../operations/get-collects-count.md) |
| GET | `/admin/api/2020-10/collections/{collection_id}.json` | Retrieves a single collection | [View](../operations/get-collections-param-collection-id.md) |
| GET | `/admin/api/2020-10/collections/{collection_id}/products.json` | Retrieve a list of products belonging to a collection. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.. The products returned are sorted by the collection's sort order. | [View](../operations/get-collections-param-collection-id-products.md) |
| GET | `/admin/api/2020-10/custom_collections.json` | Retrieves a list of custom collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-custom-collections.md) |
| POST | `/admin/api/2020-10/custom_collections.json` | Creates a custom collection | [View](../operations/create-custom-collections.md) |
| GET | `/admin/api/2020-10/custom_collections/count.json` | Retrieves a count of custom collections | [View](../operations/get-custom-collections-count.md) |
| GET | `/admin/api/2020-10/custom_collections/{custom_collection_id}.json` | Retrieves a single custom collection | [View](../operations/get-custom-collections-param-custom-collection-id.md) |
| PUT | `/admin/api/2020-10/custom_collections/{custom_collection_id}.json` | Updates an existing custom collection | [View](../operations/update-custom-collections-param-custom-collection-id.md) |
| DELETE | `/admin/api/2020-10/custom_collections/{custom_collection_id}.json` | Deletes a custom collection | [View](../operations/delete-custom-collections-param-custom-collection-id.md) |
| GET | `/admin/api/2020-10/products.json` | Retrieves a list of products. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-products.md) |
| POST | `/admin/api/2020-10/products.json` | Creates a new product.
          If you want to set the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/create-products.md) |
| GET | `/admin/api/2020-10/products/count.json` | Retrieves a count of products. | [View](../operations/get-products-count.md) |
| GET | `/admin/api/2020-10/products/{product_id}.json` | Retrieves a single product. | [View](../operations/get-products-param-product-id.md) |
| PUT | `/admin/api/2020-10/products/{product_id}.json` | Updates a product and its variants and images.
          If you want to update the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/update-products-param-product-id.md) |
| DELETE | `/admin/api/2020-10/products/{product_id}.json` | Deletes a product. | [View](../operations/delete-products-param-product-id.md) |
| GET | `/admin/api/2020-10/products/{product_id}/images.json` | Get all product images | [View](../operations/get-products-param-product-id-images.md) |
| POST | `/admin/api/2020-10/products/{product_id}/images.json` | Create a new product image | [View](../operations/create-products-param-product-id-images.md) |
| GET | `/admin/api/2020-10/products/{product_id}/images/count.json` | Get a count of all product images | [View](../operations/get-products-param-product-id-images-count.md) |
| GET | `/admin/api/2020-10/products/{product_id}/images/{image_id}.json` | Get a single product image by id | [View](../operations/get-products-param-product-id-images-param-image-id.md) |
| PUT | `/admin/api/2020-10/products/{product_id}/images/{image_id}.json` | Modify an existing product image | [View](../operations/update-products-param-product-id-images-param-image-id.md) |
| DELETE | `/admin/api/2020-10/products/{product_id}/images/{image_id}.json` |  | [View](../operations/delete-products-param-product-id-images-param-image-id.md) |
| GET | `/admin/api/2020-10/smart_collections.json` | Retrieves a list of smart collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-smart-collections.md) |
| POST | `/admin/api/2020-10/smart_collections.json` | Creates a new smart collection using the specified rules. | [View](../operations/create-smart-collections.md) |
| GET | `/admin/api/2020-10/smart_collections/count.json` | Retrieves a count of smart collections | [View](../operations/get-smart-collections-count.md) |
| GET | `/admin/api/2020-10/smart_collections/{smart_collection_id}.json` | Retrieves a single smart collection | [View](../operations/get-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2020-10/smart_collections/{smart_collection_id}.json` | Updates an existing smart collection | [View](../operations/update-smart-collections-param-smart-collection-id.md) |
| DELETE | `/admin/api/2020-10/smart_collections/{smart_collection_id}.json` | Removes a smart collection | [View](../operations/delete-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2020-10/smart_collections/{smart_collection_id}/order.json` | Updates the ordering type of products in a smart collection | [View](../operations/update-smart-collections-param-smart-collection-id-order.md) |
| POST | `/admin/api/2020-10/checkouts/{token}/complete.json` | Completes a checkout | [View](../operations/create-checkouts-param-token-complete.md) |
| GET | `/admin/api/2020-10/checkouts/{token}.json` | Retrieves a checkout | [View](../operations/get-checkouts-param-token.md) |
| PUT | `/admin/api/2020-10/checkouts/{token}.json` | Modifies an existing checkout | [View](../operations/update-checkouts-param-token.md) |
| GET | `/admin/api/2020-10/checkouts/{token}/shipping_rates.json` | Retrieves a list of available shipping rates for the specified checkout. Implementers need to poll this endpoint until rates become available.
    Each shipping rate contains the checkout's new subtotal price, total tax, and total price in the event that this shipping rate is selected. This can be used to update the UI without performing further API requests.
    To apply a shipping rate, update the checkout's shipping line with the handle of the selected rate. | [View](../operations/get-checkouts-param-token-shipping-rates.md) |
| GET | `/admin/api/2020-10/collection_listings.json` | Retrieve collection listings that are published to your app. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-collection-listings.md) |
| GET | `/admin/api/2020-10/collection_listings/{collection_listing_id}/product_ids.json` | Retrieve product_ids that are published to a collection_id.       Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-collection-listings-param-collection-listing-id-product-ids.md) |
| GET | `/admin/api/2020-10/collection_listings/{collection_listing_id}.json` | Retrieve a specific collection listing that is published to your app | [View](../operations/get-collection-listings-param-collection-listing-id.md) |
| PUT | `/admin/api/2020-10/collection_listings/{collection_listing_id}.json` | Create a collection listing to publish a collection to your app | [View](../operations/update-collection-listings-param-collection-listing-id.md) |
| DELETE | `/admin/api/2020-10/collection_listings/{collection_listing_id}.json` | Delete a collection listing to unpublish a collection from your app | [View](../operations/delete-collection-listings-param-collection-listing-id.md) |
| GET | `/admin/api/2020-10/checkouts/{token}/payments.json` | Retrieves a list of payments on a particular checkout | [View](../operations/get-checkouts-param-token-payments.md) |
| POST | `/admin/api/2020-10/checkouts/{token}/payments.json` | Creates a payment on a checkout using the session ID returned by the card vault | [View](../operations/create-checkouts-param-token-payments.md) |
| GET | `/admin/api/2020-10/checkouts/{token}/payments/{payment_id}.json` | Retrieves the payment information for an existing payment | [View](../operations/get-checkouts-param-token-payments-param-payment-id.md) |
| GET | `/admin/api/2020-10/checkouts/{token}/payments/count.json` | Counts the number of payments attempted on a checkout | [View](../operations/get-checkouts-param-token-payments-count.md) |
| GET | `/admin/api/2020-10/assigned_fulfillment_orders.json` | Retrieves a list of fulfillment orders on a shop for a specific app. | [View](../operations/get-assigned-fulfillment-orders.md) |
| POST | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/cancellation_request.json` | Sends a cancellation request to the fulfillment service of a fulfillment order. | [View](../operations/create-fulfillment-orders-param-fulfillment-order-id-cancellation-request.md) |
| POST | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/cancellation_request/accept.json` | Accepts a cancellation request sent to a fulfillment service for a fulfillment order. | [View](../operations/create-fulfillment-orders-param-fulfillment-order-id-cancellation-request-accept.md) |
| POST | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/cancellation_request/reject.json` | Rejects a cancellation request sent to a fulfillment service for a fulfillment order. | [View](../operations/create-fulfillment-orders-param-fulfillment-order-id-cancellation-request-reject.md) |
| GET | `/admin/api/2020-10/carrier_services.json` | Retrieves a list of carrier services | [View](../operations/get-carrier-services.md) |
| POST | `/admin/api/2020-10/carrier_services.json` | Creates a carrier service | [View](../operations/create-carrier-services.md) |
| GET | `/admin/api/2020-10/carrier_services/{carrier_service_id}.json` | Retrieves a single carrier service by its ID | [View](../operations/get-carrier-services-param-carrier-service-id.md) |
| PUT | `/admin/api/2020-10/carrier_services/{carrier_service_id}.json` | Updates a carrier service. Only the app that creates a carrier service can update it. | [View](../operations/update-carrier-services-param-carrier-service-id.md) |
| DELETE | `/admin/api/2020-10/carrier_services/{carrier_service_id}.json` | Deletes a carrier service | [View](../operations/delete-carrier-services-param-carrier-service-id.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/fulfillments.json` | Retrieves fulfillments associated with an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-orders-param-order-id-fulfillments.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/fulfillments.json` | Create a fulfillment for the specified order and line items.
          The fulfillment's status depends on the line items in the order:
          
          If the line items in the fulfillment use a manual or custom fulfillment service, then the status of the returned fulfillment will be set immediately.
          If the line items use an external fulfillment service, then they will be queued for fulfillment and the status will be set to pending until the external fulfillment service has been invoked.
          
          
          A fulfillment might then transition to open, which implies it is being processed by the service, before transitioning to success when the items have shipped.
          If you don't specify line item IDs, then all unfulfilled and partially fulfilled line items for the order will be fulfilled.
          However, if an order is refunded or if any of its individual line items are refunded, then the order can't be fulfilled.
          
          All line items being fulfilled must have the same fulfillment service.
          
          
            Note
            If you are using this endpoint with a Partner development store or a trial store, then you can create no more than 5 new fulfillments per minute.
          
          About tracking urls
           If you're creating a fulfillment for a supported carrier, then you can send the tracking_company and tracking_numbers fields, and Shopify will generate the tracking_url for you. If you're creating a fulfillment for an unsupported carrier (not in the tracking_company list), then send the tracking_company, tracking_numbers, and tracking_urls fields.
           
          
            Note
            If you send an unsupported carrier without a tracking URL, then Shopify will still try to generate a valid tracking URL by using pattern matching on the tracking number. However, Shopify does not validate the tracking URL, so you should make sure that your tracking URL is correct for the order and fulfillment. | [View](../operations/create-orders-param-order-id-fulfillments.md) |
| GET | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/fulfillments.json` | Retrieves fulfillments associated with a fulfillment order. | [View](../operations/get-fulfillment-orders-param-fulfillment-order-id-fulfillments.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/fulfillments/count.json` | Retrieves a count of fulfillments associated with a specific order | [View](../operations/get-orders-param-order-id-fulfillments-count.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Retrieve a specific fulfillment | [View](../operations/get-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| PUT | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Update information associated with a fulfillment | [View](../operations/update-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| POST | `/admin/api/2020-10/fulfillments.json` | Creates a fulfillment for one or many fulfillment orders. The fulfillment orders are associated with the same order and are assigned to the same location. | [View](../operations/create-fulfillments.md) |
| POST | `/admin/api/2020-10/fulfillments/{fulfillment_id}/update_tracking.json` | Updates the tracking information for a fulfillment. | [View](../operations/create-fulfillments-param-fulfillment-id-update-tracking.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}/complete.json` | Mark a fulfillment as complete | [View](../operations/create-orders-param-order-id-fulfillments-param-fulfillment-id-complete.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}/open.json` | Mark a fulfillment as open | [View](../operations/create-orders-param-order-id-fulfillments-param-fulfillment-id-open.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}/cancel.json` | Cancel a fulfillment for a specific order ID | [View](../operations/create-orders-param-order-id-fulfillments-param-fulfillment-id-cancel.md) |
| POST | `/admin/api/2020-10/fulfillments/{fulfillment_id}/cancel.json` | Cancels a fulfillment. | [View](../operations/create-fulfillments-param-fulfillment-id-cancel.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}/events.json` | Retrieves a list of fulfillment events for a specific fulfillment | [View](../operations/get-orders-param-order-id-fulfillments-param-fulfillment-id-events.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}/events.json` | Creates a fulfillment event | [View](../operations/create-orders-param-order-id-fulfillments-param-fulfillment-id-events.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}/events/{event_id}.json` | Retrieves a specific fulfillment event | [View](../operations/get-orders-param-order-id-fulfillments-param-fulfillment-id-events-param-event-id.md) |
| DELETE | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}/events/{event_id}.json` | Deletes a fulfillment event | [View](../operations/delete-orders-param-order-id-fulfillments-param-fulfillment-id-events-param-event-id.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/fulfillment_orders.json` | Retrieves a list of fulfillment orders for a specific order. | [View](../operations/get-orders-param-order-id-fulfillment-orders.md) |
| GET | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}.json` | Retrieves a specific fulfillment order. | [View](../operations/get-fulfillment-orders-param-fulfillment-order-id.md) |
| POST | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/cancel.json` | Marks a fulfillment order as cancelled. | [View](../operations/create-fulfillment-orders-param-fulfillment-order-id-cancel.md) |
| POST | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/close.json` | Marks an in progress fulfillment order as incomplete, indicating the fulfillment service
        is unable to ship any remaining items and intends to close the fulfillment order. | [View](../operations/create-fulfillment-orders-param-fulfillment-order-id-close.md) |
| POST | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/move.json` | Moves a fulfillment order from one merchant managed location to another merchant managed location. | [View](../operations/create-fulfillment-orders-param-fulfillment-order-id-move.md) |
| POST | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/fulfillment_request.json` | Sends a fulfillment request to the fulfillment service of a fulfillment order. | [View](../operations/create-fulfillment-orders-param-fulfillment-order-id-fulfillment-request.md) |
| POST | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/fulfillment_request/accept.json` | Accepts a fulfillment request sent to a fulfillment service for a fulfillment order. | [View](../operations/create-fulfillment-orders-param-fulfillment-order-id-fulfillment-request-accept.md) |
| POST | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/fulfillment_request/reject.json` | Rejects a fulfillment request sent to a fulfillment service for a fulfillment order. | [View](../operations/create-fulfillment-orders-param-fulfillment-order-id-fulfillment-request-reject.md) |
| GET | `/admin/api/2020-10/fulfillment_services.json` |  | [View](../operations/get-fulfillment-services.md) |
| POST | `/admin/api/2020-10/fulfillment_services.json` | To create a fulfillment service, you can also use a cURL request that uses that fulfillment_service.json payload:
          Copy  curl -X POST -d @fulfillment_service.json -H"Accept:application/json" -H"Content-Type:application/json" -H"X-Shopify-Access-Token:THE_TOKEN_GOES_HERE" https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services
          
          Where THE_TOKEN_GOES_HERE is replaced by the OAuth token given to you by Shopify and https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services is replaced by the authorized shop's URL. | [View](../operations/create-fulfillment-services.md) |
| GET | `/admin/api/2020-10/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/get-fulfillment-services-param-fulfillment-service-id.md) |
| PUT | `/admin/api/2020-10/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/update-fulfillment-services-param-fulfillment-service-id.md) |
| DELETE | `/admin/api/2020-10/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/delete-fulfillment-services-param-fulfillment-service-id.md) |
| GET | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/locations_for_move.json` | Retrieves a list of locations that a fulfillment order can potentially move to.
          The resulting list is sorted alphabetically in ascending order by location name. | [View](../operations/get-fulfillment-orders-param-fulfillment-order-id-locations-for-move.md) |
| GET | `/admin/api/2020-10/shopify_payments/balance.json` | Retrieves the account's current balance. | [View](../operations/get-shopify-payments-balance.md) |
| GET | `/admin/api/2020-10/shopify_payments/payouts.json` | Retrieves a list of all payouts ordered by payout date, with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-shopify-payments-payouts.md) |
| GET | `/admin/api/2020-10/shopify_payments/payouts/{payout_id}.json` | Retrieves a single payout by id. | [View](../operations/get-shopify-payments-payouts-param-payout-id.md) |
| GET | `/admin/api/2020-10/countries.json` | Retrieves a list of countries. | [View](../operations/get-countries.md) |
| POST | `/admin/api/2020-10/countries.json` | Caution
  As of version 2020-10, the tax field is deprecated.

Creates a country. | [View](../operations/create-countries.md) |
| GET | `/admin/api/2020-10/countries/count.json` | Retrieves a count of countries. | [View](../operations/get-countries-count.md) |
| GET | `/admin/api/2020-10/countries/{country_id}.json` | Retrieves a specific county. | [View](../operations/get-countries-param-country-id.md) |
| PUT | `/admin/api/2020-10/countries/{country_id}.json` | Caution
  As of version 2020-10, the tax field is deprecated.

Updates an existing country. | [View](../operations/update-countries-param-country-id.md) |
| DELETE | `/admin/api/2020-10/countries/{country_id}.json` | Deletes a country. | [View](../operations/delete-countries-param-country-id.md) |
| GET | `/admin/api/2020-10/currencies.json` | Retrieves a list of currencies enabled on a shop | [View](../operations/get-currencies.md) |
| GET | `/admin/api/2020-10/policies.json` | Retrieves a list of the shop's policies | [View](../operations/get-policies.md) |
| GET | `/admin/api/2020-10/countries/{country_id}/provinces.json` | Retrieves a list of provinces | [View](../operations/get-countries-param-country-id-provinces.md) |
| GET | `/admin/api/2020-10/countries/{country_id}/provinces/count.json` | Retrieves a count of provinces for a country | [View](../operations/get-countries-param-country-id-provinces-count.md) |
| GET | `/admin/api/2020-10/countries/{country_id}/provinces/{province_id}.json` | Retrieves a single province for a country | [View](../operations/get-countries-param-country-id-provinces-param-province-id.md) |
| PUT | `/admin/api/2020-10/countries/{country_id}/provinces/{province_id}.json` | Caution
  As of version 2020-10, the tax field is deprecated.

Updates an existing province for a country. | [View](../operations/update-countries-param-country-id-provinces-param-province-id.md) |
| GET | `/admin/api/2020-10/shipping_zones.json` | Get a list of all shipping zones | [View](../operations/get-shipping-zones.md) |
| GET | `/admin/api/2020-10/shop.json` | Retrieves the shop's configuration | [View](../operations/get-shop.md) |
| GET | `/admin/api/2020-10/tender_transactions.json` | Retrieves a list of tender transactions. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-tender-transactions.md) |
