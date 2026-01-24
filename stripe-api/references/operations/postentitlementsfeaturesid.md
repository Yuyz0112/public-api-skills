# POST /v1/entitlements/features/{id}

**Resource:** [entitlements](../resources/entitlements.md)
**Updates a feature**
**Operation ID:** `PostEntitlementsFeaturesId`

<p>Update a feature’s metadata or permanently deactivate it.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[entitlements.feature](../schemas/entitlements-feature/entitlements-feature.md)

