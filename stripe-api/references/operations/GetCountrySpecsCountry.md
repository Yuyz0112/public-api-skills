# GET /v1/country_specs/{country}

**Resource:** [country_specs](../resources/country-specs.md)
**Retrieve a Country Spec**
**Operation ID:** `GetCountrySpecsCountry`

<p>Returns a Country Spec for a given Country code.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `country` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[country_spec](../schemas/country/country-spec.md)

