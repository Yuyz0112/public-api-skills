# GET /v1/issuing/personalization_designs/{personalization_design}

**Resource:** [issuing](../resources/issuing.md)
**Retrieve a personalization design**
**Operation ID:** `GetIssuingPersonalizationDesignsPersonalizationDesign`

<p>Retrieves a personalization design object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

