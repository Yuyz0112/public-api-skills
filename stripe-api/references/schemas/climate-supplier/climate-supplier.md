# climate.supplier

A supplier of carbon removal.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Unique identifier for the object. |
| `info_url` | string | Yes | Link to a webpage to learn more about the supplier. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `locations` | climate_removals_location[] | Yes | The locations in which this supplier operates. |
| `name` | string | Yes | Name of this carbon removal supplier. |
| `object` | enum: climate.supplier | Yes | String representing the object’s type. Objects of the same type share the same value. |
| `removal_pathway` | enum: biomass_carbon_removal_and_storage, direct_air_capture, enhanced_weathering | Yes | The scientific pathway used for carbon removal. |

