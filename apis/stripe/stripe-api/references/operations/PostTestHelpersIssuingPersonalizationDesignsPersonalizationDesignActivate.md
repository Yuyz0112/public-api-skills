# POST /v1/test_helpers/issuing/personalization_designs/{personalization_design}/activate

**Resource:** [test_helpers](../resources/test-helpers.md)
**Activate a testmode personalization design**
**Operation ID:** `PostTestHelpersIssuingPersonalizationDesignsPersonalizationDesignActivate`

<p>Updates the <code>status</code> of the specified testmode personalization design object to <code>active</code>.</p>

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

