# RelatedIncidentServiceDependencyRelationship

The data for a type of relationship where the Incident is related due to Business or Technical Service dependencies.

Both `dependent_services` and `supporting_services` are returned to signify the dependencies between the Services
that the Incident and Related Incident belong to.

Each Service reference returned in the list of supporting and dependent Services has a type of:
[business_service_reference, technical_service_reference].


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dependent_services` | RelatedIncidentServiceDependencyBase[] | No |  |
| `supporting_services` | RelatedIncidentServiceDependencyBase[] | No |  |

