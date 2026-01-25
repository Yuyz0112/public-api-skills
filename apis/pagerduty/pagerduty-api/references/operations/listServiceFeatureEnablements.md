# GET /services/{id}/enablements

**Resource:** [Services](../resources/Services.md)
**Get Enablements for a Service**
**Operation ID:** `listServiceFeatureEnablements`

<!-- theme: warning -->
> ### Limited GA
> This feature is in Limited General Availability for some customers with the PagerDuty AIOps add-on. Please contact your account team or Support to request access.

List all feature enablement settings for a service. Currently, only the `aiops` enablement is supported.

For any account with the AIOps product addon, every service will have AIOps features enabled by default.

**Warning conditions**:
- If the account is not entitled to use AIOps features, a warning will be returned alongside the enablement data.

Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The list of feature enablement settings for the service. |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

