# GET /v1/exchange_rates/{rate_id}

**Resource:** [exchange_rates](../resources/exchange-rates.md)
**Retrieve an exchange rate**
**Operation ID:** `GetExchangeRatesRateId`

<p>[Deprecated] The <code>ExchangeRate</code> APIs are deprecated. Please use the <a href="https://docs.stripe.com/payments/currencies/localize-prices/fx-quotes-api">FX Quotes API</a> instead.</p>

<p>Retrieves the exchange rates from the given currency to every supported currency.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `rate_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[exchange_rate](../schemas/exchange/exchange-rate.md)

