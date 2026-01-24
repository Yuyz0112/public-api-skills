# POST /v1/sources/{source}

**Resource:** [sources](../resources/sources.md)
**Update a source**
**Operation ID:** `PostSourcesSource`

<p>Updates the specified source by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

<p>This request accepts the <code>metadata</code> and <code>owner</code> as arguments. It is also possible to update type specific information for selected payment methods. Please refer to our <a href="/docs/sources">payment method guides</a> for more detail.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

