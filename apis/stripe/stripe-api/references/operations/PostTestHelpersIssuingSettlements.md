# POST /v1/test_helpers/issuing/settlements

**Resource:** [test_helpers](../resources/test-helpers.md)
**Create a test-mode settlement**
**Operation ID:** `PostTestHelpersIssuingSettlements`

<p>Allows the user to create an Issuing settlement.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.settlement](../schemas/issuing-settlement/issuing-settlement.md)

