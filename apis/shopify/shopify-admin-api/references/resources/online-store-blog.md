# online-store/blog

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/blogs.json` | Retrieve a list of all blogs. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-blogs.md) |
| POST | `/admin/api/2020-01/blogs.json` | Create a new blog | [View](../operations/deprecated-202001-create-blogs.md) |
| GET | `/admin/api/2020-01/blogs/count.json` | Get a count of all blogs | [View](../operations/deprecated-202001-get-blogs-count.md) |
| GET | `/admin/api/2020-01/blogs/{blog_id}.json` | Get a single blog by its ID | [View](../operations/deprecated-202001-get-blogs-param-blog-id.md) |
| PUT | `/admin/api/2020-01/blogs/{blog_id}.json` | Update a blog | [View](../operations/deprecated-202001-update-blogs-param-blog-id.md) |
| DELETE | `/admin/api/2020-01/blogs/{blog_id}.json` | Delete a blog | [View](../operations/deprecated-202001-delete-blogs-param-blog-id.md) |
