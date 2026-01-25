# ResourceExportRequest

A *resource_export* request starts a job to bulk export objects for one or more resources.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `workspace` | string | No | Gid of a workspace. |
| `export_request_parameters` | ResourceExportRequestParameter[] | No | An object containing the parameters for the export request. The keys of this object are the GIDs of the resources to be exported. The values are objects with additional parameters for each resource. |

