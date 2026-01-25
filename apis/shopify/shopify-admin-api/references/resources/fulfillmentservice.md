# fulfillmentservice

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/fetch_tracking_numbers` | Get tracking numbers for orders | [View](../operations/deprecated-unknown-version-get-fetch-tracking-numbers.md) |
| GET | `/fetch_stock` | Get inventory levels | [View](../operations/deprecated-unknown-version-get-fetch-stock.md) |
| GET | `/admin/api/2020-01/fulfillment_services.json` |  | [View](../operations/deprecated-202001-get-fulfillment-services.md) |
| POST | `/admin/api/2020-01/fulfillment_services.json` | To create a fulfillment service, you can also use a cURL request that uses that fulfillment_service.json payload:
          Copy  curl -X POST -d @fulfillment_service.json -H"Accept:application/json" -H"Content-Type:application/json" -H"X-Shopify-Access-Token:THE_TOKEN_GOES_HERE" https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services
          
          Where THE_TOKEN_GOES_HERE is replaced by the OAuth token given to you by Shopify and https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services is replaced by the authorized shop's URL. | [View](../operations/deprecated-202001-create-fulfillment-services.md) |
| GET | `/admin/api/2020-01/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202001-get-fulfillment-services-param-fulfillment-service-id.md) |
| PUT | `/admin/api/2020-01/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202001-update-fulfillment-services-param-fulfillment-service-id.md) |
| DELETE | `/admin/api/2020-01/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202001-delete-fulfillment-services-param-fulfillment-service-id.md) |
| GET | `/admin/api/2020-04/fulfillment_services.json` |  | [View](../operations/deprecated-202004-get-fulfillment-services.md) |
| POST | `/admin/api/2020-04/fulfillment_services.json` | To create a fulfillment service, you can also use a cURL request that uses that fulfillment_service.json payload:
          Copy  curl -X POST -d @fulfillment_service.json -H"Accept:application/json" -H"Content-Type:application/json" -H"X-Shopify-Access-Token:THE_TOKEN_GOES_HERE" https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services
          
          Where THE_TOKEN_GOES_HERE is replaced by the OAuth token given to you by Shopify and https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services is replaced by the authorized shop's URL. | [View](../operations/deprecated-202004-create-fulfillment-services.md) |
| GET | `/admin/api/2020-04/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202004-get-fulfillment-services-param-fulfillment-service-id.md) |
| PUT | `/admin/api/2020-04/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202004-update-fulfillment-services-param-fulfillment-service-id.md) |
| DELETE | `/admin/api/2020-04/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202004-delete-fulfillment-services-param-fulfillment-service-id.md) |
| GET | `/admin/api/2020-07/fulfillment_services.json` |  | [View](../operations/deprecated-202007-get-fulfillment-services.md) |
| POST | `/admin/api/2020-07/fulfillment_services.json` | To create a fulfillment service, you can also use a cURL request that uses that fulfillment_service.json payload:
          Copy  curl -X POST -d @fulfillment_service.json -H"Accept:application/json" -H"Content-Type:application/json" -H"X-Shopify-Access-Token:THE_TOKEN_GOES_HERE" https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services
          
          Where THE_TOKEN_GOES_HERE is replaced by the OAuth token given to you by Shopify and https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services is replaced by the authorized shop's URL. | [View](../operations/deprecated-202007-create-fulfillment-services.md) |
| GET | `/admin/api/2020-07/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202007-get-fulfillment-services-param-fulfillment-service-id.md) |
| PUT | `/admin/api/2020-07/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202007-update-fulfillment-services-param-fulfillment-service-id.md) |
| DELETE | `/admin/api/2020-07/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202007-delete-fulfillment-services-param-fulfillment-service-id.md) |
| GET | `/admin/api/2020-10/fulfillment_services.json` |  | [View](../operations/get-fulfillment-services.md) |
| POST | `/admin/api/2020-10/fulfillment_services.json` | To create a fulfillment service, you can also use a cURL request that uses that fulfillment_service.json payload:
          Copy  curl -X POST -d @fulfillment_service.json -H"Accept:application/json" -H"Content-Type:application/json" -H"X-Shopify-Access-Token:THE_TOKEN_GOES_HERE" https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services
          
          Where THE_TOKEN_GOES_HERE is replaced by the OAuth token given to you by Shopify and https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services is replaced by the authorized shop's URL. | [View](../operations/create-fulfillment-services.md) |
| GET | `/admin/api/2020-10/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/get-fulfillment-services-param-fulfillment-service-id.md) |
| PUT | `/admin/api/2020-10/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/update-fulfillment-services-param-fulfillment-service-id.md) |
| DELETE | `/admin/api/2020-10/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/delete-fulfillment-services-param-fulfillment-service-id.md) |
| GET | `/admin/api/2021-01/fulfillment_services.json` |  | [View](../operations/deprecated-202101-get-fulfillment-services.md) |
| POST | `/admin/api/2021-01/fulfillment_services.json` | To create a fulfillment service, you can also use a cURL request that uses that fulfillment_service.json payload:
          Copy  curl -X POST -d @fulfillment_service.json -H"Accept:application/json" -H"Content-Type:application/json" -H"X-Shopify-Access-Token:THE_TOKEN_GOES_HERE" https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services
          
          Where THE_TOKEN_GOES_HERE is replaced by the OAuth token given to you by Shopify and https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services is replaced by the authorized shop's URL. | [View](../operations/deprecated-202101-create-fulfillment-services.md) |
| GET | `/admin/api/2021-01/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202101-get-fulfillment-services-param-fulfillment-service-id.md) |
| PUT | `/admin/api/2021-01/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202101-update-fulfillment-services-param-fulfillment-service-id.md) |
| DELETE | `/admin/api/2021-01/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-202101-delete-fulfillment-services-param-fulfillment-service-id.md) |
| GET | `/admin/api/unstable/fulfillment_services.json` |  | [View](../operations/deprecated-unstable-get-fulfillment-services.md) |
| POST | `/admin/api/unstable/fulfillment_services.json` | To create a fulfillment service, you can also use a cURL request that uses that fulfillment_service.json payload:
          Copy  curl -X POST -d @fulfillment_service.json -H"Accept:application/json" -H"Content-Type:application/json" -H"X-Shopify-Access-Token:THE_TOKEN_GOES_HERE" https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services
          
          Where THE_TOKEN_GOES_HERE is replaced by the OAuth token given to you by Shopify and https://AUTHORIZED_SHOP.myshopify.com/admin/fulfillment_services is replaced by the authorized shop's URL. | [View](../operations/deprecated-unstable-create-fulfillment-services.md) |
| GET | `/admin/api/unstable/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-unstable-get-fulfillment-services-param-fulfillment-service-id.md) |
| PUT | `/admin/api/unstable/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-unstable-update-fulfillment-services-param-fulfillment-service-id.md) |
| DELETE | `/admin/api/unstable/fulfillment_services/{fulfillment_service_id}.json` |  | [View](../operations/deprecated-unstable-delete-fulfillment-services-param-fulfillment-service-id.md) |
