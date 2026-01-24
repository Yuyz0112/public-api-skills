# GET /v1/issuing/physical_bundles/{physical_bundle}

**Resource:** [issuing](../resources/issuing.md)
**Retrieve a physical bundle**
**Operation ID:** `GetIssuingPhysicalBundlesPhysicalBundle`

<p>Retrieves a physical bundle object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `physical_bundle` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.physical_bundle](../schemas/issuing-physical/issuing-physical-bundle.md)

