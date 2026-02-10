# GET /api/v4/namespaces/{id}/subscription_add_on_purchase/{add_on_name}

**Resource:** [Add on purchases](../resources/Add-on-purchases.md)
**[DEPRECATED] Returns an add-on purchase for the namespace**
**Operation ID:** `getApiV4NamespacesIdSubscriptionAddOnPurchaseAddOnName`

Gets the add-on purchase record for the given namespace and add-on

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesGitlabSubscriptionsAddOnPurchase](../schemas/APIEntitiesGitlabSubscriptionsAddOnPurchase/APIEntitiesGitlabSubscriptionsAddOnPurchase.md)

