# Geo

Operations related to geo.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/geo_sites` | Retrieves the available Geo sites | [View](../operations/getApiV4GeoSites.md) |
| POST | `/api/v4/geo_sites` | Create a new Geo site | [View](../operations/postApiV4GeoSites.md) |
| GET | `/api/v4/geo_sites/status` | Get status for all Geo sites | [View](../operations/getApiV4GeoSitesStatus.md) |
| GET | `/api/v4/geo_sites/{id}` | Get a single GeoSite | [View](../operations/getApiV4GeoSitesId.md) |
| PUT | `/api/v4/geo_sites/{id}` | Updates an existing Geo site | [View](../operations/putApiV4GeoSitesId.md) |
| DELETE | `/api/v4/geo_sites/{id}` | Remove the Geo site | [View](../operations/deleteApiV4GeoSitesId.md) |
| GET | `/api/v4/geo_sites/{id}/status` | Get metrics for a single Geo site | [View](../operations/getApiV4GeoSitesIdStatus.md) |
| POST | `/api/v4/geo_sites/{id}/repair` | Repair authentication of the Geo site | [View](../operations/postApiV4GeoSitesIdRepair.md) |
| GET | `/api/v4/geo_nodes` | Retrieves the available Geo nodes | [View](../operations/getApiV4GeoNodes.md) |
| POST | `/api/v4/geo_nodes` | Create a new Geo node | [View](../operations/postApiV4GeoNodes.md) |
| GET | `/api/v4/geo_nodes/status` | Get status for all Geo nodes | [View](../operations/getApiV4GeoNodesStatus.md) |
| GET | `/api/v4/geo_nodes/{id}` | Get a single GeoNode | [View](../operations/getApiV4GeoNodesId.md) |
| PUT | `/api/v4/geo_nodes/{id}` | Updates an existing Geo node | [View](../operations/putApiV4GeoNodesId.md) |
| DELETE | `/api/v4/geo_nodes/{id}` | Remove the Geo node | [View](../operations/deleteApiV4GeoNodesId.md) |
| GET | `/api/v4/geo_nodes/{id}/status` | Get metrics for a single Geo node | [View](../operations/getApiV4GeoNodesIdStatus.md) |
| POST | `/api/v4/geo_nodes/{id}/repair` | Repair authentication of the Geo node | [View](../operations/postApiV4GeoNodesIdRepair.md) |
| GET | `/api/v4/geo/proxy` | Returns a Geo proxy response | [View](../operations/getApiV4GeoProxy.md) |
| GET | `/api/v4/geo/retrieve/{replicable_name}/{replicable_id}` | Returns a replicable file from store (via CDN or sendfile) | [View](../operations/getApiV4GeoRetrieveReplicableNameReplicableId.md) |
| GET | `/api/v4/geo/repositories/{gl_repository}/pipeline_refs` | Returns the list of pipeline refs for the project | [View](../operations/getApiV4GeoRepositoriesGlRepositoryPipelineRefs.md) |
| POST | `/api/v4/geo/status` | Posts the current node status to the primary site | [View](../operations/postApiV4GeoStatus.md) |
| POST | `/api/v4/geo/proxy_git_ssh/info_refs_upload_pack` | Responsible for making HTTP GET /repo.git/info/refs?service=git-upload-pack
                  request from secondary gitlab-shell to primary | [View](../operations/postApiV4GeoProxyGitSshInfoRefsUploadPack.md) |
| POST | `/api/v4/geo/proxy_git_ssh/upload_pack` | Responsible for making HTTP POST /repo.git/git-upload-pack
                  request from secondary gitlab-shell to primary | [View](../operations/postApiV4GeoProxyGitSshUploadPack.md) |
| POST | `/api/v4/geo/proxy_git_ssh/info_refs_receive_pack` | Responsible for making HTTP GET /repo.git/info/refs?service=git-receive-pack
                  request from secondary gitlab-shell to primary | [View](../operations/postApiV4GeoProxyGitSshInfoRefsReceivePack.md) |
| POST | `/api/v4/geo/proxy_git_ssh/receive_pack` | Responsible for making HTTP POST /repo.git/info/refs?service=git-receive-pack
                  request from secondary gitlab-shell to primary | [View](../operations/postApiV4GeoProxyGitSshReceivePack.md) |
| POST | `/api/v4/geo/node_proxy/{id}/graphql` | Query the GraphQL endpoint of an existing Geo node | [View](../operations/postApiV4GeoNodeProxyIdGraphql.md) |
