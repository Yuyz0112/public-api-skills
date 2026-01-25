# Standards

Standards help provide a clear understanding of what a good service configuration looks like, allowing to share and enforce organization guidelines across services to ensure adherence to best practices.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/standards` | List Standards | [View](../operations/listStandards.md) |
| PUT | `/standards/{id}` | Update a standard | [View](../operations/updateStandard.md) |
| GET | `/standards/scores/{resource_type}` | List resources' standards scores | [View](../operations/listResourceStandardsManyServices.md) |
| GET | `/standards/scores/{resource_type}/{id}` | List a resource's standards scores | [View](../operations/listResourceStandards.md) |
