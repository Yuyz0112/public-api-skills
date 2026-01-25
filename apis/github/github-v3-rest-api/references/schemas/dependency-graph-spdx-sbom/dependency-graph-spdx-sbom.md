# dependency-graph-spdx-sbom

A schema for the SPDX JSON format returned by the Dependency Graph.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sbom` | object | Yes |  |

## Nested Fields

### `sbom`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `SPDXID` | string | Yes | The SPDX identifier for the SPDX document. |
| `spdxVersion` | string | Yes | The version of the SPDX specification that this document conforms to. |
| `comment` | string | No | An optional comment about the SPDX document. |
| `creationInfo` | object | Yes |  |
| `name` | string | Yes | The name of the SPDX document. |
| `dataLicense` | string | Yes | The license under which the SPDX document is licensed. |
| `documentNamespace` | string | Yes | The namespace for the SPDX document. |
| `packages` | object[] | Yes |  |
| `relationships` | object[] | No |  |

#### `sbom.creationInfo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | string | Yes | The date and time the SPDX document was created. |
| `creators` | string[] | Yes | The tools that were used to generate the SPDX document. |

#### `sbom.packages`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `SPDXID` | string | No | A unique SPDX identifier for the package. |
| `name` | string | No | The name of the package. |
| `versionInfo` | string | No | The version of the package. If the package does not have an exact version specified,
a version range is given. |
| `downloadLocation` | string | No | The location where the package can be downloaded,
or NOASSERTION if this has not been determined. |
| `filesAnalyzed` | boolean | No | Whether the package's file content has been subjected to
analysis during the creation of the SPDX document. |
| `licenseConcluded` | string | No | The license of the package as determined while creating the SPDX document. |
| `licenseDeclared` | string | No | The license of the package as declared by its author, or NOASSERTION if this information
was not available when the SPDX document was created. |
| `supplier` | string | No | The distribution source of this package, or NOASSERTION if this was not determined. |
| `copyrightText` | string | No | The copyright holders of the package, and any dates present with those notices, if available. |
| `externalRefs` | object[] | No |  |

#### `sbom.relationships`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `relationshipType` | string | No | The type of relationship between the two SPDX elements. |
| `spdxElementId` | string | No | The SPDX identifier of the package that is the source of the relationship. |
| `relatedSpdxElement` | string | No | The SPDX identifier of the package that is the target of the relationship. |

