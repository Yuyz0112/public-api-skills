# Exports

Exports are a way to download data from Asana. The following types of exports are available:
* **Graph exports**: Export of data about objects starting from a parent object, such as a team, portfolio, or project.
* **Resource exports**: Bulk exports of resources such as tasks, teams, and messages for a workspace.
* **Organization exports**: Exports the complete data of an organization in JSON format. Please refer to [Organization exports](/reference/organization-exports) for more details.

## Graph exports
A `graph_export` object represents a request to export the
data about objects starting from a parent object. Parent object can be a team, portfolio, or project.

To create an export using this API:
1. Create a `graph_export` [request](/reference/createGraphExport) and store the ID that is returned.
2. Request the [jobs](/reference/getjob) endpoint every few minutes, until `status` field contains 'succeeded'.
3. Download the file located at the URL in the `download_url` field.

Exports can take a long time, from several minutes to a few hours for large portfolios.

*Note: Graph exports are only available to accounts of an
[Enterprise](https://asana.com/enterprise)/Enterprise+ organization.*

## Resource exports
A `resource_export` object represents a request to bulk export resources for a workspace.
To create an export using this API:
1. Create a `resource_export` [request](/reference/createResourceExport) and store the job ID that is returned.
2. Request the [jobs](/reference/getjob) endpoint at some interval, until `status` field contains 'succeeded' and a `download_url` is available.
3. Download the file located at the URL in the `download_url` field.

Exports can take a long time, from several minutes to a few hours for large workspaces.

*Note: Resource exports are only available to [Service Accounts](https://asana.com/guide/help/premium/service-accounts)
from an Enterprise+ organization or an organization with the Compliance Management Add-on.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/exports/graph` | Initiate a graph export | [View](../operations/createGraphExport.md) |
| POST | `/exports/resource` | Initiate a resource export | [View](../operations/createResourceExport.md) |
