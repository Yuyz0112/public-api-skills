# Service Dependencies

Services are categorized into technical and business services. Dependencies can be created via any combination of these services.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/service_dependencies/associate` | Associate service dependencies | [View](../operations/createServiceDependency.md) |
| GET | `/service_dependencies/business_services/{id}` | Get Business Service dependencies | [View](../operations/getBusinessServiceServiceDependencies.md) |
| POST | `/service_dependencies/disassociate` | Disassociate service dependencies | [View](../operations/deleteServiceDependency.md) |
| GET | `/service_dependencies/technical_services/{id}` | Get technical service dependencies | [View](../operations/getTechnicalServiceServiceDependencies.md) |
