# GET /v1/radar/early_fraud_warnings/{early_fraud_warning}

**Resource:** [radar](../resources/radar.md)
**Retrieve an early fraud warning**
**Operation ID:** `GetRadarEarlyFraudWarningsEarlyFraudWarning`

<p>Retrieves the details of an early fraud warning that has previously been created. </p>

<p>Please refer to the <a href="#early_fraud_warning_object">early fraud warning</a> object reference for more details.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `early_fraud_warning` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[radar.early_fraud_warning](../schemas/radar-early/radar-early-fraud-warning.md)

