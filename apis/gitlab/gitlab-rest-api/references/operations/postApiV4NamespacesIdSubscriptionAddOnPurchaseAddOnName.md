# POST /api/v4/namespaces/{id}/subscription_add_on_purchase/{add_on_name}

**Resource:** [Add on purchases](../resources/Add-on-purchases.md)
**[DEPRECATED] Create an add-on purchase for the namespace**
**Operation ID:** `postApiV4NamespacesIdSubscriptionAddOnPurchaseAddOnName`

Creates a subscription add-on record for the given namespaces and add-on

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesGitlabSubscriptionsAddOnPurchase](../schemas/APIEntitiesGitlabSubscriptionsAddOnPurchase/APIEntitiesGitlabSubscriptionsAddOnPurchase.md)

