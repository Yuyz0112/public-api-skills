# Vulnerabilities

Operations related to vulnerabilities.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/api/v4/security/projects/{id}/vulnerability_exports` | Generate a project-level export | [View](../operations/postApiV4SecurityProjectsIdVulnerabilityExports.md) |
| POST | `/api/v4/security/groups/{id}/vulnerability_exports` | Generate a group-level export | [View](../operations/postApiV4SecurityGroupsIdVulnerabilityExports.md) |
| POST | `/api/v4/security/vulnerability_exports` | Generate an instance-level export | [View](../operations/postApiV4SecurityVulnerabilityExports.md) |
| GET | `/api/v4/security/vulnerability_exports/{id}` | Get a single vulnerability export | [View](../operations/getApiV4SecurityVulnerabilityExportsId.md) |
| GET | `/api/v4/security/vulnerability_exports/{id}/download` | Download a single vulnerability export | [View](../operations/getApiV4SecurityVulnerabilityExportsIdDownload.md) |
| POST | `/api/v4/security/projects/{id}/vulnerability_archive_exports` | Generate an export file for the archived vulnerabilities within the given date range | [View](../operations/postApiV4SecurityProjectsIdVulnerabilityArchiveExports.md) |
| GET | `/api/v4/security/vulnerability_archive_exports/{id}` | Get the vulnerability archive export entity | [View](../operations/getApiV4SecurityVulnerabilityArchiveExportsId.md) |
| GET | `/api/v4/security/vulnerability_archive_exports/{id}/download` | Download a single vulnerability export | [View](../operations/getApiV4SecurityVulnerabilityArchiveExportsIdDownload.md) |
| GET | `/api/v4/vulnerabilities/{id}/issue_links` | Get related issues for a vulnerability | [View](../operations/getApiV4VulnerabilitiesIdIssueLinks.md) |
| POST | `/api/v4/vulnerabilities/{id}/issue_links` | Relate an issue to a vulnerability | [View](../operations/postApiV4VulnerabilitiesIdIssueLinks.md) |
| DELETE | `/api/v4/vulnerabilities/{id}/issue_links/{issue_link_id}` | Delete a link between an issue and a vulnerability | [View](../operations/deleteApiV4VulnerabilitiesIdIssueLinksIssueLinkId.md) |
| GET | `/api/v4/projects/{id}/vulnerability_findings` | Get a list of project vulnerability findings | [View](../operations/getApiV4ProjectsIdVulnerabilityFindings.md) |
| POST | `/api/v4/vulnerabilities/{vulnerability_id}/flags/ai_detection` | Update AI SAST False Positive detection results | [View](../operations/postApiV4VulnerabilitiesVulnerabilityIdFlagsAiDetection.md) |
| GET | `/api/v4/vulnerabilities/{id}` | Get a vulnerability | [View](../operations/getApiV4VulnerabilitiesId.md) |
| POST | `/api/v4/vulnerabilities/{id}/resolve` | Resolve a vulnerability | [View](../operations/postApiV4VulnerabilitiesIdResolve.md) |
| POST | `/api/v4/vulnerabilities/{id}/dismiss` | Dismiss a vulnerability | [View](../operations/postApiV4VulnerabilitiesIdDismiss.md) |
| POST | `/api/v4/vulnerabilities/{id}/confirm` | Confirm a vulnerability | [View](../operations/postApiV4VulnerabilitiesIdConfirm.md) |
| POST | `/api/v4/vulnerabilities/{id}/revert` | Revert a vulnerability to a detected state | [View](../operations/postApiV4VulnerabilitiesIdRevert.md) |
| GET | `/api/v4/projects/{id}/vulnerabilities` | Get a list of project vulnerabilities | [View](../operations/getApiV4ProjectsIdVulnerabilities.md) |
| POST | `/api/v4/projects/{id}/vulnerabilities` | Create a new Vulnerability (from a confirmed Finding) | [View](../operations/postApiV4ProjectsIdVulnerabilities.md) |
