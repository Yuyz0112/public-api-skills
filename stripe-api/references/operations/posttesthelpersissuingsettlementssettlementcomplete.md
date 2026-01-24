# POST /v1/test_helpers/issuing/settlements/{settlement}/complete

**Resource:** [test_helpers](../resources/test-helpers.md)
**Complete a test-mode settlement**
**Operation ID:** `PostTestHelpersIssuingSettlementsSettlementComplete`

<p>Allows the user to mark an Issuing settlement as complete.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `settlement` | path | string | Yes | The settlement token to mark as complete. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.settlement](../schemas/issuing-settlement/issuing-settlement.md)

