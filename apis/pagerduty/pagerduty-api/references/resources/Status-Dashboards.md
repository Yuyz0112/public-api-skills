# Status Dashboards

Status Dashboards represent user-defined views for the Status Dashboard product that are limited to specific Business Services rather than the whole set of top-level Business Services (those with no dependent Services).


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/status_dashboards` | List Status Dashboards | [View](../operations/listStatusDashboards.md) |
| GET | `/status_dashboards/{id}` | Get a single Status Dashboard by `id` | [View](../operations/getStatusDashboardById.md) |
| GET | `/status_dashboards/{id}/service_impacts` | Get impacted Business Services for a Status Dashboard by `id`. | [View](../operations/getStatusDashboardServiceImpactsById.md) |
| GET | `/status_dashboards/url_slugs/{url_slug}` | Get a single Status Dashboard by `url_slug` | [View](../operations/getStatusDashboardByUrlSlug.md) |
| GET | `/status_dashboards/url_slugs/{url_slug}/service_impacts` | Get impacted Business Services for a  Status Dashboard by `url_slug` | [View](../operations/getStatusDashboardServiceImpactsByUrlSlug.md) |
