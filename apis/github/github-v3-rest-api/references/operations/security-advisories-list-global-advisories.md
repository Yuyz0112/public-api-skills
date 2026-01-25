# GET /advisories

**Resource:** [security-advisories](../resources/security-advisories.md)
**List global security advisories**
**Operation ID:** `security-advisories/list-global-advisories`

Lists all global security advisories that match the specified parameters. If no other parameters are defined, the request will return only GitHub-reviewed advisories that are not malware.

By default, all responses will exclude advisories for malware, because malware are not standard vulnerabilities. To list advisories for malware, you must include the `type` parameter in your request, with the value `malware`. For more information about the different types of security advisories, see "[About the GitHub Advisory database](https://docs.github.com/code-security/security-advisories/global-security-advisories/about-the-github-advisory-database#about-types-of-security-advisories)."

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ghsa_id` | query | string | No | If specified, only advisories with this GHSA (GitHub Security Advisory) identifier will be returned. |
| `type` | query | enum: reviewed, malware, unreviewed | No | If specified, only advisories of this type will be returned. By default, a request with no other parameters defined will only return reviewed advisories that are not malware. |
| `cve_id` | query | string | No | If specified, only advisories with this CVE (Common Vulnerabilities and Exposures) identifier will be returned. |
| `ecosystem` | query | security-advisory-ecosystems | No | If specified, only advisories for these ecosystems will be returned. |
| `severity` | query | enum: unknown, low, medium... | No | If specified, only advisories with these severities will be returned. |
| `cwes` | query | any | No | If specified, only advisories with these Common Weakness Enumerations (CWEs) will be returned.

Example: `cwes=79,284,22` or `cwes[]=79&cwes[]=284&cwes[]=22` |
| `is_withdrawn` | query | boolean | No | Whether to only return advisories that have been withdrawn. |
| `affects` | query | any | No | If specified, only return advisories that affect any of `package` or `package@version`. A maximum of 1000 packages can be specified.
If the query parameter causes the URL to exceed the maximum URL length supported by your client, you must specify fewer packages.

Example: `affects=package1,package2@1.0.0,package3@2.0.0` or `affects[]=package1&affects[]=package2@1.0.0` |
| `published` | query | string | No | If specified, only return advisories that were published on a date or date range.

For more information on the syntax of the date range, see "[Understanding the search syntax](https://docs.github.com/search-github/getting-started-with-searching-on-github/understanding-the-search-syntax#query-for-dates)." |
| `updated` | query | string | No | If specified, only return advisories that were updated on a date or date range.

For more information on the syntax of the date range, see "[Understanding the search syntax](https://docs.github.com/search-github/getting-started-with-searching-on-github/understanding-the-search-syntax#query-for-dates)." |
| `modified` | query | string | No | If specified, only show advisories that were updated or published on a date or date range.

For more information on the syntax of the date range, see "[Understanding the search syntax](https://docs.github.com/search-github/getting-started-with-searching-on-github/understanding-the-search-syntax#query-for-dates)." |
| `epss_percentage` | query | string | No | If specified, only return advisories that have an EPSS percentage score that matches the provided value.
The EPSS percentage represents the likelihood of a CVE being exploited. |
| `epss_percentile` | query | string | No | If specified, only return advisories that have an EPSS percentile score that matches the provided value.
The EPSS percentile represents the relative rank of the CVE's likelihood of being exploited compared to other CVEs. |
| `per_page` | query | integer | No | The number of results per page (max 100). For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)." |
| `sort` | query | enum: updated, published, epss_percentage... | No | The property to sort the results by. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |
| 429 | Too many requests |

**Success Response Schema:**

Array of [global-advisory](../schemas/global-advisory/global-advisory.md)

