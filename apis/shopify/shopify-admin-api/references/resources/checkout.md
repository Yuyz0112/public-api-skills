# checkout

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/admin/api/2020-01/checkouts.json` | Creates a checkout | [View](../operations/deprecated-202001-create-checkouts.md) |
| POST | `/admin/api/2020-04/checkouts.json` | Creates a checkout | [View](../operations/deprecated-202004-create-checkouts.md) |
| POST | `/admin/api/2020-07/checkouts.json` | Creates a checkout | [View](../operations/deprecated-202007-create-checkouts.md) |
| POST | `/admin/api/2020-10/checkouts.json` | Creates a checkout | [View](../operations/create-checkouts.md) |
| POST | `/admin/api/2021-01/checkouts.json` | Creates a checkout | [View](../operations/deprecated-202101-create-checkouts.md) |
| POST | `/admin/api/unstable/checkouts.json` | Creates a checkout | [View](../operations/deprecated-unstable-create-checkouts.md) |
| POST | `/admin/api/2020-01/checkouts/{token}/complete.json` | Completes a checkout | [View](../operations/deprecated-202001-create-checkouts-param-token-complete.md) |
| GET | `/admin/api/2020-01/checkouts/{token}.json` | Retrieves a checkout | [View](../operations/deprecated-202001-get-checkouts-param-token.md) |
| PUT | `/admin/api/2020-01/checkouts/{token}.json` | Modifies an existing checkout | [View](../operations/deprecated-202001-update-checkouts-param-token.md) |
| GET | `/admin/api/2020-01/checkouts/{token}/shipping_rates.json` | Retrieves a list of available shipping rates for the specified checkout. Implementers need to poll this endpoint until rates become available.
    Each shipping rate contains the checkout's new subtotal price, total tax, and total price in the event that this shipping rate is selected. This can be used to update the UI without performing further API requests.
    To apply a shipping rate, update the checkout's shipping line with the handle of the selected rate. | [View](../operations/deprecated-202001-get-checkouts-param-token-shipping-rates.md) |
| POST | `/admin/api/2020-04/checkouts/{token}/complete.json` | Completes a checkout | [View](../operations/deprecated-202004-create-checkouts-param-token-complete.md) |
| GET | `/admin/api/2020-04/checkouts/{token}.json` | Retrieves a checkout | [View](../operations/deprecated-202004-get-checkouts-param-token.md) |
| PUT | `/admin/api/2020-04/checkouts/{token}.json` | Modifies an existing checkout | [View](../operations/deprecated-202004-update-checkouts-param-token.md) |
| GET | `/admin/api/2020-04/checkouts/{token}/shipping_rates.json` | Retrieves a list of available shipping rates for the specified checkout. Implementers need to poll this endpoint until rates become available.
    Each shipping rate contains the checkout's new subtotal price, total tax, and total price in the event that this shipping rate is selected. This can be used to update the UI without performing further API requests.
    To apply a shipping rate, update the checkout's shipping line with the handle of the selected rate. | [View](../operations/deprecated-202004-get-checkouts-param-token-shipping-rates.md) |
| POST | `/admin/api/2020-07/checkouts/{token}/complete.json` | Completes a checkout | [View](../operations/deprecated-202007-create-checkouts-param-token-complete.md) |
| GET | `/admin/api/2020-07/checkouts/{token}.json` | Retrieves a checkout | [View](../operations/deprecated-202007-get-checkouts-param-token.md) |
| PUT | `/admin/api/2020-07/checkouts/{token}.json` | Modifies an existing checkout | [View](../operations/deprecated-202007-update-checkouts-param-token.md) |
| GET | `/admin/api/2020-07/checkouts/{token}/shipping_rates.json` | Retrieves a list of available shipping rates for the specified checkout. Implementers need to poll this endpoint until rates become available.
    Each shipping rate contains the checkout's new subtotal price, total tax, and total price in the event that this shipping rate is selected. This can be used to update the UI without performing further API requests.
    To apply a shipping rate, update the checkout's shipping line with the handle of the selected rate. | [View](../operations/deprecated-202007-get-checkouts-param-token-shipping-rates.md) |
| POST | `/admin/api/2020-10/checkouts/{token}/complete.json` | Completes a checkout | [View](../operations/create-checkouts-param-token-complete.md) |
| GET | `/admin/api/2020-10/checkouts/{token}.json` | Retrieves a checkout | [View](../operations/get-checkouts-param-token.md) |
| PUT | `/admin/api/2020-10/checkouts/{token}.json` | Modifies an existing checkout | [View](../operations/update-checkouts-param-token.md) |
| GET | `/admin/api/2020-10/checkouts/{token}/shipping_rates.json` | Retrieves a list of available shipping rates for the specified checkout. Implementers need to poll this endpoint until rates become available.
    Each shipping rate contains the checkout's new subtotal price, total tax, and total price in the event that this shipping rate is selected. This can be used to update the UI without performing further API requests.
    To apply a shipping rate, update the checkout's shipping line with the handle of the selected rate. | [View](../operations/get-checkouts-param-token-shipping-rates.md) |
| POST | `/admin/api/2021-01/checkouts/{token}/complete.json` | Completes a checkout | [View](../operations/deprecated-202101-create-checkouts-param-token-complete.md) |
| GET | `/admin/api/2021-01/checkouts/{token}.json` | Retrieves a checkout | [View](../operations/deprecated-202101-get-checkouts-param-token.md) |
| PUT | `/admin/api/2021-01/checkouts/{token}.json` | Modifies an existing checkout | [View](../operations/deprecated-202101-update-checkouts-param-token.md) |
| GET | `/admin/api/2021-01/checkouts/{token}/shipping_rates.json` | Retrieves a list of available shipping rates for the specified checkout. Implementers need to poll this endpoint until rates become available.
    Each shipping rate contains the checkout's new subtotal price, total tax, and total price in the event that this shipping rate is selected. This can be used to update the UI without performing further API requests.
    To apply a shipping rate, update the checkout's shipping line with the handle of the selected rate. | [View](../operations/deprecated-202101-get-checkouts-param-token-shipping-rates.md) |
| POST | `/admin/api/unstable/checkouts/{token}/complete.json` | Completes a checkout | [View](../operations/deprecated-unstable-create-checkouts-param-token-complete.md) |
| GET | `/admin/api/unstable/checkouts/{token}.json` | Retrieves a checkout | [View](../operations/deprecated-unstable-get-checkouts-param-token.md) |
| PUT | `/admin/api/unstable/checkouts/{token}.json` | Modifies an existing checkout | [View](../operations/deprecated-unstable-update-checkouts-param-token.md) |
| GET | `/admin/api/unstable/checkouts/{token}/shipping_rates.json` | Retrieves a list of available shipping rates for the specified checkout. Implementers need to poll this endpoint until rates become available.
    Each shipping rate contains the checkout's new subtotal price, total tax, and total price in the event that this shipping rate is selected. This can be used to update the UI without performing further API requests.
    To apply a shipping rate, update the checkout's shipping line with the handle of the selected rate. | [View](../operations/deprecated-unstable-get-checkouts-param-token-shipping-rates.md) |
