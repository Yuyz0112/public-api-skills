# Organization exports

An `organization_export` object represents a request to export the complete data of an organization in JSON format.

To export an organization using this API:

* Create an `organization_export`
  [request](/reference/createorganizationexport)
  and store the ID that is returned.
* Request the `organization_export` every few minutes, until the
  `state` field contains ‘finished’.
* Download the file located at the URL in the `download_url` field. * Exports can take a long time, from several minutes to a few hours
  for large organizations.


*Note: These endpoints are only available to [Service Accounts](https://asana.com/guide/help/premium/service-accounts) of an [Enterprise](https://asana.com/enterprise) organization.*

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/organization_exports` | Create an organization export request | [View](../operations/createOrganizationExport.md) |
| GET | `/organization_exports/{organization_export_gid}` | Get details on an org export request | [View](../operations/getOrganizationExport.md) |
