# GET /v1/sources/{source}

**Resource:** [sources](../resources/sources.md)
**Retrieve a source**
**Operation ID:** `GetSourcesSource`

<p>Retrieves an existing source object. Supply the unique source ID from a source creation request and Stripe will return the corresponding up-to-date source object information.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `client_secret` | query | string | No | The client secret of the source. Required if a publishable key is used to retrieve the source. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `source` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[source](../schemas/source/source.md)

