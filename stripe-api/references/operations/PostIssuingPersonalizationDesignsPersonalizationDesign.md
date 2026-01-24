# POST /v1/issuing/personalization_designs/{personalization_design}

**Resource:** [issuing](../resources/issuing.md)
**Update a personalization design**
**Operation ID:** `PostIssuingPersonalizationDesignsPersonalizationDesign`

<p>Updates a card personalization object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `personalization_design` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.personalization_design](../schemas/issuing-personalization/issuing-personalization-design.md)

