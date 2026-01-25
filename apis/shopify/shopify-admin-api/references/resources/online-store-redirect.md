# online-store/redirect

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/redirects.json` | Retrieves a list of URL redirects. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-redirects.md) |
| POST | `/admin/api/2020-01/redirects.json` | Creates a redirect. When you provide a full URL as the value of the path property, it will be saved as an absolute path without the domain.
          For example, "path": "http://www.johns-apparel.com/springwear" will be saved as "path": "springwear". | [View](../operations/deprecated-202001-create-redirects.md) |
| GET | `/admin/api/2020-01/redirects/count.json` | Retrieves a count of URL redirects | [View](../operations/deprecated-202001-get-redirects-count.md) |
| GET | `/admin/api/2020-01/redirects/{redirect_id}.json` | Retrieves a single redirect | [View](../operations/deprecated-202001-get-redirects-param-redirect-id.md) |
| PUT | `/admin/api/2020-01/redirects/{redirect_id}.json` | Updates an existing redirect | [View](../operations/deprecated-202001-update-redirects-param-redirect-id.md) |
| DELETE | `/admin/api/2020-01/redirects/{redirect_id}.json` | Deletes a redirect | [View](../operations/deprecated-202001-delete-redirects-param-redirect-id.md) |
| GET | `/admin/api/2020-04/redirects.json` | Retrieves a list of URL redirects. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-redirects.md) |
| POST | `/admin/api/2020-04/redirects.json` | Creates a redirect. When you provide a full URL as the value of the path property, it will be saved as an absolute path without the domain.
          For example, "path": "http://www.johns-apparel.com/springwear" will be saved as "path": "springwear". | [View](../operations/deprecated-202004-create-redirects.md) |
| GET | `/admin/api/2020-04/redirects/count.json` | Retrieves a count of URL redirects | [View](../operations/deprecated-202004-get-redirects-count.md) |
| GET | `/admin/api/2020-04/redirects/{redirect_id}.json` | Retrieves a single redirect | [View](../operations/deprecated-202004-get-redirects-param-redirect-id.md) |
| PUT | `/admin/api/2020-04/redirects/{redirect_id}.json` | Updates an existing redirect | [View](../operations/deprecated-202004-update-redirects-param-redirect-id.md) |
| DELETE | `/admin/api/2020-04/redirects/{redirect_id}.json` | Deletes a redirect | [View](../operations/deprecated-202004-delete-redirects-param-redirect-id.md) |
| GET | `/admin/api/2020-07/redirects.json` | Retrieves a list of URL redirects. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-redirects.md) |
| POST | `/admin/api/2020-07/redirects.json` | Creates a redirect. When you provide a full URL as the value of the path property, it will be saved as an absolute path without the domain.
          For example, "path": "http://www.johns-apparel.com/springwear" will be saved as "path": "springwear". | [View](../operations/deprecated-202007-create-redirects.md) |
| GET | `/admin/api/2020-07/redirects/count.json` | Retrieves a count of URL redirects | [View](../operations/deprecated-202007-get-redirects-count.md) |
| GET | `/admin/api/2020-07/redirects/{redirect_id}.json` | Retrieves a single redirect | [View](../operations/deprecated-202007-get-redirects-param-redirect-id.md) |
| PUT | `/admin/api/2020-07/redirects/{redirect_id}.json` | Updates an existing redirect | [View](../operations/deprecated-202007-update-redirects-param-redirect-id.md) |
| DELETE | `/admin/api/2020-07/redirects/{redirect_id}.json` | Deletes a redirect | [View](../operations/deprecated-202007-delete-redirects-param-redirect-id.md) |
| GET | `/admin/api/2020-10/redirects.json` | Retrieves a list of URL redirects. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-redirects.md) |
| POST | `/admin/api/2020-10/redirects.json` | Creates a redirect. When you provide a full URL as the value of the path property, it will be saved as an absolute path without the domain.
          For example, "path": "http://www.johns-apparel.com/springwear" will be saved as "path": "springwear". | [View](../operations/create-redirects.md) |
| GET | `/admin/api/2020-10/redirects/count.json` | Retrieves a count of URL redirects | [View](../operations/get-redirects-count.md) |
| GET | `/admin/api/2020-10/redirects/{redirect_id}.json` | Retrieves a single redirect | [View](../operations/get-redirects-param-redirect-id.md) |
| PUT | `/admin/api/2020-10/redirects/{redirect_id}.json` | Updates an existing redirect | [View](../operations/update-redirects-param-redirect-id.md) |
| DELETE | `/admin/api/2020-10/redirects/{redirect_id}.json` | Deletes a redirect | [View](../operations/delete-redirects-param-redirect-id.md) |
| GET | `/admin/api/2021-01/redirects.json` | Retrieves a list of URL redirects. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-redirects.md) |
| POST | `/admin/api/2021-01/redirects.json` | Creates a redirect. When you provide a full URL as the value of the path property, it will be saved as an absolute path without the domain.
          For example, "path": "http://www.johns-apparel.com/springwear" will be saved as "path": "springwear". | [View](../operations/deprecated-202101-create-redirects.md) |
| GET | `/admin/api/2021-01/redirects/count.json` | Retrieves a count of URL redirects | [View](../operations/deprecated-202101-get-redirects-count.md) |
| GET | `/admin/api/2021-01/redirects/{redirect_id}.json` | Retrieves a single redirect | [View](../operations/deprecated-202101-get-redirects-param-redirect-id.md) |
| PUT | `/admin/api/2021-01/redirects/{redirect_id}.json` | Updates an existing redirect | [View](../operations/deprecated-202101-update-redirects-param-redirect-id.md) |
| DELETE | `/admin/api/2021-01/redirects/{redirect_id}.json` | Deletes a redirect | [View](../operations/deprecated-202101-delete-redirects-param-redirect-id.md) |
| GET | `/admin/api/unstable/redirects.json` | Retrieves a list of URL redirects. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-redirects.md) |
| POST | `/admin/api/unstable/redirects.json` | Creates a redirect. When you provide a full URL as the value of the path property, it will be saved as an absolute path without the domain.
          For example, "path": "http://www.johns-apparel.com/springwear" will be saved as "path": "springwear". | [View](../operations/deprecated-unstable-create-redirects.md) |
| GET | `/admin/api/unstable/redirects/count.json` | Retrieves a count of URL redirects | [View](../operations/deprecated-unstable-get-redirects-count.md) |
| GET | `/admin/api/unstable/redirects/{redirect_id}.json` | Retrieves a single redirect | [View](../operations/deprecated-unstable-get-redirects-param-redirect-id.md) |
| PUT | `/admin/api/unstable/redirects/{redirect_id}.json` | Updates an existing redirect | [View](../operations/deprecated-unstable-update-redirects-param-redirect-id.md) |
| DELETE | `/admin/api/unstable/redirects/{redirect_id}.json` | Deletes a redirect | [View](../operations/deprecated-unstable-delete-redirects-param-redirect-id.md) |
