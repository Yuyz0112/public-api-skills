# GET /v1/entitlements/active_entitlements/{id}

**Resource:** [entitlements](../resources/entitlements.md)
**Retrieve an active entitlement**
**Operation ID:** `GetEntitlementsActiveEntitlementsId`

<p>Retrieve an active entitlement</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes | The ID of the entitlement. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[entitlements.active_entitlement](../schemas/entitlements-active/entitlements-active-entitlement.md)

