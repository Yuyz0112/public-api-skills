# PUT /services/{id}/enablements/{feature_name}

**Resource:** [Services](../resources/Services.md)
**Update an Enablement for a Service**
**Operation ID:** `updateServiceFeatureEnablement`

<!-- theme: warning -->
> ### Limited GA
> This feature is in Limited General Availability for some customers with the PagerDuty AIOps add-on. Please contact your account team or Support to request access.

Update the feature enablement setting for a specific product addon on a service. This setting controls enabling or disabling the set of features contained within the addon.
Currently, only `aiops` is supported as a valid feature enablement.

**Warning conditions**:
- If the account is not entitled to use AIOps features, the setting will be updated, but a warning will be returned.

Scoped OAuth requires: `services.write`


## Request Body

The feature enablement setting to apply.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The feature enablement setting was updated. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

