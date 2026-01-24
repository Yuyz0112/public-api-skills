# GET /v1/entitlements/features/{id}

**Resource:** [entitlements](../resources/entitlements.md)
**Retrieve a feature**
**Operation ID:** `GetEntitlementsFeaturesId`

<p>Retrieves a feature</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes | The ID of the feature. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[entitlements.feature](../schemas/entitlements-feature/entitlements-feature.md)

